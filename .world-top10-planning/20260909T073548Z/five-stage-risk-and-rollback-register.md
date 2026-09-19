# 5단계 위험·롤백 원장

| 위험 | 영향 | 탐지 | 예방 | 롤백 | 현재 상태 |
|---|---|---|---|---|---|
| WeSaver OAuth 미구성 | 로그인·저장 불가 | /auth/google/start 503 | secret·callback 사전 검증 | auth flag off, 이전 정적판 | BLOCKED_EXTERNAL |
| R2/D1 스키마 불일치 | 데이터 손실 | 계약·checksum 검사 | migration dry-run | migration down→read-only | BLOCKED_EXTERNAL |
| 광고/affiliate 권리 미확인 | 법적·신뢰 위험 | 출처/고지 감사 | 승인 원장 | 슬롯 비활성화 | BLOCKED_EXTERNAL |
| Android 실기기 미실시 | 모바일 회귀 미확인 | adb/수동 체크 | 유휴 A56 한 대 예약 | 모바일 공개 보류 | NOT_RUN |
| 성능 회귀 | 전환 저하 | LCP/CLS/TBT CI | 예산 게이트 | 이전 릴리스 복귀 | BLOCKED_PREREQUISITE |