# Deep-Generative-Models-Practice
# [Project] Deep Generative Models Practice

다양한 딥러닝 생성 모델(VAE, GAN, Diffusion)의 구조를 이해하고, PyTorch를 활용하여 직접 구현 및 학습시킨 연습 기록입니다.

## 🚀 구현 모델 목록

### 1. Variational AutoEncoder (VAE)
* **특징:** Latent Space의 확률 분포를 학습하여 데이터를 생성. 
* **핵심 학습:** Reconstruction Loss와 KL Divergence의 균형 최적화.

### 2. Generative Adversarial Networks (GAN)
* **특징:** Generator와 Discriminator의 적대적 학습을 통한 고해상도 이미지 생성. 
* **핵심 학습:** Mode Collapse 방지 및 안정적인 학습을 위한 파라미터 튜닝.

### 3. Diffusion Models
* **특징:** 데이터에 노이즈를 추가하는 과정(Forward)과 이를 복원하는 과정(Reverse)을 학습. 
* **핵심 학습:** Denoising Score-matching 기반의 고품질 데이터 생성 원리 이해.

## 🛠 Tech Stack
* **Language:** Python
* **Framework:** PyTorch
* **Library:** Torchvision, Matplotlib, NumPy
