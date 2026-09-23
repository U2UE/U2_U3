# EventRow

일정 한 건과 그 위의 날짜 구분줄.

- `.dayhead`: `surface-2` 줄, 날짜 12px 600 + 요일 11px `ink-3`. 오늘은 `accent-ink`와 「· 오늘」.
- `.ev`: 72px 시각 칸(mono 12px `ink-2`, 종일은 「종일」 `ink-3`) + 제목(500, 말줄임) + 장소·분류(12px `ink-3`).
- 마감 일정은 제목 옆 마감 Badge. 취미 일정은 `.hobby`(`opacity-hobby`, 제목 400 `ink-2`).
