#### 작업예정 : JQuery 제이쿼리 JSON 데이터 파싱
-외부 data.js 파일에서 json데이터를 저장한 후 html에서 불러와 파싱.
-외부 사이트에서 제공하는(RestAPI) json데이터를 html에서 불러와 파싱.
-RestAPI 서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱(데이터를
분해해서 화면에 뿌려주는 작업)
-RestAPI서버 주소(빅데이터): https://coroname.me/getdata

#### 2021.05.13(목) 작업내용
-픽사베이 이미지 3개: 로고1, 슬라이드 이미지 1, Noimage1 받고, 경로 적어놓기
- 로고 : https://pixabay.com/ko/vectors/%EC%9E%90%EB%8F%99-%EC%84%B8%ED%94%BC%EC%95%84-%EC%9E%90%EB%8F%99%EC%B0%A8-%ED%8F%89%EB%A9%B4-3071895/
-슬라이드  이미지 : https://pixabay.com/ko/illustrations/%EB%88%88%EC%82%AC%EB%9E%8C-%EC%9E%A5%EB%82%9C%EA%B0%90-%EB%88%88-%ED%81%AC%EB%A6%AC%EC%8A%A4%EB%A7%88%EC%8A%A4-1090261/
-Noimage :https://pixabay.com/ko/vectors/%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EA%B8%88%EC%A7%80-%EC%95%88-%ED%95%A8-%EC%97%86%EC%9D%8C-308637/

-작업폴더를 나누는 이유: 시청(관공서), 대학, 기업의 웹프로그램(사이트)
제작 할때, 1년간 무상 유지보수 이후 보통 2천 리뉴얼 4천 비용이 책정
-home 폴더 기존작업물, 리뉴얼 home에 덮어쓰는 방식이 아니고,
-리뉴얼 할때 home2022 폴더에 작업을 하게 된다.
-제이쿼리 코어 다운받기: min버전(압축-속도UP), 일반버전(개발-속도 Normal)
-애니데스크(독일산):팀뷰어(독일산)
- html5, html. css.thml, Js.html 까지
-JQuery 기본구조만 실습

#### 20210512(수) 작업내역
-JQuery 미처리 작업은 다음주 하고,
-오늘부터는 모바일 메인 페이지 1개 만들어서 과제물로 제출 -> 스프링에서
프로그램 입히는 소스로 사용하게 된다.
-git clone 으로 프로젝트를 가져온 경우 아래 내용을 추가해 줘야 함.
-git config --list  확인해서 user.name, user.email 없으면 아래 추가.
터미널에서 아래 2가지 실행
-git config --local user.name (사용자이름)
-git cinfig --local user.email (사용자메일)

#### 20210511(화) 작업내역
-로렘 입숨 한글URL : http://guny.kr/stuff/klorem/#/table-html
-로렘 입숨 영어URL : https://loremipsum.io/generator/
-URL경로(path): /루트, /test/html5.
-html5의 레이아웃 구조 제작.
-서버(응답하는프로그램=respones) = 아파치서버, 톰캣서버
-클라이언트(요청하는프로그램=request) = 웹브라우저
-HTML은 마크업이 태그로 구성됩니다.<의미있는 문자>...</의미있는문자>
- http://127.0.0.1:80[8080/9000/5500/6500
- PC의 네트워크 내부주소(공통): 127.0.0.1 == localhost
-고유주소: yahoo.com(도메인) == 74.6.143.25(IP주소) ==주민번호
- IP주소버전: IPv4, IPv6
-HTML도 버전: HTML5, HTML4.01(old)

#### 20210510(월) 작업내역
업로드장치 1. 커밋(commit) 2. 푸시(push)
다운로드 장치 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업 할 상황
리포지토리(저장) 초기화: git init
개발자 pc (html) 과 깃 저장소와 연결
포트의 역할이 트렌드로 많이 사용됨.
포트(port) : 포트번호로 서비스를 만드는 것이 트렌드
이전에는 go 포트에 모은 서비스를 붙여놓았습니다.
모든 서비스를 개발부 분리하는 트렌드가 있습니다.
마이크로 서비스라고 합니다. ==RostAPI로 구현이 됩니다.
도메인(https:naver.com:1451241/네이버 인증서비스 개발)
외부 인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용
    html : Hyter text MarkUp Language 태그를 사용하는 언어
    md : MarkDown Laguage 태그를 사용하지 않는 언어git remote add origin