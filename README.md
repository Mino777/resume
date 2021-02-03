## 이력서 *<small><update 21.02.03><small>*

### 소개
- 이름: 조민호
- 나이: 1996.06.07
- 병역: 공군병장 만기제대
- 깃허브: [Github](https://github.com/Mino777)
- 이메일: jomino7777@gmail.com

> 안녕하세요, 소통을 바탕으로 협업하는 iOS 개발자, 조민호입니다.
><br> 교육 수료, 앱 런칭, 외주 프로젝트 참여 경험을 바탕으로 준비된 iOS 개발자의 역량을 발휘하고,
><br> 서버 개발자, 디자이너, 기획자와 협업한 경험을 바탕으로 원활하게 소통하는 iOS 개발자가 되겠습니다.
><br> 감사합니다.
---

### 학력

**경기대학교 스포츠산업경영학과** : 2014.03 ~ 2021.02 (졸업)

---

### 경력

**(프리랜서) 그래비룸 iOS 개발자** : 2020.12 ~ 2021.02
- iOS 개발 및 기획 참여
- Grap App 1.0.0(1) ~ 1.0.0(14) 개발

**(프리랜서) 소프트스퀘어드 iOS 개발자** : 2020.9 ~ 2020.12
- iOS 개발
- Conti App 1.0.0(1) ~ 1.0.8 앱 런칭,개발 및 유지보수
---
### 활동
- **2020.05 ~ 2020.07**
  - 소프트스퀘어드 컴공선배 라이징 프로그래머 1기 수료
    - iOS 프로그래밍, 업무 프로세스 교육 수료
    - [컴공선배 유투브 라이징 프로그래머 출연](https://www.youtube.com/watch?v=PGYyzqN3CGQ)
- **2020.03 ~ 2020.04**
  -  한국기술교육대학교 온라인평생교육원 리눅스 시스템과 네트워크 프로그래밍 교육 수료
 - **2019.09 ~ 2019.12**
	  - goorm 주최 온라인 개발자 육성 과정 DevelUP 1기 수료
		  - HTML, CSS, JavaScript, Nodejs를 이용한 웹 프로그래밍 교육 수료

---

### 외국어

- 영어
    - OPIC IM1 (2020.12.03)
    - 공식 문서를 읽고 영어로된 강의를 듣는 것에 어려움을 느끼지 않습니다.

---

### 프로젝트

## Conti

**사진을 이용한 SNS 어플리케이션**

> 현재는 AR기능이 추가되었는데, 저는 AR기능이 추가되기 직전 버전까지 개발하였습니다.

#### [AppStore](https://itunes.apple.com/app/id1537755211#?platform=iphone)

---

#### 개발 인원
- PM 1명, DL(개발 리드) 1명, DM(개발 실무자) 2명 (IOS, PHP), DL(디자이너 리드) 1명, DM(디자인 실무자) 1명

---

#### 기능
1. 카카오, 페이스북, 구글, 애플 SNS 로그인 가능 및 회원가입을 하지 않고 제한된 활동을 할 수 있는 게스트 로그인 가능.
2. Feed를 통해 팔로우한 유저들의 게시글 확인, 수정, 삭제, 좋아요, 댓글작성, 삭제, 신고, 팔로우 확인 가능
3. Search를 통해 전체 유저를 대상으로 해시태그, 검색된 게시물의 이미지 확인, 아이디 검색 가능
4. Creation을 통해 일자형, 십자형 게시글 (사진 + 글) 등록 가능, 글 작성시 #, @ 사용시에 해시태그, 멘션 가능
5. 팔로우, 좋아요, 멘션시 해당 유저에게 Push Notification 발송.
6. Notification을 통해 날짜, 시간별로 팔로우, 좋아요, 멘션 알림 확인 가능
7. Profile을 통해 팔로우, 팔로워 목록, 자신의 게시글 확인, 상대 유저 팔로우, 유저 신고&차단, 연락처를 통한 게시글 공유 가능.

---

#### 사용한 아키텍쳐

- `MVC`, `Delegation`, `Singleton`

---

#### 사용한 기술 및 라이브러리

- 형상관리: GitLab
- Tool: Slack, Google Sheets, Google Driver, Zeplin, Xcode, Postman, Sourcetree
- UI: Storyboard(Main) + Xib + Code, 다크 모드 금지 대응
- Swift5, Xcode10, TestFlight, REST API, CocoaPods, UIKit, Auto Layout, Concurrency, UserNotifications, Error Handling, Localizing, Networking, Custom Extension, Contacts
- 'Alamofire', '~> 4.9.1'
- 'AlamofireNetworkActivityIndicator', '~> 2.4.0'
- 'AlamofireObjectMapper', '~> 5.2.1'
- 'SnapKit' , '~> 5.0.1'
- 'Firebase/Analytics' , '~> 7.0.0'
- 'Firebase/Crashlytics', '~> 7.0.0'
- 'Firebase/Core', '~> 7.0.0'
- 'Firebase/Auth', '~> 7.0.0'
- 'GoogleSignIn', '~> 5.0.2'
- 'Firebase/Storage', '~> 7.0.0' (이미지, 서비스 이용약관, 개인정보 처리방침 저장)
- 'Kingfisher', '~> 5.15.7' (이미지 비동기 처리, 이미지 캐싱, downsampling, indicator 활용)
- 'FBSDKLoginKit', '~> 8.1.0'
- 'RxKakaoSDK', '~> 2.0.0-beta.3'
- 'RxSwift', '~> 5.1.1'
- 'RxCocoa', '~> 5.1.1' (Alamofire와 KakaoSDK 충돌로 인해 RxKakaoSDK 사용)
- 'Firebase/DynamicLinks', '~> 7.0.0' (친구 추천 기능을 위한 동적 링크 활용)
- 'Firebase/Messaging', '~> 7.0.0' (Push Notification 활용)
- 'Mantis', '~> 1.4.4' (Image Crop 기능에서 생산성을 높이기 위해 사용)
- 'Atributika', '~> 4.9.10' (해시태그 기능에서 NSAttributedString 터치 감지를 위해 사용)

---

#### 문제 해결

##### 0. 기본적인 문제 해결 루트
  - 공식 문서 활용
  - 구글링 / 블로그, 유투브 등 정제되지 않은 자료 활용
  - 10분간 리프레쉬 (잠깐 쉬었다가 다시 보는 경우에 해결되는 문제들이 있음)
  - 각종 커뮤니티 및 사수님께 질문 (질문하기 전에 최대한 깔끔하게 질문하려고 질문을 정제하다보면 해결되는 경우도 있음)
  - 이정도로도 안될시, 해당 태스크의 우선순위를 미루고 다른 태스크를 하며 관련 라이브러리를 찾아서 뜯어보는 등 사수님과 함께 고민

##### 1. 앱 런칭 심사때 Contacts 사용시, 디바이스에 저장을 하는 것인지, 불러와서 띄워주기만 하는 것인지에 대한 불명확성의 이유로 리젝
  - 저장하지 않고 불러와서 띄워주기만 한다고 답변 -> 해결

##### 2. 카카오 로그인을 위해 KakaoSDK 라이브러리 사용시 pod에서 Alamofire와 KakaoSDK 버전 충돌
  - RxKakaoSDK 특정 버전을 사용해 해결
  
##### 3. 해시태그 기능
  - 
  
##### 4. 알림함
  -
  
##### 5. 

---

#### 아쉬웠던 부분

- MVVM, Clean Swfit(VIP)등 다른 디자인 패턴을 적용시켜보지 못하고 MVC 패턴을 사용한 부분.
- Protocol에 대한 이해도가 부족해 적용을 못시켜본 부분.
- 확장성있는 코드에 대한 깊은 고민이 부족했던 부분.

---

## Grap

**그림일기를 통해 다양한 사람들과 일상을 공유하는 그림일기 SNS 어플리케이션**

> 기존에 있던 안드로이드 앱을 참고로 iOS MVP 개발을 진행 하였고, 추후 새로운 iOS 개발자 분 채용시에 출시 예정입니다.

#### [Google Play Store](https://play.google.com/store/apps/details?id=com.softsquared.grap&hl=en_GB)
#### AppStore 추후 출시 예정

---

#### 개발 인원
- PM 1명, AOS 2명, iOS 1명, PHP 1명, 디자이너 1명

---

#### 기능
1. 메인 탭에서 최신순, 인기순으로 유저들의 공개 그림 일기 확인 및 상세 화면에서 좋아요 가능, 탭바에서 메인 탭 터치시 최상위 인덱스로 이동 가능
2. 검색에서 유저 필명, 게시글에 포함된 내용 대상으로 검색 가능. 내 게시물 검색 가능
3. 그림 그리기 탭에서 그림 그리기 -> 일기 작성 가능
4. 그림 그리기시, 펜, 마커, 연필, 지우개, 페인트 도구 사용 가능. Custom Color Picker로 색상 선택 가능. 펜, 마커, 연필의 경우 슬라이드를 이용해 두께 조절 가능
5. 일기 작성시 제목, 날씨, 일기 내용, 글 정렬, 공개/비공개 설정 가능.
6. 마이페이지 탭에서 프로필 그림 다시 그리기, 필명 및 소개글 재작성 가능. 나의 일기 년도별, 날짜별 확인 가능. 나의 일기 공개/비공개 설정 및 삭제 가능. 자신이 좋아요한 목록 확인 가능
7. 설정에서 프로필 재설정, 좋아한 게시물, 게시물 전체 공개/비공개, 게시물 전체 삭제, 로그아웃 및 회원탈퇴 가능


---

#### 사용한 아키텍쳐

- `MVC`, `Delegation`, `Singleton`

---

#### 사용한 기술 및 라이브러리

- 형상관리: Github
- Tool: Slack, Meister Task, Notion, Google Sheets, Zeplin, Xcode, Postman, Sourcetree
- UI: No Storyboard, Xib + Code, 다크 모드 금지 대응
- Swift5, Xcode10, TestFlight, REST API, CocoaPods, UIKit, Auto Layout, Concurrency, UserNotifications, Error Handling, Localizing, Networking, Custom Extension, Canvas, Drawing, PKTool, CoreImage
- 'Alamofire'
- 'AlamofireNetworkActivityIndicator'
- 'AlamofireObjectMapper'
- 'SnapKit'
- 'Firebase/Analytics'
- 'Fabric'
- 'Crashlytics'
- 'Firebase/Core'
- 'Kingfisher'
- 'Firebase/Storage'

---

#### 문제 해결

##### 0. 기본적인 문제 해결 루트
  - 공식 문서 활용
  - 구글링 / 블로그, 유투브 등 정제되지 않은 자료 활용
  - 10분간 리프레쉬 (잠깐 쉬었다가 다시 보는 경우에 해결되는 문제들이 있음)
  - 각종 커뮤니티에 질문 (질문하기 전에 최대한 깔끔하게 질문하려고 질문을 정제하다보면 해결되는 경우도 있음)
  - 이정도로도 안될시, 해당 태스크의 우선순위를 미루고 다른 태스크를 하며 관련 라이브러리를 찾아서 뜯어보는 등 깊게 고민

##### 2.  그림 그리기 툴 커스텀

##### 3.  이미지 저장 퀄리티

##### 4.  vector image 사용

##### 5.  

##### 6. 
---

#### 아쉬웠던 부분

- Conti 개발과 병행 + 개발 일정 등을 핑계로, Conti 개발 당시에 부족했던 부분들을 개인적으로 채우지 못하고 그저 사용해봤던 기술, 라이브러리, 코드 스타일, 디자인패턴 등을 그대로 사용해 너무나도 아쉬웠음.
- Git flow를 적용시켜보고 싶었지만 혼자 작업하니까 필요없겠지 라는 핑계로 그저 master branch 사용과 커밋 메세지, 이슈만 신경쓴 부분.
