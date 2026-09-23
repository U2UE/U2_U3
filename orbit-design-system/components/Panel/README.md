# Panel

모든 정보 묶음의 그릇: `surface` 면, 1px `line` 테두리, `radius-6`, 헤더 한 줄.

- 헤더 `.ph`: 제목 `h2`(panel-title) + 부제 `.h2s`(12px `ink-3`, 예: 「14일」) → 출처 `.src`(「Google Calendar」) → 액션 버튼 → 상태 칩. 제목이 남는 폭을 모두 차지한다.
- 본문은 행 목록, 안내 `.note`(오류 `.note.err`, 주의 `.note.warn`), 맨 아래 `.more-toggle`(「+ 6개 더보기 (14일 내 11건)」).
- `.sample` 변형: 투명 면 + 점선 `line-2` — 가데이터일 때만.
- 마지막 갱신 시각은 패널에 적지 않고 LIVE 칩의 `title`로 보낸다.
