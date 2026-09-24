# BriefTile

브리핑 줄의 한 칸: 왼쪽 키(1행)와 한 줄 설명(2행), 오른쪽에 값 하나. 높이 84px, padding 14px 18px, 값은 두 행에 걸쳐 수직 중앙.

- `.k` label 11px 대문자 .08em ink-3 / `.s` 14px ink 1줄 말줄임 / `.v` tile-value 32px + `<small>` tile-unit.
- 값 슬롯은 숫자·라틴만: DEADLINE `D-1` · NOW `3<small>건</small>`(오늘 실행 가능 후보 수) · INBOX `9<small>/ 10통</small>` · STUDY `2<small>일</small>`(미수강 일수).
- 설명 행: DEADLINE 마감명 · NOW 할 일명 + 프로젝트 · INBOX 계정별 건수 · STUDY `0/11 시작 · 이어서 강의명`.
- 톤: 기본 값색 ink. `.bad` = D≤3(면 bad-soft). `.warn` = Study 미수강 1~6일, 7일+는 `.bad`. NOW·INBOX는 상시 기본색.
- `.now`의 「완료 · 넘김」은 1행 키 오른쪽 11px(키와 동일 크기) 텍스트 버튼, 키와 baseline 정렬(외곽선·배경 없음). 버튼 행을 추가하지 않는다.
- 줄은 4칸 고정(860px 이하 2칸). 칸을 추가하지 않는다.
