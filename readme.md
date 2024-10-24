# Google Image Downloader

A Python-based application to download images from Google Images with a clean web interface.

## 📝 Features

- Simple and intuitive web interface
- Batch download of images from Google
- Custom search query support
- Specify number of images to download
- Download progress tracking
- Image preview functionality
- Customizable download directory

## 🛠️ Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python with Flask
- **Image Download**: google_images_download package
- **Styling**: Bootstrap 5

## ⚙️ Installation

1. Clone the repository
```bash
git clone https://github.com/lugsociety/Google-Image.git
cd google-image-downloader
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages
```bash
pip install -r requirements.txt
```

## 📦 Dependencies

```txt
flask==2.0.1
google_images_download==2.8.0
requests==2.26.0
pillow==8.3.1
```

## 🚀 Usage

1. Start the Flask server:
```bash
python app.py
```

2. Open your browser and navigate to `http://localhost:5000`

3. Enter your search query and desired number of images

4. Click "Download" and wait for the process to complete

## 📁 Project Structure

```
google-image-downloader/
│
├── app.py                 # Flask application
├── requirements.txt       # Project dependencies
├── README.md             # Project documentation
│
├── static/
│   ├── css/             # Stylesheets
│   ├── js/              # JavaScript files
│   └── downloads/       # Downloaded images
│
└── templates/
    └── index.html       # Main interface
```

## 💻 Development

### Setting Up Development Environment

1. Fork the repository

2. Create a new branch
```bash
git checkout -b feature/your-feature-name
```

3. Make your changes and commit
```bash
git add .
git commit -m "Add your commit message"
```

4. Push to your fork
```bash
git push origin feature/your-feature-name
```

5. Create a Pull Request

### Code Style

- Follow PEP 8 guidelines for Python code
- Use meaningful variable and function names
- Add comments for complex logic
- Write docstrings for functions and classes

## 🤝 Contributing

1. Fork the project
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources

- [google-images-download PyPI Package](https://pypi.org/project/google-images-download/)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [GitHub Pages Hosting Guide](https://pages.github.com/)
- [Heroku Deployment Guide](https://devcenter.heroku.com/articles/getting-started-with-python)

## ⚠️ Disclaimer

This tool is for educational purposes only. Please review Google's terms of service and ensure compliance with their policies when downloading images.

## 📧 Contact

- Create an issue in this repository
- Email: lugtu@thapar.edu
- Project Link: https://github.com/lugsociety/Google-Image
