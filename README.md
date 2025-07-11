# 20250711_sicikit_learn

## **정리 출처**
- 교수님 ppt [scikit_learn_intro.pptx](./scikit_learn_intro.pptx)

## 1️⃣ 머신러닝 & 데이터 분석
### 머신러닝 기본 개념
- "Machine learning (ML) is a type of artificial intelligence that allows machines to learn from data without being explicitly programmed."
- 머신러닝은 인공지능 (AI)의 한 분야로, 사람이 직접 프로그래밍 하지 않고 컴퓨터가 데이터를 입력으로 스스로 학습하는 기술이다 
- ISO – Machine learning overview

- "The study of computer programs that improve automatically through experience."
- 머신러닝은 컴퓨터 프로그램이 경험을 통해 자동으로 성능을 개선하도록 하는 연구 분야이다 
- Stanford University’s “Introduction to Machine Learning” by Nils J. Nilsson 

<img width="902" height="508" alt="스크린샷 2025-07-11 11 57 42" src="https://github.com/user-attachments/assets/674e216a-fbbe-4484-96af-d47bedfc86b6" />

<img width="807" height="373" alt="image" src="https://github.com/user-attachments/assets/c3b5cacb-0a38-45f8-a5b1-462257f85b0e" />

**머신러닝 워크플로우 단계별 상세**
1. 데이터 수집: 데이터 소스로부너 학습에 필요한 데이터 확보(라벨링 포함)
2. 데이터 전처리 및 변환: 데이터를 학습에 적합한 형태로 변환
3. 모델 학습: 알고리즘 수행 및 모델 학습, 데이터의 숨겨진 패턴 파악
4. 모델 평가: 학습된 모델의 예측 성능 평가
5. 성능 개선: 모델 최적화를 통한 성능 향상

- **지도 학습**(Supervised learning): 라벨이 매겨진 데이터 (labeled datasets)를 학습하여 주어진 데이터를 분류하거나 결과를 예측
- **비지도 학습**(Unsupervised learning): 라벨이 없는 데이터 (unlablled datasets)를 학습하여  데이터에 숨겨진 패턴이나 구조를 발견
- **강화 학습**(Reinforcement learning): 라벨이 없는 데이터 학습 -> 출력에  대한 평가를  피드백으로 활용 ->  추론 성능 점진적 향상

**Machine learning models**
- 알고리즘을 이용한 학습의  최종 결과물 
- 주어진 데이터로부터 결과를 예측하고 패턴을 식별하기 위한 도구 
 **Machine learning algorithms**
- ML model을 도출하기 위한 기법 
- 공통 목표: 모델 예측 성능 향상
  
<img width="307" height="212" alt="스크린샷 2025-07-11 13 56 03" src="https://github.com/user-attachments/assets/4894230b-ab89-46c8-8e16-ffdfce25f4fb" />

**Under-and overfitting**
- Fitting: 모델이 학습하는 과정
- Underfitting: 모델이 지나치게 단순하여 데이터에 내재된 패턴을 파악하지 못하는 현상 
- Overfitting: 모델이 지나치게 복잡하여 학습 데이터는 잘 예측하나 새로운 데이터가 입력되면 낮은 성능을 보이는 현상

<img width="409" height="274" alt="image" src="https://github.com/user-attachments/assets/61bc237d-d7a9-4ce2-b694-8ee6742065c7" />

**Advantages of ML-based data analysis**
- 대규모 & 다차원 데이터 처리에 유리함 
- 데이터가 쌓일 수록, 학습이 진행될수록 모델 성능 향상
- 데이터에 숨겨진 패턴 발견에 유리함 

**머신러닝(ML) 프로세스 용어 정리**

<img width="745" height="398" alt="스크린샷 2025-07-11 14 08 17" src="https://github.com/user-attachments/assets/f3914270-017f-4a75-9af3-d44978dd43e1" />


