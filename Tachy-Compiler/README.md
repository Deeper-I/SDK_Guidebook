### **Tachy Compile Guide**

Tachy Compile은 Training 단계에서 회신받은 최적화된 모델을  
ONNX 형식으로 변환하고, 이후 디퍼아이 전용 확장 파일인 **`.tachyrt`** 포맷으로  
변환하는 역할을 수행하는 도구입니다.

주요 기능:
- 모델 최적화 결과를 기반으로 변환  
- ONNX → `.tachyrt` 포맷 변환  
- 하드웨어 실행용 런타임 파일 생성  
