## 👋🏻 Hi there, I'm Jihun

### Tech Stack
  
<p>
  <img src="https://img.shields.io/badge/Java-007396.svg?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring-6DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939.svg?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/nginx-009639.svg?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D.svg?style=for-the-badge&logo=redis&logoColor=white" />

## Projects
 <img width="40" height="40" alt="GamzaTechBlog" 
       src="https://github.com/user-attachments/assets/43f1e03e-f673-4635-9e19-f79d4225b541" 
       style="float: left; margin-right: 10px;"/><img width="50" height="50" alt="Hanmo" 
       src="https://github.com/user-attachments/assets/82cd1f4d-96b2-49f4-b7d7-a0f2d4568cda" 
       style="float: left; margin-right: 10px;"/>
        <img width="55" height="50" alt="Luview" 
       src="https://github.com/user-attachments/assets/676eba2a-2889-4edf-888a-2e65106be199" 
       style="float: left; margin-right: 10px;"/>
- **GamzaTechBlog** (2025.06 ~ 현재, Team: 3 B1·F1·D1)  [[Repository]](https://github.com/potato-club/GamzaTechBlog-back)<br>
  동아리 활동을 위한 기술 블로그 플랫폼  
  GitHub API와 연동되어 **기술블로그에 글 작성 시 자동으로 GitHub Repo에 저장·배포**되는 방식으로 운영  

- **Hanmo (한모)** (2025.03 ~ 2025.07, Team: 6 B3·F2·D1) [[Repository]](https://github.com/DevOpsSociety/Hanmo)<br>
  교내 학생들을 위한 실시간 친구·과팅 매칭 서비스  
  **200명 이상 사용**, **70팀 이상 매칭 성사**로 교내 교류 활성화에 기여  

- **Luview (러뷰)** (2024.09 ~ 2025.02, Team: 4 B2·F2)  [[Repository]](https://github.com/potato-club/Luview-back)<br>
  커플 전용 기록 및 리뷰 웹 서비스  
  **장소 기록·사진 업로드·리뷰 작성**을 통해 커플이 함께한 추억을 관리할 수 있는 서비스  


## Open Source Contributions

<img width="100" height="50" alt="image" src="https://github.com/user-attachments/assets/b8154a86-2654-4c80-9a5c-4a83f5355edd" />

- [Apache Seata] test: `ConsulConfigurationTest#testInitSeataConfig` **테스트 안정화(Deflake)** [[#7584]](https://github.com/apache/incubator-seata/pull/7584)  
  Consul KV 타이밍 플레이크 흡수를 위해 **최대 ~3초 대기/재시도(100ms backoff)** 추가 → 테스트 안정화 — **Merged**, fixes [#7583](https://github.com/apache/incubator-seata/issues/7583).<br>
  [상세 글 보러가기](https://velog.io/@jihun4452/apache-incubator-seata%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%EC%B2%AB-%EA%B8%B0%EC%97%AC)

- [Apache SeaTunnel] Docs: SQL 함수 **반환 타입** 명시 및 예시 정리 [[#9711]](https://github.com/apache/seatunnel/pull/9711)  
  각 함수에 “This method returns …” 한 줄과 **대문자 타입 표기** 추가, EN/zh 문서 일관성/포맷 정리 — **Merged**, closes [#9703](https://github.com/apache/seatunnel/issues/9703).<br>
  [상세 글 보러가기](https://velog.io/@jihun4452/apache-seatunnel-%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%EB%91%90%EB%B2%88%EC%A7%B8-%EA%B8%B0%EC%97%AC)

- [Apache Seata] chore: **upgrade @babel/runtime to ^7.27.0** [[#7673]](https://github.com/apache/incubator-seata/pull/7673)  
  `@babel/runtime`을 ^7.27.0으로 업그레이드해 package-lock.json과 정합성 유지 — **Merged**, fixes [#7660](https://github.com/apache/incubator-seata/issues/7660).  

- [Apache Seata] optimize: **upgrade axios to 1.12.2** [[#7699]](https://github.com/apache/incubator-seata/pull/7699)  
  `axios`를 콘솔 프론트엔드에서 ^1.12.2로 업그레이드해 package.json·package-lock.json을 동기화 — **Merged**, fixes [#7659](https://github.com/apache/incubator-seata/issues/7659).

<img width="60" height="60" alt="image" src="https://github.com/user-attachments/assets/5c7518a0-6c64-4dc5-b692-34b934ad0f36" />

- [JUnit] fix: **Validate argument count for @ParameterizedClass field injection** [[#5088]](https://github.com/junit-team/junit-framework/pull/5088)  
  `@ParameterizedClass` 필드 인젝션 시 인자 부족으로 발생하던 **ArrayIndexOutOfBoundsException**을  
  명확한 **ParameterResolutionException**으로 변경해 오류 메시지 개선 및 테스트 안정화 — **Merged**, closes [#5079](https://github.com/junit-team/junit-framework/issues/5079).<br>
  [상세 글 보러가기](https://velog.io/@jihun4452/JUnit%EC%97%90-%EA%B8%B0%EC%97%AC%EB%A5%BC-%ED%96%88%EC%8A%B5%EB%8B%88%EB%8B%A4)

## Stats & Algorithm

<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=jihun4452&show_icons=true&bg_color=ffffff&text_color=000000&icon_color=f1c40f&title_color=e74c3c&border_color=e74c3c"
    alt="GitHub Stats" />
  <a href="https://solved.ac/jihun6548/">
    <img
      src="https://mazassumnida.wtf/api/v2/generate_badge?boj=jihun6548"
      alt="Solved.ac Profile" />
  </a>
</div>

