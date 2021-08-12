<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tab</title>
    <link rel="stylesheet" href="/reset.css">
    <style>
        html{font-size: 62.5%;}
        section>div{
            position: relative;
            margin: 0 auto;
            width: 64.4rem;height: 34.5rem;
        }
        section>div>h2{
            position: relative;
            float: left; padding: 0 2rem;
            font: bold 2rem/6.6rem "Malgun gothic",sans-serif;
            color: #848998;
        }
        section>div>div{
            position: absolute; left: 0;top: 6.6rem;
            border-top: 0.1rem solid #dadada;
            width: 100%; height: 27.9rem;
            background: white;
        }
        section>div>div>dl{
            margin-left: 1.8rem;
            letter-spacing: -0.1rem;
        }
        section>div>div>dl>dt{
            margin-top: 2.4rem;margin-bottom: 1.7rem;
        }
        section>div>div>dl>dt>a{
            color: #333;
        }
        section>div>div>dl>dd{
            overflow: hidden;
            height: 1.5rem; white-space: nowrap; text-overflow: ellipsis;
            font: 1.5rem/1.5rem 'Malgun Gothic',sans-serif; color: #4a4a4a;
        }
        section>div>div>ul{
            margin-top: 4.3rem;padding-top: 1.3rem;
            background: url(https://lll.gm.go.kr/site/lll/images/main/board_pattern.png)repeat-x 0 0;
            letter-spacing: -0.1rem;
            font: 1.6rem/3.6rem 'Malgun Gothic',sans-serif;
        }
        section>div>div>ul>li{
            height: 3.6rem;
        }
        section>div>div>ul>li>a{
            position: relative;
            float: left;
            padding-left: 1.7rem;
            width: 54.5rem;
            color: #333;
        }
        section>div>div>ul>li>a::before{
            position: absolute; left: 0; top: calc(50% - 0.2rem);
            width: 0.3rem; height: 0.3rem; background: #cb2621;
            content: "";
        }
        section>div>div>ul>li>span{
            overflow: hidden;
            display: block; width: 42rem;white-space: nowrap;text-overflow: ellipsis;
        }
        section>div>div>ul>li>time{
            float: right;
        }
        section>div>p{
            position: absolute; right: 0; top: 2.3rem; width: 1.8rem; height: 1.8rem;
            background: url(https://lll.gm.go.kr/site/lll/images/main/main_sprite.png)no-repeat 0 -15.9rem;
            font-size: 0; line-height: 0;
        }
        section>div>p>a{
            display: block;
            height: 1.8rem;
        }

        /*이벤트*/
        section>div>h2.on{
            font-size: 2.3rem; color: #ec6624;
        }
        section>div>h2.on::before{
            position: absolute;z-index: 100; left: 0; bottom: -0.1rem;
            border-bottom: 0.3rem solid #ec6624;
            width: 100%; height: 0;
            content: ""; 
        }
        section>div>h2.on::after{
            position: absolute;z-index: 100; left:calc(50% - 0.3rem); bottom: 0.2rem;
            border: 0.6rem solid #fff;
            border-bottom-color: #ec6624;
            width: 0; height: 0;
            content: ""; 
        }
        section>div>div.on{z-index: 10;}
        section>div>p.on{z-index: 10;}
    </style>
</head>
<body>
    <h1>탭 메뉴</h1>
    <section>
        <h1>notice</h1>
        <!--div>(h2+(div>(dl>dt+dd)+(ul>li*4>(a>span)+time))+p>a)*3-->
        <div>
            <h2 class="on">공지사항</h2>
            <div class="on">
                <dl>
                    <dt><a href="#">2021 광명시 미디어학교 - &lt;1인 미디어&gt;, &lt;청년 원데이클래스&gt; 안내</a></dt>
                    <dd>
                        디지털 시대, 무엇보다도 필수적인 미디어 활용능력! 초보자도 쉽게 브이로그와 팟캐스트를 만...
                    </dd>
                </dl>
                <ul>
                    <li><a href="#"><span>평생학습도서관 일요 도서관 활동가 모집</span></a>
                        <time datetime="2021-08-05">2021.08.05</time></li>
                    <li><a href="#"><span>평생학습원 「일요일 확대」 운영 안내</span></a>
                        <time datetime="2021-08-04">2021.08.04</time></li>
                    <li><a href="#"><span>2021년 하반기 광명시 평생학습원 학습모임방(동아리실) 대... </span></a>
                        <time datetime="2021-07-30">2021.07.30</time></li>
                    <li><a href="#"><span>2021년 평생학습원 평생학습체험 청년인턴 추가모집 안내</span></a>
                        <time datetime="2021-07-27">2021.07.27</time></li>
                </ul>
            </div>
                <p class="on"><a href="#">공지사항 더보기</a></p>
            <h2>평생학습소식</h2>
            <div>
                <dl>
                    <dt><a href="#">누구나 우리는 평생학습도시, 시민주도형 평생학습축제 ... </a></dt>
                    <dd>
                        관련뉴스 : httdd://news.gm.go.kr/news/articleView.html?idxno=16223 광명시는 전국 지자체 최초 '평생학습도...
                    </dd>
                </dl>
                <ul>
                    <li><a href="#"><span>'광명시 평생학습축제 추진위원회' 위원 위촉</span></a>
                        <time datetime="2021-08-09">2021.08.09</time></li>
                    <li><a href="#"><span>광명시 평생학습원 8월 8일 일요일 운영 시작!</span></a>
                        <time datetime="2021-08-08">2021.08.08</time></li>
                    <li><a href="#"><span>광명시민 평생학습장학금, '만25세 이상 20만원 지급안' 채택</span></a>
                        <time datetime="2021-08-08">2021.08.08</time></li>
                    <li><a href="#"><span>광명시 평생학습원, 일요일도 운영합니다.</span></a>
                        <time datetime="2021-08-03">2021.08.03</time></li>
                </ul>
            </div>
                <p><a href="#">평생학습소식 더보기</a></p>
            <h2>동아리활동후기</h2>
            <div>
                <dl>
                    <dt><a href="#">광명 2동 2020년 " 사랑의 김장 나눔 " 행사에 자원봉사 다... </a></dt>
                    <dd>
                        2020년 "사랑의 김장 나눔 " 행사는 모두에게 백신보다 강력한 역할 장기간 코로나 19로 너무 ...
                    </dd>
                </dl>
                <ul>
                    <li><a href="#"><span>노을소리샘 첫 길거리 공연</span></a>
                        <time datetime="2020-11-17">2020.11.17</time></li>
                    <li><a href="#"><span>안양 중앙시장 행사</span></a>
                        <time datetime="2020-08-21">2020.08.21</time></li>
                    <li><a href="#"><span>2020.8.19.민주야,같이 놀자!-7차시-푸른 작은도서관</span></a>
                        <time datetime="2020-08-19">2020.08.19</time></li>
                    <li><a href="#"><span>2020.8.19.민주야, 같이 놀자!-7차시-푸른 작은도서관</span></a>
                        <time datetime="2020-08-19">2020.08.19</time></li>
                </ul>
            </div>
                <p><a href="#">동아리활동후기 더보기</a></p>
        </div>
    </section>
</body>
</html>
