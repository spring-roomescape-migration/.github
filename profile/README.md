<br>

<p align="center">
 <img src="https://github.com/user-attachments/assets/42a87114-ccf9-4ec6-bc20-b784a862c62f" alt="Resized Logo" width="256">
</p>

<p align="center">
 <a href="https://www.roomescape.me" rel="nofollow"><img src="https://camo.githubusercontent.com/b34bcbadf151fc946861cf752e6a40abf6deec97dbd383a60f09dacea273cf0e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d2546302539462539332538365f5765625f536572766963652d626c7565" alt="Release" data-canonical-src="https://img.shields.io/badge/-%F0%9F%93%86_Web_Service-blue" style="max-width: 100%;"></a> 
 <br>
 <a href="https://github.com/spring-roomescape-migration/spring-roomescape-migration/releases/tag/v0.8.0">
  <img src="https://img.shields.io/badge/%E2%9C%A8%20release-v0.8.0-brightgreen" alt="Release">
 </a>
</p>

<br>
<br>

## **1. 서비스 소개**
본 서비스는 방 탈출 카페를 예약할 수 있는 웹 애플리케이션입니다. 사용자는 회원가입과 로그인 후에 방 탈출 테마와 예약 시간을 선택하여 예약을 진행할 수 있고, 관리자는 특정 사용자를 직접 선택하여 예약시킬 수 있습니다. 예약이 마감된 경우에는 예약 대기를 요청할 수 있습니다.


#### 로그인 및 쿠키를 통한 사용자 식별
![로그인](https://github.com/user-attachments/assets/2e5eef96-1a3a-4c0f-b60e-0c3a4ff941fe)

#### 사용자 예약 및 자신의 예약 확인
![화면 기록 2025-01-11 오후 9 42 33](https://github.com/user-attachments/assets/93d38a3c-e765-4996-bbc5-d4d9fd4f1b41)

#### 사용자 예약 대기 요청
![화면 기록 2025-01-13 오후 2 37 14](https://github.com/user-attachments/assets/d316c84a-7993-4045-9670-2701c8d030cc)

<br>
<br>

## **2. 교육 과정 및 AWS 클라우드 전환 과정 소개**
2024년 6월 3일부터 8월 11일까지 [학습 테스트로 배우는 Spring 3기-NEXTSTEP](https://edu.nextstep.camp/s/OiPrZU5t) 
 교육 과정에 참여하여 Spring MVC 및 Spring Core에 관한 이해를 높이고 챌린지 형태의 개인 프로젝트를 진행했습니다. 이 과정에서 사전에 준비된 요구사항과 문제를 해결하도록 코드를 작성하여 `19개 API 구현`, `87개 테스트 코드` 및 `136개 리뷰`를 남겼고, 리뷰어의 검증과 추가적인 피드백을 통해 지속해서 코드를 개선했습니다. 또한, 개발 과정에서 생긴 어려움이나 궁금한 부분이 생길 때마다 리뷰어에게 적극 질문하거나 오프라인 모짝미(모여서 짝으로 미션) 및 네트워킹을 활용하여 해결했습니다.

교육을 수료한 후, 애플리케이션의 배포 환경을 로컬 환경에서 `AWS 클라우드 환경`으로 전환했습니다. 클라우드 전환의 가장 큰 이유는 실제 현업에서 사용하는 개발 환경과 개발 프로세스를 경험해보고 싶었기 때문입니다. 또한, [인프라 관련 교육](https://edu.nextstep.camp/s/WVWWBg6X)을 수료하고 AWS 자격증을 취득할 만큼 인프라에 관심이 있었지만, 시간적 제약 때문에 팀 프로젝트나 해커톤에서 이를 도입하지 못했었습니다. 이에 이번 프로젝트를 마이그레이션하면서 AWS의 여러 서비스를 활용하여 인프라를 직접 설계하고 구현하여 안정적이고 확장성 있는 애플리케이션을 개발하고 운영할 수 있는 능력을 갖추고자 했습니다.

<br>


![무제1](https://github.com/user-attachments/assets/545b3bb7-5879-4d7a-8c75-e6b4a0704990)
![무제2](https://github.com/user-attachments/assets/1fd8f2d3-031b-43b7-84b2-b9d413fdc09c)
![무제3](https://github.com/user-attachments/assets/628021b6-d166-4146-a74c-01e11a93bb1c)



<br>
<br>

## **3.학습 저장소**
프로젝트 진행 간에 학습했던 것이나 고민이 들거나 문제를 해결한 경험을 [Wiki](https://github.com/spring-roomescape-migration/spring-roomescape-migration/wiki)를 통해 남기고 있습니다.

* 기술1
* 기술2

<br>
<br>

## **4. 백엔드 기술 및 AWS 인프라**
본 서비스는 Java/SpringBoot를 사용하여 구축했습니다. 서비스 구축을 위해 AWS를 활용했으며 EC2, ALB, RDS, CodepipeLine 등 다양한 AWS 서비스 및 자원을 사용하고 있습니다. Junit5, RestAssured 등의 기술을 사용하여 통합 테스트 환경을 구축하고 Jacoco를 통해 테스트 커버리지를 확인하여 서비스의 안정적인 운영과 배포를 만들어가고 있습니다. 백엔드 위주 및 개인 프로젝트이다 보니 페이지 렌더링에 필요한 HTML, CSS, js 뼈대 코드 및 페이지 디자인은 교육기관인 NEXT-STEP으로 제공받았습니다.


<br>

![image](https://github.com/user-attachments/assets/7345985e-4d0b-4277-98e1-ee8471beca19)



> 백엔드 및 인프라에 관한 상세한 설명은 [해당 링크](https://github.com/spring-roomescape-migration/spring-roomescape-migration)를 참조해주세요.

<br>
<br>
