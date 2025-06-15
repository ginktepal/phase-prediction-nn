# 3-Layer 인공신경망 기반 상변화 예측

이 프로젝트는 타이타늄 합금의 조성 데이터를 이용하여 고상/액상/다상을 분류하는 분류 문제를 PyTorch 기반 인공신경망 모델로 해결하는 실습입니다.

## 📁 구성
- `notebooks/phase_nn_classification.ipynb`: PyTorch 기반 3-layer NN 구현 노트북
- 데이터는 기존 GitHub 저장소의 CSV 파일을 URL로 불러옵니다.

## ⚙️ 주요 기술
- PyTorch
- 신경망 구성: 입력층 → 은닉층1 → 은닉층2 → 출력층
- CrossEntropyLoss + Adam Optimizer
- 성능 평가: classification_report

## ✅ 실행 방법
1. 노트북을 Colab 또는 Jupyter에서 실행
2. 조성 데이터를 불러와 전처리
3. 모델 학습 및 성능 평가
