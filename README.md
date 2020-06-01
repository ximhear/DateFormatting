# DateFormatting
SwiftUI로 String -> Date로 변환, 다시 String로 변환하는 샘플.

String -> Date변환시 DateFormatter에 locale를 설정하지 않으면 변환 실패하는 경우가 있다.

재현 경로
- iOS 13 이상
- 12시간제. 24시간제로 하면 발생하지 않음.
- 지역을 일본으로 설정.

