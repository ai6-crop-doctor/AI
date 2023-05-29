## Crop Doctor Main Service
### 작물 질병 진단 인공지능 모델 
![image](https://github.com/ai6-crop-doctor/AI/assets/72302404/cf02844a-06a2-439e-9634-bd7a91a808e8)




## Project Start


### .env

```
aws_access_key_id 
aws_secret_access_key 
endpoint_url 
```


### 터미널

```
# ai 폴더로 이동
cd ai

# 선택사항: (충돌 방지) 가상환경 설정 
conda create -n cropdoctor python=3.8
conda activate cropdoctor

# 필요 패키지 설치 
pip install -r requirements.txt

# 실행 
uvicorn main:app --reload
```
