# 제2회 코스포 x 데이콘 도서 추천 알고리즘 AI경진대회
---
# 결과
---
### 요약 정보
* 도전기관 : 시큐레이어
* 도전자 : 석민재
* 최종 스코어 : (public) 3.2581
* 제출 일자 : 2023-07-04
* 총 참여 팀수 : 709
* 순위 및 비율 : 3 (1.69%)

# 결과 화면
---
<img width="500" alt="캡처" src="https://github.com/Jsonseok/SecuLayer/assets/112038669/59361f1e-9547-48c2-9abc-dce31166a394">

# 사용한 방법 & 알고리즘
---
* 범주형 변수들을 cat_features에 추가
* optuna를 통해 best 파라미터 설정
* K-fold(n_split=20) 사용 / 최종 score = 각 fold의 평균

# 코드
---
[jupyter notebook code](main.ipynb)

# 참고자료
---
##### https://dacon.io/competitions/official/236093/codeshare/8389?page=1&dtype=recent
