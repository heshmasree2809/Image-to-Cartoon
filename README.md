<div align="center">

# 🎨 Image to Cartoon AI

### Turn Real-World Images into Cartoon Art with AI ✨

**Transform ordinary photographs into artistic cartoon illustrations using deep learning and computer vision.**

<br>

[![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)](https://www.tensorflow.org/)
[![Flask](https://img.shields.io/badge/Flask-Web%20Application-000000?style=for-the-badge\&logo=flask\&logoColor=white)](https://flask.palletsprojects.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge\&logo=opencv\&logoColor=white)](https://opencv.org/)

<br>

**📷 Upload an Image   →   🧠 AI Processing   →   🖼️ Cartoon Transformation**

</div>

---

## 🌟 About the Project

Ever wondered what your photographs would look like as cartoons?

**Image to Cartoon AI** is a deep-learning-powered application that transforms ordinary images into cartoon-style artwork. It uses a White-box Cartoonization model to produce stylized images while preserving important visual characteristics of the original photograph.

Built with Python, TensorFlow, computer vision, and Flask, the application provides a web interface for uploading images and viewing their cartoonized results.

The project also includes video-processing functionality, allowing video files to be transformed into cartoon-style videos when the required dependencies and configuration are available.

### ✨ What Makes It Interesting?

* 🎭 **AI-Powered Cartoonization:** Transform photographs using a deep learning model.
* 🖼️ **Image Transformation:** Upload an image and generate its cartoonized version.
* 🎬 **Video Cartoonization:** Process videos into cartoon-style outputs.
* 🧠 **Deep Learning:** Use a pretrained White-box Cartoonization model.
* 🌐 **Web Interface:** Interact with the application through a Flask-powered interface.
* ⚙️ **Configurable Processing:** Adjust supported processing options through the project configuration.

---

## 🚀 How It Works

The application follows a straightforward image-processing pipeline.

| Step | Process           | Description                                                                  |
| :--: | ----------------- | ---------------------------------------------------------------------------- |
|  01  | 📤 Upload         | Select an image through the web interface.                                   |
|  02  | 🔍 Preprocessing  | Read the uploaded image and convert it into a suitable image representation. |
|  03  | 🧠 AI Inference   | Pass the image through the White-box Cartoonization model.                   |
|  04  | 🎨 Transformation | Generate the cartoonized image.                                              |
|  05  | 🖼️ Output        | Display the resulting artwork in the web interface.                          |

---

## 🛠️ Technology Stack

| Technology               | Purpose                                  |
| ------------------------ | ---------------------------------------- |
| Python                   | Core application development             |
| TensorFlow               | Deep learning inference                  |
| White-box Cartoonization | Image stylization model                  |
| OpenCV                   | Image processing and file operations     |
| NumPy                    | Numerical and image-array operations     |
| Pillow                   | Image loading and conversion             |
| Flask                    | Web application and request handling     |
| FFmpeg                   | Video processing and frame-rate handling |
| YAML                     | Application configuration                |

---

## 📂 Project Structure

```text
Image-to-Cartoon/
│
├── static/
│   ├── cartoonized_images/
│   └── uploaded_videos/
│
├── templates/
│   ├── index_cartoonized.html
│   └── ...
│
├── white_box_cartoonizer/
│   ├── saved_models/
│   └── ...
│
├── app.py
├── video_api.py
├── config.yaml
├── requirements.txt
├── .gitignore
├── .dockerignore
├── LICENSE
└── README.md
```

*Note: The structure above highlights the main project components. Exact files and subdirectories may vary.*

---

## ⚡ Getting Started

Follow these steps to run the application locally.

### 1. Clone the Repository

```bash
git clone https://github.com/heshmasree2809/Image-to-Cartoon.git
```

Navigate into the project directory:

```bash
cd Image-to-Cartoon
```

### 2. Create a Virtual Environment

Using Python's built-in `venv` module:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

On Linux or macOS:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Compatibility note:** The original project was tested with an older software stack, including Python 3.7 and TensorFlow 2.1.0. Modern Python versions may require dependency adjustments. Check the model requirements before choosing your environment.

### 4. Configure the Application

Open `config.yaml` and review the available settings.

Check the configured model directory, GPU settings, local execution options, and other parameters before starting the application.

For local processing, ensure that the required model files and weights are present.

Some optional video-processing or cloud-processing configurations may require additional dependencies and credentials.

### 5. Launch the Application

```bash
python app.py
```

If startup is successful, open your browser and navigate to:

**http://127.0.0.1:8080**

You can then explore the application's available functionality.

---

## 🎬 Image and Video Processing

### 🖼️ Image Cartoonization

1. Open the web application.
2. Select an image to upload.
3. Submit the image for processing.
4. Allow the model to generate the cartoonized result.
5. View the transformed image.

### 🎥 Video Cartoonization

The application also contains a video-processing workflow.

Depending on the selected configuration, video processing may require:

* FFmpeg installed and available on your system.
* Additional Python video-processing dependencies.
* Compatible model files and sufficient computational resources.
* Additional configuration for optional cloud-based processing.

Video processing performance depends on the input resolution, frame rate, model configuration, and available hardware.

---

## 💡 Potential Applications

Explore how AI-powered cartoonization can be used in creative projects.

* 🎨 Digital art and creative photography.
* 👤 Personalized cartoon portraits.
* 📱 Social media profile artwork.
* 🎬 Stylized video content.
* 🧪 Experiments in deep learning and computer vision.
* 🎓 Educational demonstrations of neural-network-based image transformation.

These are potential applications of the technology rather than claims that every use case has been implemented in the current application.

---

## 🔮 Future Enhancements

Ideas for taking the project further:

* [ ] Add multiple artistic styles, such as anime, pencil sketch, watercolor, and comic effects.
* [ ] Build an interactive before-and-after comparison slider.
* [ ] Introduce drag-and-drop image uploads.
* [ ] Add batch image processing.
* [ ] Improve error handling and upload validation.
* [ ] Add a download button for generated artwork.
* [ ] Develop a responsive, modern user interface.
* [ ] Add Docker-based deployment and reproducible environments.
* [ ] Explore GPU acceleration and inference optimization.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Implement your changes.
4. Test your implementation.
5. Submit a pull request describing your contribution.

If you encounter a bug or have a feature idea, open an issue in the repository.

---

## 📜 License

This repository includes a `LICENSE` file. Review it before using, modifying, or redistributing the project.

Also review the licensing terms of any pretrained model, dataset, or third-party dependency used by the application.

---

## 👩‍💻 Developer

**Avuthu Heshma Sree**

GitHub: [@heshmasree2809](https://github.com/heshmasree2809)

Project: [Image-to-Cartoon](https://github.com/heshmasree2809/Image-to-Cartoon)

---

<div align="center">

### ✨ From Pixels to Cartoon Magic ✨

*Exploring the creative possibilities of deep learning and computer vision.*

**If you find this project interesting, consider giving the repository a ⭐!**

</div>
