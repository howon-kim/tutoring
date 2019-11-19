# Sorting lll 

## 퀵소트와 합병소트의 비교
- 퀵소트는 기본적으로 분할 (partitioning)
- 
## 퀵소트의 선택
1. **랜덤화**: 무작위로 피벗을 선택하거나 정렬전 배열을 무작위로 섞는다.
2. **중간값**: Median 값을 피벗값으로 선택
	- 증간값을 사용하였을때 최악의 경우는 $\theta$ (N log N) 이지만 합병소트 (Mergesort) 보다 느리다.
3. **재귀단계제한**: 만일 재귀호출이 일정값 이상으로 호출될 때, 분류 중단
	- 만일 특정 값 (10) 이상으로 재귀 호출될때, 합병소트 사용.

## 안정성, 최적화, 그리고  adaptiveness

## 랜덤화
