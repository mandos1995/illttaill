# 일따일 (ilttail)

## 프로젝트 개요
- 앱 이름: 일따일 (ilttail)
- 한 줄 설명: "일단 따라하는 일본어"
- 타겟: 한국 사용자, 일본어 입문~중급
- 플랫폼: iOS

## 기술 스택
- 언어: Swift
- UI: SwiftUI + UIKit
- 아키텍처: MVVM-C (Coordinator)
- 모듈화: Tuist
- 비동기: Swift Concurrency (async/await)

## 아키텍처
### MVVM-C 구조
- Model: 데이터 모델
- View: SwiftUI View
- ViewModel: 비즈니스 로직, 상태 관리
- Coordinator: 화면 전환 로직

### 모듈 구조
- Core: 공통 유틸, 익스텐션
- Domain: Entity, UseCase
- Data: Repository, 로컬/네트워크 데이터 소스
- Feature: 화면별 모듈 (단어장, 학습, 퀴즈 등)
