# 모션 키포인트 검출 AI 경진대회
---
# 결과
---
### 요약 정보
* 도전기관 : 시큐레이어
* 도전자 : 석민재
* 최종 스코어 : 16.80
* 제출 일자 : 2023-07-10
* 총 참여 팀수 : 156
* 순위 및 비율 : 20 (12.82%)

# 결과 화면
---
<img width="800" alt="1" src="https://github.com/Jsonseok/SecuLayer/assets/112038669/aa8bad23-d293-4d6f-8bbd-f93940420be3">
<img width="800" alt="2" src="https://github.com/Jsonseok/SecuLayer/assets/112038669/6acb9830-39de-49e3-b334-82130b1f255e">

# 사용한 방법 & 알고리즘
---
* Pretrain된 Pose HR-Net 모델 사용
* Normalization, warpAffine 전처리 사용
* Staking Ensemble 사용

# 코드
---
[jupyter notebook code](main.ipynb)

# 참고자료
---
##### https://arxiv.org/pdf/1905.11946.pdf
##### https://github.com/leoxiaobin/deep-high-resolution-net.pytorch
