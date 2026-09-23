# StatusSelect

외주 작업 한 줄의 상태를 바꾸는 알약 셀렉트(`.tks`): 예정 · 자료 대기 · 진행 · 완료.

- 예정·완료: `surface` 면 + `ring-line-inset`, `ink-3`. 완료는 배지를 더하지 않고 작업 이름에 취소선만 긋는다.
- 자료 대기(클라이언트에게 받을 것): `warn-soft`/`warn`. 진행: `info-soft`/`info`.
- 11px 600, 가운데 정렬, `radius-pill`. TaskRow 안에서만 쓴다.
