# CourseCard

수강 중인 강의 한 개(가로 레일 카드, `card-width` 236px).

- 좌측 3px 스트라이프는 상태를 따른다: 시작 전(0/N) = `line-2` 중립 → 진행 중 = 플랫폼 색(`platform-*`) → 방치 = `warn` → 수강기한 임박 = `bad` → 완강 = `opacity-done`. 플랫폼 색은 시작한 강의에만 나타난다. 마크업: 진행 중에만 `--pc`를 주고, 나머지는 `.c-new` / `.c-stale` / `.c-due` / `.done`.
- 머리줄: 플랫폼(600 `ink-2`) · 분류 · 「이어서」 태그(현재 카드). 제목 13px 600 말줄임. 진행바 + `n/N`.
- 아래줄: 상태 문구(「3일째 안 봄」은 warn, 「기한 D-4」는 bad) + 「+1강」. 「−」「편집」은 hover 때만.
- 현재 카드 `.cur`: `surface` 면 + `accent` 테두리. 완강 `.done`: `opacity-done`.
