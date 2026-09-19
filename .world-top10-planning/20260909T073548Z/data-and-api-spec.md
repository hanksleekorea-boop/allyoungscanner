# 데이터·API 명세

- R2 STATIC: 공개 HTML/JS/CSS/JSON/이미지, 경로 정규화·ETag·HEAD 지원.
- D1: users, sessions, user_snapshots (migrations/0001_google_auth.sql).
- GET /api/catalog, /api/store-links, /api/guides: 공개 읽기.
- GET /api/me, GET/PUT/DELETE /api/account/snapshot: 인증 후 사용자 데이터. 미설정 시 503 fail-closed.
- OAuth: Google OIDC + PKCE + state/nonce + HttpOnly Secure SameSite cookie.
- 가격·제휴·검색 쓰기 API: 현재 미이주·미공개, 503 또는 미지원으로 표시.
