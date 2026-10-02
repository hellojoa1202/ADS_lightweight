<p><sub>ADS_lightweight</sub></p>

<p><sub>분야: 자율주행 · 차선 인식 · 객체 인식 · 모델 경량화</sub></p>
<p><sub>기간: 2025 한이음 ICT 멘토링</sub></p>

<p><sub>구조</sub></p>

<pre><code>ADS_lightweight/
├── PilotNet/           # PilotNet 모델·평가 지표
├── YOLO/               # 객체 인식 모델
├── efficientDet-lite0/ # pruning·quantization
├── src/                # 차선 인식 실험 코드
├── data/               # 차선·객체 인식 데이터
├── trafficlight/       # 신호등 인식
├── reference/          # 참고 코드
└── results/
    └── quantization/   # q-dr8 · q-fp16</code></pre>

<p><sub>모델: PilotNet · YOLOv5 · EfficientDet-Lite0 · UFLD</sub></p>
<p><sub>실험: pruning · quantization · 정확도 비교 · 추론 시간 비교</sub></p>