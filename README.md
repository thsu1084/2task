# 날씨, 일기를 작성/조회/수정/삭제 하는 백엔드를 구현

### 최종 구현 API 리스트

#### POST /create/diary
- date parameter로 받아주세요. (date 형식: yyyy-MM-dd)
- text parameter로 일기 글을 받아주세요.
- 외부 API에서 받아온 날씨 데이터와 함께 DB에 저장해주세요.

#### GET /read/diary
- date parameter로 조회할 날짜를 받아주세요.
- 해당 날짜의 일기를 List 형태로 반환해주세요.

#### GET /read/diaries
- startDate, endDate parameter로 조회할 날짜 기간의 시작일/종료일을 받아주세요.
- 해당 기간의 일기를 List 형태로 반환해주세요.

#### PUT /update/diary
- date parameter로 수정할 날짜를 받아주세요.
- text parameter로 수정할 새 일기 글을 받아주세요.
- 해당 날짜의 첫번째 일기 글을 새로 받아온 일기글로 수정해주세요.

#### DELETE /delete/diary
- date parameter로 삭제할 날짜를 받아주세요.
- 해당 날짜의 모든 일기를 지워주세요.
