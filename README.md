# MechineLearning_FireDetect

Dataset Link: https://www.kaggle.com/datasets/phylake1337/fire-dataset

BaseModel과 MainModel은 모두 Colab에서 작성 및 구동하였음.

[Use Colab]
1. 위의 링크를 통해 데이터셋을 다운로드.
2. 구글 드라이브 최상단 폴더에 압축상태와 이름 그대로 업로드. 최상단 폴더에 업로드하지 않을 시 경로를 수정해야함.
3. BaseModel과 MainModel의 코드를 Colab에 복사하여 Colab에서 구동.

[Use Others]
1. 위의 링크를 통해 데이터셋을 다운로드.
2. 다음의 코드를 지움.
from google.colab import drive
drive.mount('/content/drive')
!cp /content/drive/MyDrive/archive.zip ./
!unzip archive.zip
3. 데이터셋을 압축해제.
4. datasetpath = "fire_dataset" 의 코드에서 "fire_dataset"을 데이터셋이 위치한 경로로 수정.
