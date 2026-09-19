# 통합 제품 인텔리전스·5단계 상세개발계획 v3.3

대상: 올영스캐너(Cloudflare Workers/R2 정적판, WeSaver Google OAuth 예정)

이 문서는 제품 코드가 아니라 실행 가능한 계획이다. 기존 v3.2 산출물을 보존·참조하고 5단계·96필드·시험·증거 계약을 추가한다.

## 1. STAGE-1-BASELINE
- 목적: 현행 파악·자료 보존·개발환경·안전 기준선
- 진입: 프로젝트 식별 완료
- 종료: 정본·범위·백업·실행·검사 기준선이 재현 가능
- 현재: PARTIAL_EXTERNAL_BLOCK
- 상세: stage-01/README.md

## 2. STAGE-2-FOUNDATION
- 목적: 구조·데이터·권한·공통 UI·핵심 기반
- 진입: 1단계 통과
- 종료: 후속 기능 의존 계약·구조·공통부가 시험 가능
- 현재: BLOCKED_EXTERNAL
- 상세: stage-02/README.md

## 3. STAGE-3-CORE
- 목적: 핵심 사용자 여정과 필수 기능
- 진입: 2단계 통과
- 종료: 정상·빈·로딩·오류·복구 흐름이 인수 기준 통과
- 현재: BLOCKED_PREREQUISITE
- 상세: stage-03/README.md

## 4. STAGE-4-QUALITY
- 목적: 전 분야 격차·통합·성능·접근성·보안·운영 내구성
- 진입: 3단계 통과
- 종료: 모바일·PC·권한·자료·장애·관측 품질 조건 통과
- 현재: BLOCKED_PREREQUISITE
- 상세: stage-04/README.md

## 5. STAGE-5-RELEASE
- 목적: 공개 준비·이전·전체 회귀·복구·인수인계·안정화
- 진입: 4단계 통과
- 종료: 출시 통과표·복구 시험·운영 문서와 차단 항목 확정
- 현재: BLOCKED_EXTERNAL
- 상세: stage-05/README.md

## 실행 순서
1. BASELINE 기준선 재현 및 권리·운영 게이트 식별
2. FOUNDATION에서 Cloudflare·OAuth·공통 UI 계약을 시험 가능한 형태로 고정
3. CORE에서 검색·상품 신뢰·계정 저장·광고 고지 여정을 구현
4. QUALITY에서 자동·브라우저·실기기·접근성·보안·성능 회귀를 차단
5. RELEASE에서 공개·복구·관측·인수인계를 검증

현재는 분석 전용 실행이므로 실제 구현·배포·OAuth 비밀 등록은 수행하지 않았다.