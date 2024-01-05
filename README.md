# MovieReview App입니다
MVVM 패턴 및 RxSwift 공부용 앱입니다.    
왓챠피디아의 UI가져오되 약간의 수정으로 좀 더 기능이 적은 앱을 만들어볼 예정이다.    
탭바를 제외시키고 UI를 구현할 생각    
영화목록, 검색, 영화 상세화면, 나의 평가 목록 등만 표시하도록 하는 앱        
[TMDB API](https://developer.themoviedb.org/reference/intro/getting-started)를 활용하여 제작

[피그마 UI](https://www.figma.com/file/ToFENHzJos7i78eWAI4OY9/Untitled?type=design&node-id=0-1&mode=design&t=aVVnItmoqdkZ4ty4-0)

# 데이터 모델
### Movie
- 간단한 영화 정보
- id, 제목, 영화 포스터 이미지, 개봉일, 평균 점수

### MovieDetail
- 자세한 영화 정보
- id, 제목, 원문 제목, 장르, 영화 배경이미지, 포스터 이미지, 만든 나라, 개봉일, 러닝타임, 평균 점수, 평가수

### Review
- 영화 리뷰에 대한 정보
- 리뷰 남긴 사람, 리뷰 남긴 사람의 디테일 정보, 리뷰 내용, 생성일, 수정일

### Reviewer
- 영화 리뷰 남긴 사람에 대한 디테일 정보
- 이름, 닉네임, 프로필이미지, 별점


