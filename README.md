# Pdf-Website-Data-Extraction

This project is designed to extract text, images, and tables from both PDF documents and websites. The data is then stored in AWS S3 buckets for easy access and management. The project uses a combination of tools and libraries for PDF parsing, web scraping, and a web-based interface for user interaction.

## Live Demo:

You can try out the app live here: [Streamlit App Demo]([YOUR_STREAMLIT_LINK_HERE](https://damg7245team6-lshvwtf6d8aotrsg7tyvwy.streamlit.app/))

## Key Features:
- **PDF Data Extraction**: Extracts text, images, and tables from PDF files.
- **Website Data Extraction**: Scrapes text, images, and tables from websites.
- **AWS S3 Integration**: Stores extracted data in respective AWS S3 buckets.
- **User Interface**: Built with Streamlit to allow users to upload PDFs and input URLs for website scraping.
- **Backend**: FastAPI provides API endpoints for file uploads and website URL submissions.

## Technologies Used:
- **PDF Data Extraction**:
  - `PyMuPDF`: For extracting text, images, and tables from PDF files.
  - `Azure Data Intelligence`: For enhanced document processing and extraction from PDFs.
- **Website Data Extraction**:
  - `BeautifulSoup`: For parsing and scraping website data.
  - `ScrapingBee`: For web scraping with ease and avoiding anti-scraping mechanisms.
- **Frontend**:
  - `Streamlit`: For building a user-friendly interface for data upload and retrieval.
- **Backend**:
  - `FastAPI`: For creating API endpoints for file uploads and URL submissions.
- **Cloud**:
  - `AWS S3`: For storing extracted data in cloud buckets.
