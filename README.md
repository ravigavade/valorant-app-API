# Valorant - Clutch Guide Api

This is a simple Flask-based API that serves video files stored in directories. Users can access videos dynamically from nested folders via HTTP GET requests.

## Features

- Serves video files from nested folders dynamically
- Handles errors if a folder or file is not found
- Secure file serving using Flask

## Folder Structure

```
mysite/
├── app.py  # Flask application
├── videos/
│   ├── folder1/
│   │   ├── video1.mp4
│   ├── folder2/
│   │   ├── video2.mp4
