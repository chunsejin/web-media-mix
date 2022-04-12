# web-media-mix metadata 개발

웹툰, 웹 소설, 웹드라마 등 웹 콘텐츠 시장이 전 세계적으로 증가하고 있습니다. 만화책을 위한 Comic Book ontology처럼 단일 매체용 정보 모델은 존재했지만, 미디어 믹스로 인해 기존의 정보 모델로 설명 불가능한 관계가 등장했습니다. 예시로는, 웹툰의 드라마화로 인한 웹툰의 등장인물과 드라마 배우 간의 관계 등이 있습니다. 이런 관계를 효과적으로 검색/질의/구독하기 위한 정보 데이터 모델은 존재하지 않습니다. 따라서 관계 및 속성에 대한 개념을 공유/개방 가능한 형태로 모델링하고 자 합니다.

# 미디어 믹스란?
하나의 콘텐츠를 영화, 드라마, 게임, 음반, 굿즈, 장난감, 출판 등의 다양화 방식으로 판매하는 것을 말합니다. 웹툰 원작을 영화로 만든 신과 함께 등이 있습니다. 

# 메타 데이터란?
데이터를 설명하는 데이터로, 사진의 경우 크기, 촬영 날짜, 태그 등이 있습니다. 태그처럼 데이터를 설명하기 위한 목적이나, 날짜처럼 데이터를 빨리 찾기 위한 목적으로 작성합니다. 

# 현재 단계 및 향후 방향
웹툰 미디어 믹스의 대략적인 구조는 설계되어 있으나, 특정 프로그래밍 언어로 표현되지 않았기 때문에 프로그램적으로 사용하기가 어렵습니다. 주어진 자료를 Human- and machine- readable 하며 공유 가능한 포맷으로 변환하는 작업을 수행합니다.

# 사용 도구
Labelled Property Graph(LPG)를 기반으로 지식 그래프를 작성합니다. 
[arrows.app](https://arrows.app/)을 이용해(LPG) 기반 지식 그래프를 그려 볼 수 있습니다. Export 형식은 JSON입니다. 


# 참고

현재 아이디어는 성소정, 최소원으로부터 시작되었습니다. 

# 참고 문헌
- [웹툰캐릭터의 미디어믹스전략에 관한 연구](http://www.riss.kr/search/detail/DetailView.do?p_mat_type=be54d9b8bc7cdb09&control_no=f6c6137ed82e927effe0bdc3ef48d419&keyword=%EB%AF%B8%EB%94%94%EC%96%B4%EB%AF%B9%EC%8A%A4)
