1. 프로젝트 설명
- HTML과 CSS를 활용해 간단한 로그인, 회원가입 페이지 구현 

2. 2025.09.03 구현한 것

구조
- header/main/footer 시맨틱 영역 사용
- 각 페이지에 'title'태그와 'h1' 태그 존재

폼/접근성
- 모든 input에 연결된 'label'태그 존재(클릭 시 포커스)
- required로 브라우저 기본 검증 동작
- 이메일은 type="email"

스타일
- 카드가 화면 중앙에 정렬
- input 100% 가로 + 내부 padding
- 버튼 hover/focus 스타일 구분 가능
- :focus 시 명확한 포커스 링/테두리

반응형
- 480px 이하에서 카드/타이포가 자연스럽게 보임

내비게이션
- 서로 왕복 가능한 링크 존재(로그인↔회원가입)

3. 오늘 배운 점/아쉬운 점
  1) 시맨틱 태그 : 문서의 구조와 의미를 명확하게 나타내는 역할을 함. 유지보수와 접근성이 향상
  참고 사이트 : https://www.designkits.co.kr/blog/web-css/etc/Semantic-Tag?srsltid=AfmBOoqc-ZQWHeMSUCra8hhWTlLYqVSiEn1PquTvm4zvxb6CxXXb5LoO
  2) header, main, footer 태그는 body 안에 들어감
  3) required 속성 이해

  4. 로그인 페이지에서 아이디, 패스워드 자동저장이 되지 않았는데, login_check.html 파일을 임시로 만들어서 넘어간 것처럼 하니까 저장됐음