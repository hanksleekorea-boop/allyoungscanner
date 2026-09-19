# 보안·개인정보·접근성 명세

- 비밀값은 저장소·로그·보고서에 기록하지 않는다.
- OAuth Client Secret·OAUTH_STATE_SECRET은 Cloudflare Secret으로만 주입한다.
- 공개 페이지는 CSP·HTTPS·nosniff·referrer 정책을 유지한다.
- 개인정보 최소 수집: Google sub/email/display name과 스냅샷만. 삭제는 사용자별 D1 행 삭제로 검증한다.
- 광고·affiliate는 동의·고지·순위 독립성을 분리한다.
- 키보드 44px 터치·focus·aria-live·색 대비·한국어/영어를 자동+브라우저+실기기로 각각 기록한다.
- 실제 보조기술과 Android/iOS는 미실시를 완료로 바꾸지 않는다.
