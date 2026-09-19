# 측정·운영 명세

핵심 지표: 검색 성공률, 0건 회복률, 정확 SKU 클릭률, 판매처 도착률, 저장/복원 성공률, OAuth 성공률, LCP/CLS/TBT, 5xx, stale-feed 비율.

운영 주기: 매일 health·5xx, 주 1회 링크 샘플·R2 checksum, 월 1회 권리·정책·삭제 drill. 개인정보 없는 집계만 저장한다.

출시 인수: P0 증거 100%, 5xx·허위 가격·데이터 손실 0, rollback 15분 이내 재현.
