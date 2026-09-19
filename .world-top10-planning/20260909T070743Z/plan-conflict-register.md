# 계획 충돌 기록

|ID|충돌|이전 주장|현재 증거|처리|
|---|---|---|---|---|
|CON-001|v4/v7의 완료율 vs 현재 OAuth|구현·상용화 완료로 읽힐 수 있음|OAuth 공개 엔드포인트 503|완료율 주장과 분리, 외부 차단|
|CON-002|GitHub Pages vs Cloudflare 대표 주소|Pages가 주 호스팅으로 기록|Cloudflare custom domain HTTP 200|Cloudflare를 현재 공개판, Pages를 rollback으로 분리|
|CON-003|Top10 이전 분석의 비유사 후보|MyFitnessPal·Clue 등 포함|v3.2 카탈로그 범위와 유사도 재평가|SUPERSEDED, 재사용하지 않음|
|CON-004|정적 개인정보 문구|Google 계정 저장 미제공 문구|Worker는 계정 경로를 준비했으나 503|구현 상태와 공개 문구 갭으로 등록|

미해결 충돌은 BLOCKED_BY_DECISION으로 남기며 구현 완료로 바꾸지 않는다.
