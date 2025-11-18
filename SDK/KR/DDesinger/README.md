### **DDesigner API Guide**

PyTorch(`model.pth` / `model.pt`) 또는  
TensorFlow(`model.h5` / `saved_model.pb`)로 학습된 모델을  
**DDesigner API**를 통해 디퍼아이 하드웨어 전용 파라미터로  
변환하는 전체 과정을 설명합니다.

주요 기능:
- 학습된 모델 구조 파싱  
- 디퍼아이 전용 실행 파라미터 생성  
- 하드웨어 맞춤 최적화  
