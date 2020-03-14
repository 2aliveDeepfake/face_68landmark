# face_68landmark
얼굴에 68랜드마크 표시하는 코드

얼굴영역 분할과 코드 통합 예정

실행 환경 : 리눅스
실행에 필요한 라이브러리 
PyTorch >= 0.4.1 (PyTorch v1.1.0 is tested successfully on macOS and Linux.)
Python >= 3.6 (Numpy, Scipy, Matplotlib)
Dlib (Dlib is optionally for face and landmarks detection. There is no need to use Dlib if you can provide face bouding bbox and landmarks. Besides, you can try the two-step inference strategy without initialized landmarks.)
OpenCV (Python version, for image IO opertations.)
Cython (For accelerating depth and PNCC render.)

원 코드 : https://github.com/cleardusk/3DDFA
