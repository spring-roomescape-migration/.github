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


<br>
<br>

## **2. 교육 과정 및 AWS 클라우드 전환 과정 소개**
2024년 6월 3일부터 8월 11일까지 [학습 테스트로 배우는 Spring 3기-NEXTSTEP](https://edu.nextstep.camp/s/OiPrZU5t) 
 교육 과정에 참여하여 Spring MVC 및 Spring Core에 관한 이해를 높이고 챌린지 형태의 개인 프로젝트를 진행했습니다. 이 과정에서 사전에 준비된 요구사항과 문제를 해결하도록 코드를 작성하여 19개 API 구현, 87개 테스트 코드 및 136개 리뷰를 남겼고, 리뷰어의 검증과 추가적인 피드백을 통해 지속해서 코드를 개선했습니다. 또한, 개발 과정에서 생긴 어려움이나 궁금한 부분이 생길 때마다 리뷰어에게 적극 질문하거나 오프라인 모짝미(모여서 짝으로 미션) 및 네트워킹을 활용하여 해결했습니다.

교육을 수료한 후, 애플리케이션의 배포 환경을 로컬 환경에서 AWS 클라우드 환경으로 전환했습니다. 클라우드 전환의 가장 큰 이유는 실제 현업에서 사용하는 개발 환경과 개발 프로세스를 경험해보고 싶었기 때문입니다. 또한, [인프라 관련 교육](https://edu.nextstep.camp/s/WVWWBg6X)을 수료하고 AWS 자격증을 취득할 만큼 인프라에 관심이 있었지만, 시간적 제약 때문에 팀 프로젝트나 해커톤에서 이를 도입하지 못했었습니다. 이에 이번 프로젝트를 마이그레이션하면서 AWS의 여러 서비스를 활용하여 인프라를 직접 설계하고 구현하여 안정적이고 확장성 있는 애플리케이션을 개발하고 운영할 수 있는 능력을 갖추고자 했습니다.

<br>

![리뷰](https://github.com/user-attachments/assets/8795c0e2-0226-48e7-babd-5a80874df664)


<br>
<br>


## **3. AWS 아키텍처 & CI/CD**
본 서비스는 AWS의 서비스 및 자원을 활용하여 구축 및 운영하고 있습니다. AWS CodePipeline을 사용하여 CI/CD 파이프라인을 구성하고, VPC 엔드포인트를 통해 프라이빗 서브넷의 EC2에 애플리케이션을 배포하고, 데이터베이스를 별도의 프라이빗 서브넷에 배치했습니다. 사용자와의 통신은 Route 53과 ALB 로드밸런서를 통해 관리합니다. 또한 보안을 위해 HTTPS를 구축했고 앞으로 사용자 트래픽을 고려한 Auto-Scaling 적용할 계획입니다.

<br>

![Untitled](https://github.com/user-attachments/assets/6edd2b1f-cbfd-40c8-8026-6997cdccb655)
  

<br>
<br>

## **4. Test Coverage**
  <img alt="image" src="https://github.com/user-attachments/assets/85090c15-2c63-439f-b0f2-53f81783ccbe" max-width= 100 />




## **5.학습 저장소**
프로젝트 진행 간에 학습했던 것이나 고민이 들거나 문제를 해결한 경험을 [Wiki](https://github.com/spring-roomescape-migration/spring-roomescape-migration/wiki)를 통해 남기고 있습니다.
