# TaskRow

외주 작업 묶음 칸(`.gcol`)과 그 안의 작업 한 줄(`.tk`).

- 칸 머리: 묶음 이름(12px 600) · `accent` 진행바 · `완료/전체`(mono 11px).
- 작업 줄: 이름(클릭하면 인라인 편집 `.tk-in`, `accent` 테두리) · 메모(11px `ink-3`) · StatusSelect. 완료는 이름 취소선.
- 마지막 줄 `.tk-add`: 「+ 항목」(11px `ink-3`, hover `accent-ink`). 입력 규칙: 「이름 / 메모」, Enter 추가, Esc 취소, 비우고 Enter면 삭제.
