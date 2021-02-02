##  조민호

1996.06.07

현재 iOS 개발자가 되기 위해 준비하고 있습니다.

- [Github](https://github.com/Mino777)

---

#### 학력

**경기대학교 스포츠산업경영학과** : 2014.03 ~ 2021.02 (졸업)

---

#### 경력

**(프리랜서) 소프트스퀘어드 IOS 개발자** : 2020.9 ~ 2020.12
- iOS 개발
- Conti App 1.0.0(1) ~ 1.0.8 개발 및 유지보수

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
    - iOS 프로그래밍 교육 수료
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

[AppStore](https://itunes.apple.com/app/id1537755211#?platform=iphone)

#### 개발 인원
- PM 1명, DL(개발 리드) 1명, DM(개발 실무자) 2명 (IOS, PHP), DL(디자이너 리드) 1명, DM(디자인 실무자) 1명

#### 기능
1. 카카오, 페이스북, 구글, 애플 SNS 로그인 가능 및 회원가입을 하지 않고 제한된 활동을 할 수 있는 게스트 로그인 가능.
2. Feed를 통해 친구들의 게시글 확인, 수정, 삭제, 좋아요, 댓글작성, 팔로우 확인, 유저 신고&차단 가능
3. Search를 통해 전체 유저를 대상으로 해시태그, 검색된 게시물의 이미지 확인, 아이디 검색 가능
4. Creation을 통해 일자형, 십자형 게시글 (사진 + 글) 등록 가능
5. 팔로우, 좋아요, 멘션시 해당 유저에게 Push Notification 발송.
6. Notification을 통해 팔로우, 좋아요, 멘션 알림 확인 가능
7. Profile을 통해 팔로우, 팔로워 목록, 자신의 게시글 확인, 상대 유저 팔로우, 유저 신고&차단, 연락처를 통한 게시글 공유 가능.

#### 사용한 아키텍쳐

- `MVC`, `Delegation`, `Singleton`

#### 사용한 기술 및 라이브러리

- 형상관리: GitLab
- 커뮤니케이션: Slack, Google Sheet, Google Driver
- UI 구성: Storyboard(Main) + Xib + Code, 다크 모드 금지 처리
- `Swift5`, `Xcode10`, `UIKit`, `Auto Layout`, `UserNotifications`, `Error Handling`, `Localizing`, `Networking`, `Contacts`
- 'Alamofire', '~> 4.9.1'
- 'AlamofireNetworkActivityIndicator', '~> 2.4.0'
- 'AlamofireObjectMapper', '~> 5.2.1'
- 'SnapKit' , '~> 5.0.1'
- 'Firebase/Analytics' , '~> 7.0.0'
- 'Firebase/Crashlytics', '~> 7.0.0'
- 'Firebase/Core', '~> 7.0.0'
- 'Firebase/Auth', '~> 7.0.0'
- 'GoogleSignIn', '~> 5.0.2'
- 'Firebase/Storage', '~> 7.0.0'
- 'Kingfisher', '~> 5.15.7'
- 'FBSDKLoginKit', '~> 8.1.0'
- 'RxKakaoSDK', '~> 2.0.0-beta.3'
- 'RxSwift', '~> 5.1.1'
- 'RxCocoa', '~> 5.1.1' (Alamofire와 KakaoSDK 충돌로 인해 RxKakaoSDK 사용)
- 'Firebase/DynamicLinks', '~> 7.0.0'
- 'Firebase/Messaging', '~> 7.0.0'
- 'Mantis', '~> 1.4.4' (Image Crop 기능에서 생산성을 높이기 위해 사용)
- 'Atributika', '~> 4.9.10' (해시태그 기능에서 NSAttributedString 터치 감지를 위해 사용)


#### 트러블슈팅

- 
