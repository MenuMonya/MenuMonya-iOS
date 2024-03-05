## 메뉴머냐 - 강남 한식 뷔페 소개 앱
메뉴머냐는 강남 한식 뷔페 위치와 메뉴를 손쉽게 탐색할 수 있는 앱 입니다.

[App Store](https://apps.apple.com/kr/app/%EB%A9%94%EB%89%B4%EB%A8%B8%EB%83%90-%EA%B0%95%EB%82%A8-%ED%95%9C%EC%8B%9D-%EB%B7%94%ED%8E%98-%EB%A9%94%EB%89%B4%EB%A5%BC-%ED%95%9C-%EB%88%88%EC%97%90/id6448675881)

* Swift, SwiftUI, Naver Map SDk

<img src="https://github.com/MenuMonya/MenuMonya-iOS/assets/22342277/5d0acaae-b904-4074-ac17-1e039e9f7c36" width=400>

## 주요 경험
- 매일 업데이트되는 한식 뷔페 메뉴를 수집하기 위해 직접 평일 오전 강남 지역 20곳 이상의 한식 뷔페 메뉴판 사진을 찍어 메뉴 정보를 수집, DB에 업로드.
- 한식 뷔페의 위치를 표시할 지도 SDK를 고민, 문서화 및 디자인에서 강점을 가지는 네이버 지도 SDK를 사용하여 커스텀 마커 적용 및 지도 위 카메라 이동 기능을 구현.
- 한식 뷔페 정보를 보여주기 위한 Snap Carousel 카드 뷰를 구현하기 위해 DragGesture를 사용, 사용자의 드래그 방향과 속도에 따라 스냅 제스처를 인식 후 카드 인덱스를 증감하여 수평 스크롤 뷰 상에서 현재 보이는 카드 뷰를 변경
