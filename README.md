# 📚 Book-Data-by-Kakao
This project collects and processes book information (metadata, locations, events, etc.) based on **Kakao book data**. By organizing **real-world locations and events that form the background of books**, the data can be used for various purposes such as travel planning, literary analysis, and educational material development.
<br/>
<br/>

## ✨ Key Features
- 📖 **Book metadata collection**: Crawls book information such as title, author, publisher, and ISBN using the Kakao API  
- 🗺️ **Location and event data structuring**: Links locations and events in novels or literary works to real-world coordinates and descriptions  
- 🗂️ **JSON-formatted data provision**: Provides structured data such as `book_location_event.json`, `book_metadata_kakao.json`  
- 🧾 **Easy notebook execution**: Allows users to review the data collection and processing pipeline via `book_info_crawling.ipynb`  
<br/>
<br/>

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/Book-Data-by-Kakao.git
cd Book-Data-by-Kakao

# Create and activate a virtual environment (optional)
python -m venv venv
source venv/bin/activate   # (macOS/Linux)
venv\Scripts\activate    # (Windows)
```
<br/>
<br/>

## 📂 Data Structure
- ```Ver. Base/``` : Base dataset (book_location_event.json, book_metadata_kakao.json)  
- ```Ver. 0911/``` : Latest version dataset  
- ```book_info_crawling.ipynb``` : Jupyter Notebook for Kakao API–based data collection  
<br/>
<br/>
