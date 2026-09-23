# PanelTabs

여러 트래커를 한 패널에서 바꾸는 세그먼트 탭(Study · Career · Client).

- `.ptabs`는 `surface-2` 홈 안의 버튼 묶음, 선택된 버튼은 `surface` 면 + `ring-line` + `ink`. 각 버튼 앞 6px 점이 트래커 색(`accent` / `info` / `gig`), 비선택 점은 `opacity-dot-off`.
- 패널에 `.ptpanel`과 `data-tab="study|career|gig"`를 주면 상단 2px 선이 같은 색으로 바뀐다.
- 개수는 `.n`(mono 10px). 우측 끝에 「+ 외주 추가」 같은 추가 버튼과 저장 상태 칩.
