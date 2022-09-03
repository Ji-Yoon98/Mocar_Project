# ✨ mocar_project

> <h4>차량 렌트 서비스</h4>
> Mocar

# ✨ 제작기간 &amp; 참여인원
> [ 2022/05/17 ~ 2022/06/30 ]<br>
> 팀 프로젝트(총 6명, 팀장)

# ✨ 사용기술
```Back-end```
- JSP MVC2<br>
- JAVA 8<br>
- ApacheTomcat 8.5v<br>
- Oracle DB<br>
- JSON<br>
- MyBatis<br>
- JSTL.jar<br>

```Front-end```
- HTML5 & CSS3<br>
- JavaScript & JQuery<br>

# ✨ 설계

### 흐름도
![흐름도](https://user-images.githubusercontent.com/97427387/185802512-953f3327-00c3-4daf-a237-a3d89c875825.png)

### ERD
![ERD](https://user-images.githubusercontent.com/97427387/185803251-acf26ccd-c7cf-4093-9829-c69ca51fab28.png)


# ✨ 화면구성 &amp; 기능
### 1. 회원가입
![회원가입](https://user-images.githubusercontent.com/97427387/185804369-b34f2014-7c80-4bc7-9e38-ceb6909e69a9.gif)
- 회원가입을 모달창으로 만들어 따로 페이지 이동을 하지 않게 제작
- ajax를 이용하여 중복확인 버튼 클릭시 사용가능or사용불가 메세지 출력
- validation check(유효성 검사)를 통해 사용불가, 입력 누락 시 회원가입 X

### 2. 로그인
![로그인](https://user-images.githubusercontent.com/97427387/188269543-e80170ca-4043-4c3c-b6c0-1cce95310fba.gif)
- 로그인 버튼 클릭시 모달창
- DB에 저장된 아이디와 비밀번호가 맞다면 로그인 성공
- 틀리다면 로그인 실패 alert창이 뜸

### 3. ID찾기
![ID찾기](https://user-images.githubusercontent.com/97427387/188269760-2a96891a-995f-4382-b77b-5e2b1284eae7.gif)
- DB에 저장된 이름과 이메일이 일치한 회원의 아이디를 alert창으로 알려줌 
- 이름과 이메일이 맞지 않거나 없다면 아이디 찾기 실패 alert창이 뜸

### 4. 회원정보수정
![회원정보수정](https://user-images.githubusercontent.com/97427387/188269864-d56f3e8e-e176-4609-b638-ae997de38385.gif)

### 5. 회원탈퇴
![회원탈퇴](https://user-images.githubusercontent.com/97427387/188269872-d2d9a7dd-579a-4681-b3c6-95b5b1e4e886.gif)

### 6. 예약하기
![예약하기](https://user-images.githubusercontent.com/97427387/188269881-080a6984-4846-4beb-b8bf-417a3b9a1f01.gif)

### 7. 게시판
![게시판](https://user-images.githubusercontent.com/97427387/188269909-cd7324ce-bba7-4cab-ba12-60ce1ea11259.gif)


### 4. 문의하기
![문의하기](https://user-images.githubusercontent.com/97427387/188269911-2d3a0994-1db8-4621-ab4c-f2b192630364.gif)


