
import pyrealsense2 as rs
import numpy as np
import cv2

위 라이브러리를 import 시켜야 한다.

pip install pyrealsense2     # pyrealsense2
pip install numpy            # numpy
pip install opencv-python    # cv2

여기서 pyrealsense2가 설치가 안될 수 있는데 https://pypi.org/project/pyrealsense2/#files 이 사이트로 들어가서 
pyrealsense2-2.55.1.6486-cp311-cp311-manylinux1_x86_64.whl 라고 적어진 파일을 다운로드하여 리눅스에서 설치한다.
설치 명령어 : pip install pyrealsense2-2.55.1.6486-cp311-cp311-manylinux1_x86_64.whl
파일 설치할 때 파이썬 버전을 3.11.xx로 맞춰야 하기 때문에 다른 버전이면 버전 수정 후 설치. 파이썬 재설치에는 파이썬 말고도 pip도 새로 설치해야 한다.
그래도 안되면... 직접 해봐야 될듯

------------------------------------------------------------------------------------------------------------------------------------------------

실행 방법 : 
그냥 run 시키면 된다. 그러면 창 하나가 뜨는데 왼쪽은 일반 카메라로 찍은 화면, 오른쪽은 깊이가 적용된 색깔로 구별된 화면이 뜬다.
종료는 "ctrl + c"

------------------------------------------------------------------------------------------------------------------------------------------------

2025.01.14_14:23 :
Visual studio code 에서 우분투 가상환경에서 실행 안됨. 우분투에서 카메라 연결을 인식 못하는 문제.
