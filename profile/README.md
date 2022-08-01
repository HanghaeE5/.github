# TODO WITH

## 📌 링크
[TodoWith 링크](https://todowith.co.kr)  
[Front-End Repo 링크](https://github.com/HanghaeE5/Front-end)  
[Back-End Repo 링크](https://github.com/HanghaeE5/Back-end)  
[Notion 링크](https://www.notion.so/99-E-5-35d0ee3dd2054d5aa4e2c2515c1f4f45)  
[소개 영상](URL)  

## 🎬 프로젝트 소개
-  우리는 하루에도 수 많은 일들을 합니다. 할 일을 쉽게 기록하고 확인할 수 있는 것이 있다면 얼마나 좋을까요? 우리의 서비스 TODOWITH 은 쉽고 재미있게 TODO 를 수행할 수 있도록 도와주는 여러분들의 친구입니다.

## ⏳ 프로젝트 기간
### 2022년 6월 24일 - 2022년 8월 5일
## 🙏 팀원
|이름|포지션|깃허브 or 블로그|담당|
|:---:|:---:|:---:|:---|
|심아영|Front-End|https://github.com/ccimayoung|[부리더]</br>1. CICD/무중단배포 </br>2. 로그인/회원가입/온보딩 </br>3. 메인페이지 </br>4. 채팅 </br>5. 친구목록/친구페이지 </br>6. 알림(개발중)|
|조윤경|Front-End|||
|김지환|Back-End|https://github.com/Kimjipang|[리더]</br>1. 커뮤니티 CRUD</br>2. To Do 정렬 코드 변경 </br>3. 알림 기능(간단한 알림 테스트 O , 프로젝트에 구현은 X)|
|이건우|Back-End|https://github.com/geonoo|1. CICD / 무중단배포</br>2. 로그인(일반, 소셜)</br>3. 이벤트 기능(스케줄러, 랜덤뽑기)</br>4. 커뮤니티 검색|
|양희수|Back-End|https://github.com/hee1su123|1. 채팅(WebSocket, Redis)</br>2. 친구추가 기능</br>3. To-do 리스트</br>4. 캐릭터 및 아이템 기능|
|박혜진|DESIGNER||1. 소개페이지</br>2. 투두리스트페이지</br>3. 커뮤니티 페이지</br>4. 친구목록페이지</br>5. 채팅페이지</br>6. 캐릭터선택페이지</br>7.이벤트 배너 및 상세페이지|
|최민영|DESIGNER|||

## 🎁 주요 기능

### 😃 간단하고 안전한 회원가입
- 구글, 네이버, 카카오를 통한 소셜 로그인 및 이메일 인증을 통한 회원가입
- 페이지 설명
    - 소셜 or 일반로그인
    - 온보딩페이지(온보딩 페이지를 통해 투두윗이 어떠한 서비스인지 알 수 있음)
    - PWA 다운가능  
![로그인/회원가입](https://github.com/HanghaeE5/.github/blob/main/image/login.png)

### 😃 메인 페이지 
- 페이지 설명
    - 메인페이지에서 캐릭터 gif를 볼수있음.(2가지 캐릭터)
    - 캐릭터와 아이템은 스텝에 따라 변화함으로써, 사용자에게 To Do 달성을 더 재미있게 할 수 있도록 흥미와 동기를 부여함.  
![메인 페이지](https://github.com/HanghaeE5/.github/blob/main/image/main.png)

### 😃 계획 작성, 목표 달성을 위한 TO-DO 리스트 작성
- 구글, 네이버, 카카오를 통한 소셜 로그인 및 이메일 인증을 통한 회원가입
- 페이지 설명
    - 소셜 or 일반로그인
    - 온보딩페이지(온보딩 페이지를 통해 투두윗이 어떠한 서비스인지 알 수 있음)
    - PWA 다운가능  
![Todo 리스트](https://github.com/HanghaeE5/.github/blob/main/image/Untitled.png)

### 😃 커뮤니티를 통한 위드투두 진행 및 일상 공유
- 커뮤니티에서 TO-DO 를 함께 진행할 사람들을 모을 수 있음.
- 페이지 설명
    - 단체채팅방을 참여하여 함께 TO-DO 를 진행하는 사람들과 소통이 가능함.  
![커뮤니티](https://github.com/HanghaeE5/.github/blob/main/image/Untitled%20(1).png)

### 😃 친구와 함께 공유 가능한 TO-DO 리스트 및 캐릭터
- 친구 추가 후 TO-DO 리스트 공유 가능😃 친구와 소통하며 함께 TO-DO 를 진행할 수 있는 채팅방
- 페이지 설명
    - 닉네임을 통해 친구 요청(받은 사람은 수락 또는 거절 가능)
    - 친구 페이지에서 캐릭터, 보유 아이템, 당일 투두를 볼 수 있으며 친구가 비공개로 해놓은 경우에는 볼 수 없음.  
![친구](https://github.com/HanghaeE5/.github/blob/main/image/Untitled%20(2).png)

### 😃 채팅 페이지
- 커뮤니티의 With To Do 기능을 통해 함께 TO-DO 를 진행 중인 사람들 또는 친구와의 일대일 채팅 가능
- 페이지 설명
    - 새로운 메시지가 온 순서대로 채팅방이 정렬됨.
    - 영구적 저장 DB(늦게 들어온 사용자도 채팅방의 모든 내용을 확인 가능함)  
![채팅](https://github.com/HanghaeE5/.github/blob/main/image/Untitled%20(3).png)

### 😃 나만의 프로필 사진과 닉네임
- 프로필 사진과 닉네임을 변경할 수 있음.
- 페이지 설명
    - 닉네임 중복 확인이 가능하며, 프로필 사진을 설정할 수 있음.
    - 비밀번호 변경  
![프로필](https://github.com/HanghaeE5/.github/blob/main/image/Untitled%20(4).png)

### 😃 TO-DO 완료하고 상품을 받을 수 있는 이벤트
- 오늘의 TO-DO 를 전부 완료 시(당일 날짜로 지정한 미완료 TO-DO가 없어야 함) 도장을 받을 수 있음
- 도장의 개수가 누적 3개가 모이면, 응모권으로 교환하여 이벤트 참여 가능
- 페이지 설명
    - 다양한 상품의 기프티콘 랜덤 당첨  
![이벤트](https://github.com/HanghaeE5/.github/blob/main/image/Untitled%20(5).png)

## 🔨 아키텍처 / 기술 스택
![Architecture](https://github.com/HanghaeE5/.github/blob/main/image/architecture.jpg)

<details>
<summary>Front-End</summary>
<div markdown="1">

</div>
</details>

<details>
<summary>Back-End</summary>
<div markdown="1">

| 사용 기술 | 기술 선정 이유 및 설명 |
| --- | --- |
| spring-security | 인증 및 리소스 권한을 직접 소스로 만들게 되면 많은시간이 소요되기 때문에 사용 |
| spring-mail | 이메일 인증 관련 |
| oauth2 | 소셜 로그인  |
| websocket | • 양방향 통신이 필요한 채팅 기능을 구현하기 위해 선정</br>• 요청이 오면 응답을 하는 http 프로토콜과 달리 연결상태를 유지하여 실시간 상호작용 가능</br>• Polling, Long Polling, Streaming 방식으로 비슷한 효과를 보일 수는 있지만, 이들은 불필요한 트래픽이 야기함. |
| stomp | • Spring Framework 에서 사용 가능( 써본적 없는 NodeJs 를 배워서 하는 것 보다 Spring 에서 구현해 보는 것이 더 좋다고 판단 )</br>• pub/sub 방식으로 작동해 송/수신 처리가 명확</br>• 여러 브로커를 사용 가능 (메모리, Rabbitmq, Kafka, Redis 등등) |
| swagger | • Spring REST Docs라는 문서화 도구와는 달리 Swagger는 코드 몇 줄만 추가하면 만들 수 있고, 적용하기가 쉬움.</br>• 테스트 할 수 있는 UI를 제공 → Spring REST Docs는 테스트를 돌리면서 성공 여부를 확인하지만 Swagger는 문서 화면에서 바로 API 테스트 가능함. |
| Querydsl | • 문자가 아닌 코드로 쿼리를 작성함으로써, 컴파일 시점에 문법 오류를 쉽게 확인할 수 있다.</br>• 자동 완성 등 IDE의 도움을 받을 수 있다.</br>• 동적인 쿼리 작성이 편리하다.</br>• 쿼리 작성 시 제약 조건 등을 메서드 추출을 통해 재사용할 수 있다. |
| aws-s3 upload  | • 저장 용량이 무한대이고 파일 저장에 최적화되어 있다. 용량을 추가하거나 성능을 높이는 작업이 필요 없음</br>• 다른 설치 파일 없이 HTTP 프로토콜로 파일 업로드/다운로드 처리 가능</br>• 비용이  저렴 |
| MySQL Full Text Search(MATCH ~ AGAINST) | • LIKE 검색 개선 |
| nGrinder / JMeter | • 부하 테스트 |
| Redis | • Redis 의 Pub/Sub 기능을 활용해 서로 다른 서버에서도 Stomp 프로토콜 활용이 가능</br>• 메인 서버가 다운되더라도 채팅 메시지를 보존 가능 |
| Github Action | • 코드를 배포해야하는 상황이 빈번히 발생하고 배포 시에 잠깐 서버가 중단되는 상황을 개선하기 위해 고려함.</br>• Jenkins와 Github Action 2가지를 고려했지만 Jenkins 를 사용하려면 도커에 설치해야 함. 더불어, 여러 절차가 필요</br>• Github Action 은 설치 없이 간단하게 적용 할 수 있었기에 같은 기능을 한다면 간단하게 적용할 수 있는 Github Action을 선택함. |

</div>
</details>