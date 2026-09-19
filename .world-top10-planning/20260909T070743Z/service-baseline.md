# 서비스 기준선

## 판정

화장품을 검색·비교하고 여러 판매처에서 확인하도록 돕는 독립 뷰티 쇼핑 탐색 서비스. 현재 기준판은 2026-09-05-service-v0.40-shopping-trust이며 Cloudflare 대표 주소에서 정적 화면과 읽기 API가 공개 검증됐다.

## 사용자 여정

유입 → 검색/탐색 → 상세·근거 확인 → 비교·찜 → 판매처 이동 → 백업/복원 → 지원·정정 → 삭제

## 실제 상태

|표면|상태|근거|
|---|---|---|
|PC|PUBLIC_VERIFIED · HTTP 200|SRC-OWN-003|
|모바일|PUBLIC_VERIFIED · HTTP 200|SRC-OWN-004|
|대시보드|PUBLIC_VERIFIED · HTTP 200|SRC-OWN-003|
|Google OAuth|IMPLEMENTED_UNVERIFIED · 503 fail-closed|SRC-OWN-005|
|Android|미실시|EVD-005|
|WeSaver 권한|외부 차단|EVD-006|


계획 문서의 목표와 실제 공개 증거를 합산하지 않는다.
