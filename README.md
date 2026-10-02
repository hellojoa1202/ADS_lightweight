<p><sub>ADS_lightweight</sub></p>

<p><sub>TAVE 14기 자율주행 프로젝트를 바탕으로 차선 인식과 객체 인식 모델을 경량화하고, 임베디드 환경에서 정확도와 추론 성능을 비교한 2025 한이음 ICT 멘토링 프로젝트입니다.</sub></p>

<p><sub>구조 및 포함 내용</sub></p>

<ul>
  <li><sub><code>PilotNet/</code>: PilotNet 학습 모델, 정확도·F1 지표, 모델 크기와 추론 시간 기록</sub></li>
  <li><sub><code>YOLO/</code>: YOLOv5 기반 객체 인식 노트북과 모델 파일</sub></li>
  <li><sub><code>efficentDet-lite0/</code>: EfficientDet-Lite0 pruning 실험 노트북, 설정 파일, pruning 모델과 양자화된 TFLite 모델</sub></li>
  <li><sub><code>UFLD</code>, <code>src/</code>: 차선 인식 모델 실험 코드와 UNet·SCNN·UFLD 관련 결과</sub></li>
  <li><sub><code>trafficlight/</code>: 신호등 인식 실험 노트북</sub></li>
  <li><sub><code>data/</code>: 원본·가공 차선 데이터와 객체 인식 학습용 라벨</sub></li>
  <li><sub><code>reference/</code>: 참고용 차량 제어 코드</sub></li>
  <li><sub><code>q-dr8</code>, <code>q-fp16</code>: 양자화 실험 결과 파일</sub></li>
</ul>

<p><sub>폴더별로 모델 학습·경량화·양자화·임베디드 적용에 필요한 코드와 결과 파일을 구분해 보관하고 있습니다.</sub></p>