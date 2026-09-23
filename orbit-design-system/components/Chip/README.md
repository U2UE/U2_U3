# Chip

패널 헤더 끝의 상태 칩: 데이터가 지금 어떤 상태인지 한 단어로.

- `.live`: `accent-soft`/`accent-ink` + 맥박 치는 6px 점 — 실시간 연결 정상. `title`에 「마지막 갱신 08:31 · …」.
- `.stale`: amber — 캐시만 있고 새로고침 실패. `.off`: `surface-2`/`ink-3` — 연결 중·꺼짐. `.sample`: 가데이터.
- 11px 500 대문자, letter-spacing .04em, `radius-pill`. 한 패널에 칩은 하나.
