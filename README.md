# Multimodal Authentication System

A secure and flexible multimodal authentication system that supports both facial recognition-based login and traditional credential-based login with OTP verification. This project is built using Python and Flask, and integrates computer vision for face authentication.

---

## Features

- Face registration and face-based login using webcam
- Credential-based login with email OTP verification
- Flask-based backend
- Modular structure for ease of development and extension

---

## Environment Setup

### 1. Create and activate virtual environment

```bash
# Create a conda environment with Python 3.8.10
conda create -n authsys python=3.8.10

# Activate the environment
conda activate authsys
```
### 2. Install required libraries

```bash
# Install these Libraries in your virtual environment
pip install flask
pip install opencv-python
pip install cmake
pip install dlib
pip install face_recognition
```
### Running the project 

```bash
python app.py
```
## License

[MIT](https://choosealicense.com/licenses/mit/)


