# 일따일 (ilttail)

## 프로젝트 개요
- 앱 이름: 일따일 (ilttail)
- 한 줄 설명: "일단 따라하는 일본어"
- 타겟: 한국 사용자, 일본어 입문~중급
- 플랫폼: iOS

## 기술 스택
- 언어: Swift
- UI: SwiftUI
- 아키텍처: Clean Architecture + MVVM
- 모듈화: Tuist (Micro Feature Architecture)
- 네비게이션: Router (NavigationStack 기반)
- 비동기: Swift Concurrency (async/await)

## 아키텍처
- Clean Architecture (Presentation / Domain / Data)
- Tuist 모듈화 (Micro Feature Architecture)
- Feature별 독립 모듈 (각 Feature가 자체 Domain/Data/Presentation 보유)
- Feature 간 공유: SharedDomain + Interface 혼합 전략
- 의존성 역전 원칙 (DIP) 준수
