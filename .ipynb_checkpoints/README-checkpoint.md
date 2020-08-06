# Base_line_code
  
  Follow [MINIKAGGLE]Face Emotion......ipynb
  
  make folder "test", "train"
  
  correct way to unzip dataset
  
  test->"images"
  
  train->label_0,label_1.........->images,images......
  
***  



## Use Google Colab

https://datascienceschool.net/view-notebook/f9d9fddb7cc7494a9e4be99f0e137be0/

코랩의 장점


>- 파이썬 설치 불필요 Python Installation unrequired

>- 다양한 라이버리가 이미 설치됨. Many library preinstalled

>-  **GPU 무료 사용**.  Free GPU ()


1. http://colab.research.google.com 접속/connect to
2. 런타임 -> 런타임 유형변경 ->GPU  / Runtime-> Change Runtime type -> to gpu
3. (옵션/optional) 좌측 폴더 아이콘 클릭->구글드라이브 심볼 클릭해서 연동 Click Folder icon on the left and click Google Drive for syncing

 *Runtime could close if no activity, and your data will be lost so save model and download just in case during training
 *directly reading whole images from drive sometimes cause unknown error, better upload zip files into google drive, and unzip to hosted'save_data' path, for details follow the code of unzipping in ColabMethond.ipynb

