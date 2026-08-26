# 시큐리티 아카데미 8기 · TEAM Rak's

<!-- 로고 준비되면 아래 주석을 해제하세요
<div align="center">
  <img src="assets/logo.png" width="220">
  <br>
</div>
-->

---

## 프로젝트 개요

본 프로젝트는 **금융권 모바일 보안 위협**이 **실제 금전 피해**로 이어지는 과정을 분석하여,
**단말 보안 모듈의 탐지 데이터를 FDS 룰에 연동**하는 대응 체계를 설계하는 것을 목표로 합니다.

단순한 위협 나열이 아닌, 실제 피해 사례와 악성 앱 분석 결과를 바탕으로 공격 시나리오를 재구성합니다. 이후 각 공격 단계에서 확인할 수 있는 탐지 데이터를 실제 보안 모듈의 필드와 연결하고, 이를 활용한 FDS 룰을 설계하여 금융 서비스 환경에 적용 가능한 대응 방안을 제시합니다.

---

## 주요 섹션

<div class="grid cards" markdown>

-   :material-bug-outline: **1단계 · 위협 유형 분석**

    ---

    로더, 정보 탈취, 전화 가로채기, 원격제어 등
    금융 악성 앱의 악성 행위를 유형별로 분류하고 국내 사례와 함께 분석했습니다.

    [:octicons-arrow-right-24: 바로가기](./01-threat/overview.md)

-   :material-sitemap: **2단계 · 공격 시나리오**

    ---

    분석한 위협 유형을 조합해
    실제 발생 가능한 공격을 단계별로 재구성했습니다.

    [:octicons-arrow-right-24: 바로가기](./02-scenario/overview.md)

-   :material-database-search: **3단계 · 탐지 데이터**

    ---

    보안 모듈의 탐지 정보를 유형별로 정리하고,
    공격 시나리오별 탐지 가능 데이터와 활용 방안을 분석했습니다.

    [:octicons-arrow-right-24: 바로가기](./03-detection/overview.md)

-   :material-lan-connect: **4단계 · 보안 아키텍처**

    ---

    단말 · 보안 모듈 · 금융사 서버 · FDS로 이어지는
    연동 구조와 역할 분담을 설계했습니다.

    [:octicons-arrow-right-24: 바로가기](./04-architecture/module-integration.md)

-   :material-shield-check: **5단계 · FDS 룰 설계**

    ---

    복수 탐지 데이터를 조합한 시나리오별 탐지 룰을 설계하고,
    실제 사고 사례에 대입해 검증했습니다.

    [:octicons-arrow-right-24: 바로가기](./05-fds-rule/principles.md)

</div>

---

## 팀원 소개

<div class="grid cards" markdown>

-   **이호영**

    ---

    위협 유형 분석, 공격 시나리오 설계, 탐지 데이터 분석, FDS 룰 설계

    [:fontawesome-brands-github:](https://github.com/lhywk)
    &nbsp;
    [:fontawesome-brands-linkedin:](https://www.linkedin.com/in/hoyoung-lee-76364935a/)
    &nbsp;
    [:material-post:](https://lhywk.tistory.com/)

-   **임정락**

    ---

    위협 유형 분석, 공격 시나리오 설계, 탐지 데이터 분석, FDS 룰 설계

    [:fontawesome-brands-github:](#)
    &nbsp;
    [:fontawesome-brands-linkedin:](#)
    &nbsp;
    [:material-post:](#)

-   **김주연**

    ---

    위협 유형 분석, 공격 시나리오 설계, 탐지 데이터 분석, FDS 룰 설계

    [:fontawesome-brands-github:](#)
    &nbsp;
    [:fontawesome-brands-linkedin:](#)
    &nbsp;
    [:material-post:](#)

-   **김현섭**

    ---

    위협 유형 분석, 공격 시나리오 설계, 탐지 데이터 분석, FDS 룰 설계

    [:fontawesome-brands-github:](#)
    &nbsp;
    [:fontawesome-brands-linkedin:](#)
    &nbsp;
    [:material-post:](#)

</div>

**Mentor** 김지웅

---

!!! info "공지사항"
    모든 분석 내용은 프로젝트 진행에 따라 지속적으로 업데이트될 예정입니다.
