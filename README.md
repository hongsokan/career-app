# career

## 개인 프로젝트 : ios 취업 정보 어플 (2020.06.11 시작)
- 사람인, 잡코리아 등 사이트에서 ios 신입 공채 등 정보 알람 기능
- 원하는 정보 메모장에 저장, 혹은 이미지로 캡처
- 아이폰 캘린더에 원하는 공채 정보 전송
- 개인 일정 관리를 위한 기능도 추가

## 06.25
- 테이블뷰에 크롤링 데이터 보여주기
- 탭바 만들기 (기업정보, 캘린더, 마이페이지)

## 06.18
- 크롤링할 샘플 데이터 기준으로 모델 만들어보기
- 만든 모델 데이터 아이폰 캘린더로 전송하기 (날짜, 제목, url, 메모)

- sampleEvent 만들면서 self.titleLabel.text! 등 정보 가져올 때 메인 스레드에서 처리해야 되는 에러 발생 -> DispatchQueue 에서 처리

- [EKEvent](https://developer.apple.com/documentation/eventkit/ekevent)
- [How to add an event in the device calendar using swift](https://stackoverflow.com/questions/28379603/how-to-add-an-event-in-the-device-calendar-using-swift/36723472)
