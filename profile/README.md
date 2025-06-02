# 💡 AIVLE LMS
도서관리시스템 웹 애플리케이션입니다. 📚

[2025] KT AIVLE SCHOOL 4차 MINI PROJECT  

<br>

## 💻 팀원

| 이름    | 이의형    | 박가희   | 장성희 | 현승아 | 최민지 | 강서연 | 박상훈
| ------- | ----------| ----------|---------- | ----------| ----------| ----------| ----------
| **git** | 	[leh60245](https://github.com/leh60245) | [LienBak](https://github.com/LienBak) | [ddanglehee](https://github.com/ddanglehee)   | [seungah-hyun](https://github.com/seungah-hyun) |[choiminji-020102](https://github.com/choiminji-020102) |[seoyeon](https://github.com/haaaaauy) |[sanghuniolsida](https://github.com/sanghuniolsida)
| Role | backend| backend | backend| frontend | frontend | frontend | frontend

<br>

## 📦 주요 레포지토리

- [frontend](https://github.com/aivleLMS/frontend) - 프론트엔드 소스
- [backend](https://github.com/aivleLMS/backend) - 백엔드 소스
- [notion](https://www.notion.so/4-20297e47e8a280e3b5b0f862d33443fd) - 문서


## 🛠 기술 스택

### 🖥 Frontend  
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white)](https://reactjs.org/)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🔧 Backend  
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![OpenAI](https://img.shields.io/badge/GPT%20API-412991?style=for-the-badge&logo=openai&logoColor=white)](https://platform.openai.com/)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white)


<br>

## 프로젝트 구조 (Backend)
```
src/
└── main/
├── java/
│ └── com.aivle.booksystem/
│ ├── config/
│ │ └── WebConfig.java
│ ├── controller/
│ │ ├── BookController.java
│ │ └── UserController.java
│ ├── domain/
│ │ ├── Book.java
│ │ └── User.java
│ ├── dto/ 
│ │ ├── BookDTO.java
│ │ └── UserDTO.java
│ ├── repository/ 
│ │ ├── BookRepository.java
│ │ └── UserRepository.java
│ ├── service/ 
│ │ ├── book/
│ │ └── user/
│ └── BooksystemApplication.java 
└── resources/
└── application.yml
```
## 프로젝트 구조 (Frontend)
```
src/
├── api/ 
│ ├── axiosInstance.js 
│ ├── bookService.js 
│ └── openaiService.js 
│
├── components/
│ ├── AppBar.jsx
│ └── BookCard.jsx 
│
├── pages/ # 각 페이지별 구성
│ ├── BookDetail.jsx 
│ ├── BookList.jsx 
│ ├── EditBook.jsx 
│ ├── RegisterBook.jsx
│ ├── Login.jsx
│ └── UserInfo.jsx
```
