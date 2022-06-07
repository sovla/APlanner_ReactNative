## 에이플래너(애가인)

### 파일 구조

-   src
    -   Api [ api 관련된 폴더 ]
    -   assets [ image,css 파일 ]
    -   Component [ 컴포넌트 폴더, 주요기능 - 이름 으로 분류 되어있습니다. ]
    -   Container [ 컨테이너 폴더, 페이지 기능 ]
    -   Route [ 앱 라우팅 작업 되어있는 파일 ]
    -   State [ 전역 상태 ]
    -   utils [ 각종 Util 파일 ]

### 플로우

-   안드로이드

    -   1. 앱 설치후 QR코드(다이나믹 링크)를 찍는다
    -   2. 다이나믹 링크를 통해 시설정보를 받아와 설정이 되고, 로그인
    -   3. 사전 점검 방문 예약, 나의 접수 현황 메뉴 선택 가능

-   IOS

    -   1. 앱 설치후 로그인 화면에서 시설 정보를 선택한다.
    -   2. 안드로이드와 동일
    -   3. 안드로이드와 동일

### 앱 라우팅

구조는 [ 대분류 / 소분류 or 파일 ]

-   Container.js : 전체 라우팅 관리 및 시설 정보 받아오기 기능 작업 페이지
-   Check.js : 사전 점검 방문 예약 안내 페이지
-   CheckCalendar.js : 사전 점검 방문 예약 날짜 선택 페이지
-   CheckTime.js : 사전 점검 방문 예약 시간 선택 페이지
-   Complain.js : 불만 사항 접수 페이지
-   ComplainAdd.js : 불만 사항 추가 접수 페이지
-   ComplainList.js : 불만 사항 리스팅 페이지
-   ComplainUpdate.js : 불만 사항 수정 페이지
-   Home.js : 로그인후 메뉴 페이지
-   Login.js : 로그인 페이지
-   MoveIn.js : 입주 예약 날짜 선택 페이지
-   MoveInTime.js : 입주 예약 시간 선택 페이지
-   Reception.js : 나의 접수 현황 페이지

### 참고

-   기존 기획은 사전 점검 예약, 입주 예약, 불만 사항 접수 기능이 있엇으나 현재는 사전 점검 예약 기능만 사용하도록 되어 있습니다. 추후에 불만 접수 기능 추가할 예정으로 알고있습니다.
