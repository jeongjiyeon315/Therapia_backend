# Therapia_backend

![슬라이드2](https://user-images.githubusercontent.com/63544044/206661157-9d42451f-c1e2-4e9d-ad16-b14f24b99873.JPG)
[테라피아 스토리보드](https://github.com/jeongjiyeon315/Therapia_backend/blob/main/%EC%82%AC%EC%97%B0%20%EC%8B%9C%EB%82%98%EB%A6%AC%EC%98%A4%20-THERAPIA.pdf)
--------------------------------------------
### 개발 배경   
코로나19로 인해 신체적/심리적 문제를 겪고 있는 사람들이 많아지고 있고, 코로나19 전까지만 해도 꾸준히 도시농업에 대한 관심이 증가했었음. Therapia는 라틴어로 '치료'라는 뜻을 담고 있는데 우리 서비스에서 치료는 두 가지의 의미를 담고 있음. 첫 번째는 '치유농장'을 통한 심적인 치료를 할 수 있다는 의미이고, 두 번째는 '작물 진단'을 통한 신체적인 치료를 할 수 있다는 의미임. 그래서 많은 사람이 농업으로 힐링하였으면 좋겠다는 마음으로 서비스를 고안함.  

### 기능 소개
![1번](https://user-images.githubusercontent.com/63544044/206660955-1ce04bf4-8aab-449c-853e-285661741250.png)
1. 농장 소개
- 가고 싶은 지역을 검색하여 지정  
- 해당 지역에서 ‘주말 농장’, ‘치유 농장’, ‘체험 농장’ 중 하나를 선택  
- 각각 눌러 농장들의 위치를 지도를 통해 바로 확인할 수 있고 상세 설명은 지도 아래에서 확인 가능  
![2번](https://user-images.githubusercontent.com/63544044/206661037-21cd1914-5841-4d9b-a4aa-ee2211f6bacc.png)
2. 작물 선택
- 자신의 증상에 가까운 것들을 체크하면 그 증상에 맞는 효능 작물을 소개해주는 서비스를 제작   
- 작물들로 음식을 만들 수 있게 원하는 작물을 선택하면 효능, 제철 시기, 보관방법, 재료, 레시피 정보를 제공 
![그림3](https://user-images.githubusercontent.com/63544044/206661213-08917251-1cf0-4391-a598-8a74ba07c1db.png)
3. 농장 추천도
- 도넛차트는 총 세 개이며 제목은 거리, 평점, 추천도임
- 거리는 현위치로부터 선택한 농장까지의 직선거리, 평점은 사람들이 리뷰와 함께 남긴 평점들의 평균, 추천도는 거리와 평균을 환산한 값의 평균임. 즉, 추천도를 측정하는 항목이 거리와 평점임

### 활용 데이터
1. 농림축산식품 공공데이터 포털 - [텃밭 분양 상세정보](https://data.mafra.go.kr/opendata/data/indexOpenDataDetail.do?data_id=20171122000000000916) (오픈 API 활용해 XML/JSON 포맷으로 데이터 획득)
2. 공공데이터포털 - [서울시 주말농장 현황](https://www.data.go.kr/data/15047308/fileData.do)(Excel 데이터를 활용해 데이터 획득 후 파이썬을 이용해 알맞게 가공)
3. 공공데이터포털 – [농촌진흥청_치유농장](https://www.data.go.kr/data/15081306/openapi.do) (오픈 API를 활용해 AJAX 방식으로 치유농장 데이터를 획득)

----------------------------------------------------------------------------
### Therapia API 문서
[API문서](https://jeongjiyeon315.notion.site/API-02168d25316644f89af3bda19b9624b8)
### Therapia ERD
![테라피아ERD](https://user-images.githubusercontent.com/63544044/172849734-612d9abb-6388-4c4b-a7ac-4e56ce3b3819.png)  
|커밋|컨벤션|
|-----|-----|
|Feat : |기능 추가|
|Fix : |버그 해결|
|Docs : |문서 수정 (README.md)|
|Rename : |파일명, 폴더명 수정 또는 이동|
|Chore : |사소한 수정, 소스코드 외 내용|
|Test : |테스트 커밋|
