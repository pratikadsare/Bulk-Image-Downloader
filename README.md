# Bulk Image Downloader

A Streamlit app to download images in bulk from URLs and package them into a ZIP file.

## Features

- Paste image URLs directly
- Upload TXT or CSV containing URLs
- Try to use original filename from server response
- Fallback to CDN or URL filename
- ZIP download with report CSV
- Parallel downloads for faster processing

## Run locally

```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
