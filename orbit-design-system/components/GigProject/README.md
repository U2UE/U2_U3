# GigProject

외주 프로젝트 한 건 — Client 탭의 본체.

- 머리줄 `.gp-hd`: 프로젝트명(14px 600) · 클라이언트(12px `ink-3`) · 마감 DdayBadge · 대기 Badge · 「Sheet」 · 「편집」. 연장 이력은 `.gnote`(「연장 1회」), 캘린더 날짜 불일치는 `.gnote.w`.
- 상태줄 `.gp-st`: 단계 Segmented · `accent` 진행바 · 「완료 **4/14** · 진행 2 · 자료 대기 1」 · 보기 전환(할 일 | 금액).
- 금액 보기: `.gm-sum` 요약(기준 · 변경 · 현재 · 실수령(3.3% 원천징수) · 입금 · 남은 돈), 변경은 `accent-ink`(+)/`bad`(−), 남은 돈 `ink` 700. `gig`는 Client 탭 점·패널 윗선에만 쓴다. 아래 `.gcols` 2칸(금액 변경 / 입금)에 MoneyRow.
- 금액은 금액 보기에서만 보인다(v32). 정산 완료는 `.fin`(`opacity-fin`), 본문 접힘.
