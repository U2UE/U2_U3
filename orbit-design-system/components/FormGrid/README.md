# FormGrid

추가·편집 폼(`.st-form`): 패널 안에서 펼쳐지는 자동 채움 그리드.

- `surface-2` 면, `repeat(auto-fill, minmax(160px, 1fr))`, 넓은 항목은 `.wide`(한 줄 전체).
- 라벨 11px `ink-3`가 위, 입력 13px `surface` 면 1px `line-2` `radius-5`.
- 라벨 문구가 곧 도움말이다: 「마감일 (바꾸면 연장 기록이 남아요)」, 「로그인 계정 (ID만 · 비밀번호 금지)」.
- 버튼 줄 `.row2`: 「저장」「닫기」, 오른쪽 끝 삭제(`bad` 글자), 상태 메시지는 mono `.meta`.
