# 방탈출 예약 관리 애플리케이션

<br>

<p align="center">    <img src="https://github.com/user-attachments/assets/42a87114-ccf9-4ec6-bc20-b784a862c62f" alt="Resized Logo" width="256">
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

<br>
<br>

## **2. 교육 과정 소개 및 프로젝트 진행 방향**
2024년 6월 3일부터 8월 11일까지 [학습 테스트로 배우는 Spring 3기-NEXTSTEP](https://edu.nextstep.camp/s/OiPrZU5t) 
 교육 과정에 참여하여 Spring MVC 및 Spring Core에 관한 이해를 높이고 개인 프로젝트를 진행했습니다. 이 과정에서 사전에 준비된 요구사항과 문제를 해결하도록 코드를 작성하여 19개 API 구현, 87개 테스트 코드 및 136개 리뷰를 남겼고, 리뷰어의 검증과 추가적인 피드백을 통해 지속적으로 코드를 개선했습니다. 또한, 개발 과정에서 생긴 어려움이나 궁금한 부분이 생길 때마다 리뷰어에게 적극적으로 질문하거나 오프라인 모짝미(모여서 짝으로 미션) 및 네트워킹을 활용하여 해결했습니다.

<br>
<br>

## **3. AWS Architecture & CI/CD**
본 서비스는 AWS의 서비스 및 자원을 활용하여 구축 및 운영하고 있습니다. AWS CodePipeline을 사용하여 CI/CD 파이프라인을 구성하고, VPC 엔드포인트를 통해 프라이빗 서브넷의 EC2에 애플리케이션을 배포하고, 데이터베이스를 별도의 프라이빗 서브넷에 배치했습니다. 사용자와의 통신은 Route 53과 ALB 로드밸런서를 통해 관리합니다. 또한 보안을 위해 HTTPS를 구축했고 앞으로 사용자 트래픽을 고려한 Auto-Scaling 적용할 계획입니다.

![Untitled](https://github.com/user-attachments/assets/6edd2b1f-cbfd-40c8-8026-6997cdccb655)
  

<br>

## 4. Test Coverage
  <img alt="image" src="https://github.com/user-attachments/assets/85090c15-2c63-439f-b0f2-53f81783ccbe" max-width= 100 />



