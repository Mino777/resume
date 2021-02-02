## 이력서 *<small><update 21.02.03><small>*

#### 소개
- 이름: 조민호
- 나이: 1996.06.07
- 깃허브: [Github](https://github.com/Mino777)
- 이메일: jomino7777@gmail.com

> 안녕하세요, 소통을 바탕으로 협업하는 iOS 개발자, 조민호입니다.
><br> 교육 수료, 앱 런칭, 외주 프로젝트 참여 경험을 바탕으로 준비된 iOS 개발자의 역량을 발휘하고,
><br> 서버 개발자, 디자이너, 기획자와 협업한 경험을 바탕으로 원활하게 소통하는 iOS 개발자가 되겠습니다.
><br> 감사합니다.
---

#### 학력

**경기대학교 스포츠산업경영학과** : 2014.03 ~ 2021.02 (졸업)

---

#### 경력

**(프리랜서) 소프트스퀘어드 IOS 개발자** : 2020.9 ~ 2020.12
- iOS 개발
- Conti App 1.0.0(1) ~ 1.0.8 앱 런칭,개발 및 유지보수

**(프리랜서) 그래비룸 IOS 개발자** : 2020.12 ~ 2021.02
- iOS 개발
- Grap App 1.0.0(1) ~ 1.0.0(14) 개발

---
#### 활동

- **2019.09 ~ 2019.12**
  - goorm 주최 온라인 개발자 육성 과정 DevelUP 1기 수료
    - HTML, CSS, JavaScript, Nodejs를 이용한 웹 프로그래밍 교육 수료
- **2020.04 ~ 2020.04**
  -  한국기술교육대학교 온라인평생교육원 리눅스 시스템과 네트워크 프로그래밍 교육 수료
- **2020.05 ~ 2020.07**
  - 소프트스퀘어드 컴공선배 라이징 프로그래머 1기 수료
    - iOS 프로그래밍, 업무 프로세스 교육 수료
    - [컴공선배 유투브 라이징 프로그래머 출연](https://www.youtube.com/watch?v=PGYyzqN3CGQ)

---

#### 외국어

- 외국어
  - 영어
    - OPIC IM1 (2020.12.03)
    - 공식 문서를 읽고 영어로된 강의를 듣는 것에 어려움을 느끼지 않습니다.

---

#### 프로젝트

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
2. Feed를 통해 친구들의 게시글 확인, 수정, 삭제, 좋아요, 댓글작성, 팔로우 확인, 유저 신고&차단 가능
3. Search를 통해 전체 유저를 대상으로 해시태그, 검색된 게시물의 이미지 확인, 아이디 검색 가능
4. Creation을 통해 일자형, 십자형 게시글 (사진 + 글) 등록 가능, 글 작성시 #, @ 사용시에 해시태그, 멘션 
5. 팔로우, 좋아요, 멘션시 해당 유저에게 Push Notification 발송.
6. Notification을 통해 팔로우, 좋아요, 멘션 알림 확인 가능
7. Profile을 통해 팔로우, 팔로워 목록, 자신의 게시글 확인, 상대 유저 팔로우, 유저 신고&차단, 연락처를 통한 게시글 공유 가능.

---

#### 사용한 아키텍쳐

- `MVC`, `Delegation`, `Singleton`

---

#### 사용한 기술 및 라이브러리

- 형상관리: GitLab
- Tool: Slack, Google Sheet, Google Driver, Zeplin, Xcode, Postman, Sourcetree
- UI 구성: Storyboard(Main) + Xib + Code, 다크 모드 금지 처리
- `Swift5`, `Xcode10`, `TestFlight`, `REST API`, `UIKit`, `Auto Layout`, `UserNotifications`, `Error Handling`, `Localizing`, `Networking`, `Custom Extension`,`Contacts`
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

