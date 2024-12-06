# Title (Please modify the title)
## Team

| ![김예승](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김도경](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김지식](https://avatars.githubusercontent.com/u/156163982?v=4) | ![은지영](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이홍록](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [김예승](https://github.com/UpstageAILab)             |            [김도경](https://github.com/UpstageAILab)             |            [김지식](https://github.com/UpstageAILab)             |            [은지영](https://github.com/UpstageAILab)             |            [이홍록](https://github.com/UpstageAILab)             |
|                            팀장, 담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |

## 0. Overview
### Environment
- streamlit
- mariaDB
- AWS RDS



## 1. Competiton Info

### Overview

- 영화추천 시스템
  
## 2. Components

### Directory

- _Insert your directory structure_

e.g.
```
├── code
│   ├── jupyter_notebooks
│   │   └── model_train.ipynb
│   └── train.py
├── docs
│   ├── pdf
│   │   └── (Template) [패스트캠퍼스] Upstage AI Lab 1기_그룹 스터디 .pptx
│   └── paper
└── input
    └── data
        ├── eval
        └── train
```

## 3. Data descrption

### Dataset overview

- TMDB 데이터 기반, 영화 추천 시스템
- MovieLens 데이터 기반, 협업 필터링 설계

### EDA

- ![image](https://github.com/user-attachments/assets/ee73e77c-206b-43ba-9385-35d33157d894)
- ![image](https://github.com/user-attachments/assets/4f04d9ad-5a21-4713-b681-8da49cfea5b7)


### Data Processing

- 결측치 80% 이상 컬럼 삭제 (작곡가, 프로듀서 등)
- 기타 결측치 보간 실시
- 개봉 영화 기준
- 영미/한국 기준 영화 

## 4. Modeling


### Modeling Process

- 1) 영화 메타데이터 기준
     - 수익> 투표수 순으로 흥행 기준 영화 추천
  2) 협업 필터링 - 사용자 기반
     - cosine 유사도 파악 :사용자별
     - 유사한 사용자끼리 , 시청하지 않은 영화추천
     

## 5. Result
![image](https://github.com/user-attachments/assets/d1327e43-f1f0-47f1-a3e7-2b41ddc83a1e)



### Presentation



- _Insert related reference_
