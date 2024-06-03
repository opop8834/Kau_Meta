# Kau_Meta

**파일 및 영상** : https://drive.google.com/drive/folders/1qKwLHjyeLk1T8CQ4dpJumYUZzWN_nzwq?usp=sharing



유니티 이용한 메타버스 프로젝트 개발

팀원 :  4명
프로젝트 목표

학교 생활을 가상으로 체험할 수 있는 항공대 메타버스 구축
강의를 실시간 온라인으로 들을 수 있게 구축
 

실적

1. 최대 200명 접속 가능한 Unity Unet서버 생성

2. PDF Viewer를 활용한 비대면 수업 환경 조성

3. 수업중 웹 브라우저와 메모장 기능 활용


> ### 서비스 Framework
<img src="https://velog.velcdn.com/images/opop8834/post/8046d03a-10a7-4df9-9829-ee6568275ae9/image.png">

- Unity Unet 기반 메타버스 서버 구축<br/>
- AWS Cognito를 통한 계정 관리, <br/>
- AWS RDS를 통한 계정 정보 저장, <br/>
- Unity Vivox 서버를 이용한 채팅 서버 구현

기능
> #### 1. 회원가입 및 로그인
<img src="https://velog.velcdn.com/images/opop8834/post/f5b13542-f677-488b-9503-d2ea57291bd0/image.png">

> #### 2. 자유로운 활동 및 의사소통
<img src="https://velog.velcdn.com/images/opop8834/post/4e5e45f7-6bf6-481a-9cbd-3185a0c30466/image.png">

> #### 3. 비대면 강의 참여
<img src="https://velog.velcdn.com/images/opop8834/post/ffd226ed-9995-443f-9d61-ccd1aab35a24/image.png">


> ### 역할
#### 서버 구축 및 메타버스 내 기능 구현 담당
#### + 주요 개발 내역
**1. Unity Unet 서버구현**
 -> 최대 접속 인원 200명 서버를 구현
 
**2. AWS  Cognito 계정 인증 및 권한 관리**
 ->  이메일 인증을 통한 접속 권한 획득 방식
 
**3. AWS RDS 활용 계정 정보 및 닉네임 저장**
 ->  닉네임 DB에 저장 및 중복 닉네임 방지
 
**4. Sample 캐릭터 애니메이션 서버에 구현**
 ->    Sample 캐릭터를 활용하여 서버 동기화 test
 
**5. 로그인 화면 UI 구현**

**6. 유저 닉네임 설정 및 표시  기능**
 ->   user 머리 위로 닉네임이 뜨게 적용
 
**7. PDF 뷰 및 동기화 기능**
 ->   URL 연동 방식으로 구현 및 동기화 / PDF 파일이 서버 안에서 보일 수 있게 적용
 
**8. 마우스 커서 활성화 / 비활성화 기능**
 ->   마우스 커서는 특정 상황일 때만 활성화 (ex. Esc 입력 시)
설정 기능 구현

 ->  Esc 입력 시 설정창 진입
 
**9. 메모장 기능**
 ->  T 입력 시 메모장 사용 가능 
 
**10. 웹 브라우저 기능**
 ->  H 입력 시 웹 브라우저 사용 가능
 
**11. 디자인된  맵, 캐릭터 서버 연동**
 ->  디자인된 맵, 캐릭터 서버에 적용
 
**12. 버그 수정 및 테스트**
 ->  기능 추가하면서 생기는 버그들 수정
 
