# React 토이 프로젝트
주소: https://yoyo-9109a.web.app/home  

id:test@test.com    
pw:123456

# 로그인 해야 입장가능
![제목 없음](https://github.com/rnr9928/REACT/assets/97073355/cf43b080-fcc4-4305-baff-98b14b21c6f5)


### 회원가입

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/8e2a9a28-944a-43d8-a940-e35acc7d6254/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

파이어베이스 인증기능인  getAuth를 임포트 해준다

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/ebacedcb-974d-4ed9-a488-7c32966d8823/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

파이어베이스 콘솔에서 인증 기본설정을 할 수있다

이메일/비밀번호 형식으로 설정

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/c79bc951-6a3f-43d1-b63c-25af6e0dae54/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

이메일과 비밀번호를 이용하여 회원가입을 진행할수있고

file storage를 추가해서 프로필 설정도 가능하게 만들었다

회원가입 성공 실패 여부도 파이어베이스가 수행해준다

toast 라이브러리로 성공 실패 알림 

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/61651106-31b1-44b0-9bba-ca378b58c24f/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

회원가입을 완료하면

파이어베이스에서 유저정보를 확인할 수 있다 

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/0be2f32a-be43-4f0f-824f-711cd7c842c2/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

파이어베이스 auth는 현재 로그인한 사람을 확인하는 currentUser함수를 가지고 있다

로그인하지 않은 상태면 null을 반환한다

currentUser 값에 따라 로그인 상태를 조작 가능

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/aed62cbf-f102-4fce-b6a4-cbb4c2303b7b/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

이런식으로 로그인이 되어있지 않다면 로그인 페이지로 이동하게 만들 수 있다

# 기능들

[]()

# 유저 정보 확인

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/5be49c8c-c0dc-4613-9e2c-74d9ec2b349d/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

## 파이어 베이스 DB관리

![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/98a4fe96-7bec-4c26-8e3a-a362399fe7a9/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)

## 파일 스토리지
![제목 없음.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/95e5b05c-c8f2-4cfe-bbab-99aac56e3458/d032cd8a-31de-492b-a5ed-b3a1c763612a/%EC%A0%9C%EB%AA%A9_%EC%97%86%EC%9D%8C.png)
