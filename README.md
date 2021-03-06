# 회식나우(Whesiknow) 안드로이드 애플리케이션

- 회식나우란?

불특정 다수의 사용자가 회식(식사 자리)을 하게 됐을 경우 적절한 회식 장소 예약을 도와주고 더 나아가 해당 식당의 메뉴를 미리 주문할 수 있게끔 하여 회식의 편의성을 극대화하는 서비스

---

- 애플리케이션 환경

1. Android API 23 (MIN : API 15)
2. Gradle 2.10
3. Dependencies : butterknife:8.2.1, facebook-android-sdk:4.+, kakao-sdk:1.1.20, google-play-services:9.2.1, retrofit:2.1.0, Okhttp:3.4.1

---

- 역할


1. 자체적으로 여러 개의 테마를 정하여 테마별 식당을 사용자에게 회식 장소로 추천
2. 애플리케이션 사용자의 후기를 누적하여 랭크(Rank) 시스템을 구축하고, 해당 랭크를 사용자에게 제공하여 사용자에게 인기있는 식당 정보를 제공
3. 자신의 위치를 기반으로 근처에 있는 식당 정보 제공
4. 식당과의 협약을 통한 이벤트 / 패키지를 구성하여 회식 상품 제공 (예정)
5. 회식을 진행하는 회원이 현재 자신이 있는 식당에서 얼마나 먹었는지 바로 확인할 수 있는 실시간 회식 정보 제공(예정)
6. '식당 선택 -> POS기 연동을 통한 예약 -> 결제' 3단계 과정을 통한 예약 기능 제공(예정)

---

- 개선할 사항

1. 촘촘한 예외 처리 필요
2. 레이아웃 및 소스 정리 필요
3. 역할들 중 아직 개발하지 않은 예정 사항들 개발 필요
4. 애플리케이션의 특성상 업데이트를 하면 바로 반영되지 않기 때문에 자동으로 업데이트할 사항들을 체크하는 기능 탑재 필요
5. iOS 개발 필요

---

* [플레이 스토어 링크](-)
* [회식나우 서비스 서버 Github](https://github.com/knunu/whesiknow_server)


