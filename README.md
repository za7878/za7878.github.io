#### 20210512(수) 작업내역
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