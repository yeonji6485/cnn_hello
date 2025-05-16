# 🧠 감정 인식 CNN 실험 (cnn_hello)

이 프로젝트는 CNN 기반으로 얼굴 이미지의 감정을 인식하는 실험 시리즈입니다.  
ResNet, VGG 등의 다양한 모델 구조를 적용하고, 이미지 전처리 및 하이퍼파라미터 조정을 통해 성능 개선을 시도했습니다.

---

## 📁 폴더 구조

```
cnn_hello/
└── notebooks/
    ├── vgg_experiment.ipynb         # VGG 기반 baseline 실험
    ├── resnet50_base.ipynb          # 기본 ResNet50 학습 실험
    ├── scaling_resnet.ipynb         # 이미지 스케일 조정 실험
    └── resnet_finetune.ipynb        # Dropout, Epoch, Batch size 튜닝 실험
```

---

## 📌 주요 실험 요약

| 실험명 | 주요 내용 |
|--------|-----------|
| `vgg_experiment` | VGG16 구조로 감정 분류 baseline 성능 측정 |
| `resnet50_base` | 사전 학습된 ResNet50 모델로 기본 실험 수행 |
| `scaling_resnet` | 이미지 해상도 및 비율 변화에 따른 성능 영향 측정 |
| `resnet_finetune` | Dropout, Batch size 등 하이퍼파라미터 튜닝 실험 |

---

## 📈 향후 개선 아이디어

- 클래스 불균형 개선을 위한 데이터 재가공
- 위험 감정 상태 threshold 기반 알림 시스템 설계
- 챗봇 연동 구조 확장 (GPT 기반 감정 반응 유도)

---
