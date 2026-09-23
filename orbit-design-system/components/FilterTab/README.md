# FilterTab

목록을 거르는 알약 탭 한 줄(전체 · 개인 · 취미 · 외주·업무 · 마감).

- 기본: 1px `line-2`, `ink-2`, 12px. 선택(`aria-selected="true"`): `accent-soft` 채움, `accent-ink` 600, 테두리 없음.
- 개수는 `.n` mono 11px, 불투명도 .7.
- 예외: 「취미」 탭은 선택돼도 `surface-2`/`ink-2`로 조용하게 — 취미 일정은 저채도다.
- 줄은 패널 헤더 바로 아래 `.tabs`, 좌우 `space-16`.
