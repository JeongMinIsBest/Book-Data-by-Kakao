# 📚 Book-Data-by-Kakao

카카오 도서 데이터를 기반으로 책 정보(메타데이터, 장소, 이벤트 등)를 수집하고 가공합니다.
**책의 배경이 되는 실제 장소 및 이벤트 데이터를 정리**하여 다양한 활용(여행 계획, 문학 작품 분석, 교육 자료 개발 등)이 가능합니다.
<br/>

## ✨ 주요 기능
- 📖 **책 메타데이터 수집** : 카카오 API 기반 책 제목, 저자, 출판사, ISBN 등 정보 크롤링  
- 🗺️ **장소 및 이벤트 데이터화** : 소설/작품 속 장소와 사건을 실제 좌표 및 설명과 연결  
- 🗂️ **JSON 포맷 데이터 제공** : `book_location_event.json`, `book_metadata_kakao.json` 등 구조화된 데이터 제공  
- 🧾 **노트북 간편 실행** : `book_info_crawling.ipynb`를 통해 데이터 수집 및 가공 과정 확인 가능  
<br/>

## ⚙️ 설치 방법
```bash
# 저장소 클론
git clone https://github.com/yourusername/Book-Data-by-Kakao.git
cd Book-Data-by-Kakao

# 가상환경 생성 및 활성화 (선택 사항)
python -m venv venv
source venv/bin/activate   # (맥/Linux)
venv\Scripts\activate      # (윈도우)
```
<br/>

## 📂 데이터 구조

- ```Ver. Base/``` : 기본 데이터셋 (book_location_event.json, book_metadata_kakao.json)
- ```Ver. 0911/``` : 최신 버전 데이터셋
- ```book_info_crawling.ipynb``` : 카카오 API 기반 데이터 수집 주피터 노트북
<br/>
