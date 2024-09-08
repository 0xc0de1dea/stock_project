# 💰 주식 배당금 서비스 프로젝트

## ⚙ 주요기능
<ol>
  <li>회사 이름을 인풋으로 받아 해당 회사의 메타 정보와 배당금 정보를 반환</li>
  <li>자동완성 기능을 위한 API</li>
  <li>서비스에서 관리하고 있는 모든 회사 목록을 반환</li>
  <li>추가하고자 하는 회사의 ticker 를 입력으로 받아 해당 회사의 정보를 스크래핑하고 저장</li>
  <li>ticker 에 해당하는 회사 정보 삭제</li>
  <li>회원가입 API (중복 ID 허용 X, 패스워드 암호화)</li>
  <li>로그인 API (회원가입이 되어있고, 아이디/패스워드 정보가 옳은 경우 JWT 발급)</li>

## 🛠 사용기술
<ul>
  <li>Language : <strong>Java</strong></li>
  <li>Build : <strong>Gradle</strong></li>
  <li>Database : <strong>h2</strong></li>
  <li>JDK : <strong>OpenJDK 17</strong></li>
  <li>Library : <strong>web, data-jpa, data-redis, security, h2, jsoup, jjwt, common-collections4, lombok</strong></li>
  <li>Tool : <strong>IntelliJ IDEA Ultimate</strong></li>
</ul>
