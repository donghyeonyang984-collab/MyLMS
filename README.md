# 🎓 MyLMS
> Spring Boot & JDBC 기반의 온라인 학습 관리 플랫폼 (LMS)

---

## 📘 프로젝트 소개
MyLMS는 강의 수강, 구매, 장바구니, 쪽지 기능 등  
기본적인 LMS 기능을 모두 포함한 온라인 학습 플랫폼입니다.  
로그인 역할에 따라 **헤더/사이드바 UI가 동적으로 변경**되는 구조를 직접 설계했습니다.

---

## 🧑‍💻 주요 기능
- 홈페이지 전체 프론트엔드 개발 (HTML/CSS/JS)
- 백엔드 페이지 매핑 및 연동 (Spring Boot / JDBC)
- 강의 재생 및 진도율 저장 기능
- 강의 구매 · 장바구니 기능 전체 구현
- 장바구니 페이지 내 구매 기능 및 구매 여부 확인
- 쪽지 보내기 기능 구현
- 로그인 역할에 따라 헤더 및 사이드바 자동 변경

---

## ⚙️ 기술 스택
- **Backend:** Spring Boot, JDBC  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL  
- **Collaboration:** GitHub  
- **Build Tool:** Maven  

---

## 🔥 핵심 구현 포인트
- **역할 기반 UI 자동 렌더링 구조 개발:** 로그인 시 사용자 유형(Admin/User)에 따라 메뉴 동적 표시  
- **장바구니 → 결제 흐름 구현:** 상품 구매, 결제 완료, 구매 여부 검증까지 전 과정 처리  
- **강의 진도율 관리:** 재생 위치 저장 및 수강 완료 자동 감지 로직 구현  
- **Front + Back 자연스러운 연동:** Thymeleaf 기반으로 페이지 구조 설계 및 컨트롤러 연동  

---

## 🧩 프로젝트 구조 (간단 예시)
```text
MyLMS/
 ┣ src/
 ┃ ┣ main/
 ┃ ┃ ┣ java/com/example/mylms/
 ┃ ┃ ┣ resources/
 ┃ ┃ ┃ ┣ static/
 ┃ ┃ ┃ ┗ templates/
 ┃ ┗ test/
 ┣ pom.xml
 ┗ README.md
```

## 🗓 개발 기간
**2025.09.04 ~ 2025.10.14 (6주)**

---

## 📦 실행 방법
```bash
git clone https://github.com/donghyeonyang984-collab/MyLMS.git
cd MyLMS
mvn clean package
java -jar target/mylms-0.0.1-SNAPSHOT.jar
```
---

## 🔗 관련 링크
- **포트폴리오 문서:** [Notion 바로가기]([https://www.notion.so/2be91ca4e4f0806283aff8df0a5021ec](https://tasty-ear-c9b.notion.site/2be91ca4e4f0806283aff8df0a5021ec)
- **PDF 포트폴리오:** (추후 추가 예정)

---


📜 License

이 프로젝트는 개인 학습 및 포트폴리오 용도로 작성되었습니다.


