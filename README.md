# 🌟 Face Swap Flask App 🌟

## 🎯 Aim
The goal of this project is to swap faces from a source image to a given destination image.

## ✨ Features
- 🖼️ Extracts human faces using OpenCV and dlib.
- 📍 Utilizes a pretrained model to extract facial landmarks.
- 🌐 Implements a web application using Flask.

## 🛠️ Technologies Used
- **OpenCV**: For image processing and face detection.
- **dlib**: For extracting facial landmarks.
- **Flask**: For creating the web application.

## 📦 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/face-swap-flask-app.git
    cd face-swap-flask-app
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

1. Run the Flask app:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000`.

3. Upload the source and destination images to perform the face swap.

## 📂 Project Structure
- `app.py`: The main Flask application file.
- `templates/`: Contains the HTML templates for the web app.
- `static/`: Contains static files like CSS and JavaScript.
- `requirements.txt`: Lists the dependencies required for the project.

## 🤝 Contributing
Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements
- OpenCV
- dlib
- Flask
