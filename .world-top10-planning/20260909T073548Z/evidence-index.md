# 증거 색인

- A: 공식 문서 또는 직접 재현 응답
- B: 프로젝트 파일·자동 검사·브라우저 관찰
- C: 보조 정황
- U: 미확인

|ID|내용|상태|근거|
|---|---|---|---|
|EVD-001|Cloudflare root/mobile/dashboard/API HTTP 200|확인|SRC-OWN-002~004|
|EVD-002|OAuth start/me/snapshot fail-closed 503|확인|SRC-OWN-005|
|EVD-003|R2 정적 자산 234개씩·전용 Worker 바인딩|확인|STATE.json·D-056|
|EVD-004|31/31 통합 테스트·4,108/83 공개판 검사|확인|SRC-OWN-007|
|EVD-005|Android ADB 장치 없음|미실시|adb devices -l|
|EVD-006|WeSaver 프로젝트 직접 조회 권한 없음|차단|gcloud projects describe wesaver|
|EVD-007|ShopStyle 소비자 서비스 종료|확인|SRC-SHP-001|
