# 오픈소스 조사

Date Created: November 2, 2022 9:08 AM
Status: 진행 중

- AR인테리어 관련
    - Unity: AR 개발 툴킷
        - 라이선스: 사유
        - 종류: 게임 엔진
        - 프로그래밍 언어: C#, C++
        - **유니티**(Unity)는 3D 및 2D 비디오 게임의 개발 환경을 제공하는 게임 엔진이자, 3D 애니메이션과 건축 시각화, 가상현실(VR) 등 인터랙티브 콘텐츠 제작을 위한 통합 제작 도구이다.
    - Three.js
        - 라이선스: MIT
        - 종류: 자바스크립트 라이브러리
        - 프로그래밍 언어: 자바스크립트
        - 저장소: [github.com/mrdoob/three.js](https://github.com/mrdoob/three.js)
        - Three.js는 웹 브라우저에서 3차원 컴퓨터 그래픽스 애니메이션 응용을 만들고 표현하기 위해 사용되는 자바스크립트 라이브러리이자 API이다. 오픈 소스 프로젝트로 깃허브에서 공개되어 있다.
        - Three.js는 특정 웹 브라우저나 플러그인에 의존하지 않고 자바스크립트 언어를 사용하여 웹 컨텐츠의 한 부분으로서 그래픽 처리 장치(GPU)에서 가속되는 3차원 컨텐츠를 만들 수 있도록 해 준다. 이는 WebGL의 출현으로 인하여 가능하게 되었다.
    - MAXST
        - MAXST AR SDK
        - 라이선스: 사유
            - 인식 대상, 추적 방식, 개발 환경과 필요에 따라 선택할 수 있는 모든 ***AR*** 기능을 제공한다.
            - 가상공간과 증강현실을 연결한 플랫폼 개발에 기능 지원을 해준다.
        - https://github.com/armaxst/MaxstARSDK_5.0_Unity_Sampleapp
            - github에서 Unity_Sampleapp다운로드 가능
    
- 백엔드
    
    오픈소스 관계형 DB
    
    - MySQL
    - PostgreSQL
    - MariaDB
    
    오픈소스 **NoSQL(비관계형) DB**
    
    - **MongoDB**
        - **라이선스: SSPL**
        - 종류: 도큐먼트 지향 데이터베이스
        - 저장소: [github.com/mongodb/mongo](https://github.com/mongodb/mongo)
        - **몽고DB**(MongoDB←HUMONGOUS)는 크로스 플랫폼 도큐먼트(문서) 지향 데이터베이스 시스템이다. NoSQL 데이터베이스로 분류되는 몽고DB는 JSON과 같은 동적 스키마형 도큐먼트들(몽고DB는 이러한 포맷을 BSON이라 부름)을 선호함에 따라 전통적인 테이블 기반 관계형 데이터베이스 구조의 사용을 삼간다. 이로써 특정한 종류의 애플리케이션을 더 쉽고 더 빠르게 데이터 통합을 가능케 한다. 아페로 GPL과 아파치 라이선스를 결합하여 공개된 몽고DB는 자유-오픈 소스 소프트웨어이다.
        - 비관계형 DB
            
            **특징**
            
            - 관계형DB의 단점을 보완하기 위해 나온 DB.
            - 거대한 Map으로서 key-value 형식을 지원함.
            - 관계형 db와 달리 PK,FK JOIN등 관계를 정의하지 않음.
            - 스키마에 대한 정의가 없다.
            
            **장점**
            
            - 대용량 데이터 처리를 하는데 효율적임.
            - 읽기 작업보다 쓰기 작업이 더 빠르고 관계형 데이터베이스에 비해 쓰기와 읽기 성능이 빠름.
            - 데이터 모델링이 유연함.
            - 뛰어난 확장성으로 검색에 유리함.
            - 최적화된 키 값 저장 기법을 사용하여 응답속도나 처리효율 등에서 성능이 뛰어남.
            - 복잡한 데이터 구조를 표현할 수 있음.
    - CouchDB
    - Cassandra
- 프론트엔드
    - jQuery
        - 라이선스: MIT
        - 종류: 자바스크립트 라이브러리
        - 저장소: [github.com/jquery/jquery](https://github.com/jquery/jquery)
        - **jQuery**(제이쿼리)는 **HTML의 클라이언트 사이드 조작을 단순화** 하도록 설계된 크로스 플랫폼의 자바스크립트 라이브러리다. 존 레식이 2006년 뉴욕 시 바캠프(Barcamp NYC)에서 공식적으로 소개하였다.
            
            jQuery는 MIT 라이선스를 가진 자유 오픈 소프트웨어이다. jQuery의 문법은 코드 보기, 문서 객체 모델 찾기, 애니메이션 만들기, 이벤트 제어, Ajax 개발을 쉽게 할 수 있도록 디자인되었다. 또한, jQuery는 개발자가 플러그인을 개발할 수 있는 기능을 제공한다.
            
- 기타
    - 채팅: Rotket.Chat
        - 라이선스: MIT
        - Rocket.Chat 은 HipChat, Slack 형태의 중소규모 그룹을 위한 오픈소스 메신저 서버/클라이언트 프로그램이다.
            
            실시간 채팅을 할 수 있고, 음성과 화상채팅도 가능하다. 다양한 서버 OS를 지원하고 있으며, Raspberry PI 2에 설치도 가능하다. 클라이언트 프로그램으로는 PC(Electron - Windows/macOS/Linux)와 모바일 앱(iOS/Android)이 이미 준비되어 있다.
            
    - 지도: 오픈스트리트맵(OSM)
        - OpenstreetMap은 무료로 편집 가능한 전 세계의 오픈 콘텐츠 라이센스로 출시된 지도이다.
        - 라이선스: 지도 이미지와 편집을 위한 바탕지도 데이터를 무료 (또는 거의 무료) 로 사용하는 것을 허용하고 있다.
            
            라이런스 설명 링크: [https://www.openstreetmap.org/copyright](https://www.openstreetmap.org/copyright)
            
            OpenStreetMap®은 *오픈 데이터* OpenStreetMap 재단 (OSMF)의 오픈 데이터 커먼즈 오픈 데이터베이스 라이선스(ODbL)에 따라 사용할 수 있다.
            
            OpenStreetMap 기여자를 명시하는 한, OpenStreetMap 데이터를 자유롭게 복사, 배포, 전송 및 적용할 수 있다. 데이터를 바꾸거나 데이터를 기초로 작업할 때는 오로지 같은 라이선스에 따라서만 결과를 배포할 수 있다. 전문은 당신의 권리와 책임을 설명한다.
            
            설명문서는 크리에이티브 커먼즈 저작자표시-동일조건변경허락 2.0 라이선스(CC BY-SA)에 따라 사용할 수 있다.
            
    - 프론트엔드 아이콘: Font-awesome
        - 라이선스: *무료* 버전(최대 4개까지 의 모든 릴리스 및 5개까지의 무료 버전)은 SIL Open Font License 1.1, Creative Commons Attribution 4.0 및 MIT License 에 따라 사용할 수 있다.
        - 웹 사이트 구축에서 필요한 아이콘들을 사용할 수 있는 무료 오픈소스이다. 비록 더 많은 기능을 사용하기 위해서는 유료로 구매해야 하지만 무료 버전으로도 대부분의 웹 사이트에서는 크게 문제가 없다.
        - 폰트 어썸 자세한 사용법
            
            [Font Awesome](https://fontawesome.com/)
            
        - [[Html] 웹 폰트 아이콘 Font Awesome(폰트 어썸) 사용법](https://coding-factory.tistory.com/192)
- 오픈소스 올려져있는 사이트
    - ****[OSDN (https://ko.osdn.net/)](https://ko.osdn.net/)****
        - OSDN은 오픈 소스 소프트웨어 프로젝트를 저장해놓은 웹사이트 입니다. 55,000개가 넘는 방대한 프로젝트들이 있습니다.
    - ****[SOURCEFORGE (https://sourceforge.net/)](https://sourceforge.net/)****
        - 소스포지는 소프트웨어 개발자들을 위해 열려있는, 오픈 소스 소프트웨어 개발관리를 위한 웹사이트입니다. 무수히 많은 오픈 소스들이 있으며 매일 4백만 건 이상의 다운로드와 월간 3천만 명이 넘는 사용자가 이용하는 대형 사이트입니다. 또한 검색 기능과 다운로드에 대한 통계도 공개되어 있어 오픈 소스에 대한 인기 여부도 판단하실 수 있습니다.
    - ****[Awesome Open Source (https://awesomeopensource.com/)](https://awesomeopensource.com/)****
        - 깃허브는 어마어마하게 많은 소스들이 있지만 완성도가 높은 소스들을 찾기는 결코 쉽지 않습니다. Awesome Open Source 사이트는 이러한 문제점을 해결하고자 깃허브의 많은 오픈소스 중 완성도가 높은 것들만 정리해둔 사이트입니다. 각각의 기술별로 목록 형태로 잘 분류되어 있습니다.
    - ****[Bootstrap (https://getbootstrap.com/)](https://getbootstrap.com/)****
        - Bootstrap은 세계적으로 반응형 웹 사이트 구축할때 사용되는 가장 인기 있는 프레임워크이다. 기본적으로 반응형 웹 기반의 HTML, CSS javascript파일을 제공한다. 뿐만 아니라 데모 사이트를 제공하고 커스텀마이징 가능한 예제를 제공해준다.