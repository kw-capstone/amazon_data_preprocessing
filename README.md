# 기존 데이터에서 필요없는 데이터 삭제


### 데이터 정보
* json파일, 476483 rows × 20 columns / 1.8G
* 전처리 후 : csv파일, 219788 rows × 16 columns / 0.7G


### 각 columns별 missing data 비율

*  category - 0.0%
*  tech1 - 98.4%
*  description - 0.0%
*  fit - 92.7%
*  title - 0.0%
*  also_buy - 0.0%
*  tech2 - 100.0%
*  brand - 12.0%
*  feature - 0.0%
*  rank - 0.0%
*  also_view - 0.0%
*  main_cat - 0.3%
*  similar_item - 97.5%
*  date - 84.6%
*  price - 53.9%
*  asin - 0.0%
*  imageURL - 0.0%
*  imageURLHighRes - 0.0%
*  details - 0.0%
  

### Nan 값이 대부분인 필요없는 columns 삭제
1. tech1
2. fit
3. tech2
4. similar_item
5. date


### 카테고리 분류
카테고리를 분류하려고 했으나, 카테고리의 수가 너무 많아 아직 진행하지 않았으며, 어떻게 할지 생각해봐야 할 부분

