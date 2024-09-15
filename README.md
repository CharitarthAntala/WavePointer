

# WavePointer
Our project WavePointer makes human computer interaction simple by making use of Hand Gestures. The computer requires almost no direct contact.
Currently, wireless mouse or a Bluetooth mouse still use a battery for power and a receiver to connect it to the PC. In the proposed system, this limitation can be overcome by employing webcam or a built-in camera.
All I/O operations can be virtually controlled by using static and dynamic hand gestures. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures. It leverages models such as CNN implemented by MediaPipe running on top of pybind11.
Currently it works on Windows platform.
WavePointer’s domains are not restricted as in our application can be used in diverse domain by all type of users ranging from regular user to industry professionals.


# Getting Started

  ### Pre-requisites
  
  Python: (3.6 - 3.10.2)<br>
  Anaconda Distribution: To download click [here](https://www.anaconda.com/products/individual).
  
  ### Procedure
  ```bash
  git clone https://github.com/rdr6000/WavePointer.git
  ```
  For detailed information about cloning visit [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
  
  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install pywin32
  ```
  ```bash 
  pip install pipwin
  ```
  ```bash 
  pipwin install pyaudio
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Command may look like: `cd C:\Users\.....\WavePointer\src`
  
  Step 6:
  ```bash 
  python start.py
  ```
