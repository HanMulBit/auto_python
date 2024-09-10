---
marp: true
title: 제목
description: 헬스케어 데이터의 품질 향상을 위한 전처리 과정
style: |
    .columns {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 1rem;    
    }
header: PPT 상단에 공통으로 들어가는 내용
footer: PPT 하단에 공통으로 들어가는 내용
paginate: true
theme: uncover
# theme: gaia / default(기본) / uncover
# + class:invert
class: invert
---

# 헬스케어 데이터 전처리

- 데이터 품질 향상
- 일관성 유지
- 분석용 데이터 준비

---

## 데이터 품질 향상 목표

1. **정확성**: 데이터 오류 수정
2. **일관성**: 서로 다른 소스의 데이터 통합
3. **완전성**: 누락된 데이터 채우기

---

## 데이터 전처리 과정

### 1. 데이터 수집
- 개인별 간단한 데이터 입력
- 음식 사진 및 Kcal 정보

---

### 2. 데이터 클렌징
- 이상치 제거 및 변환
- 중복 데이터 처리

```python
import pandas as pd

# 중복 데이터 제거 예시
df.drop_duplicates(inplace=True)

```

---

## 표 형식 슬라이드

| 단계        | 설명                         |
| ----------- | ---------------------------- |
| 데이터 수집 | 개인별 입력 및 사진 데이터   |
| 데이터 클렌징 | 이상치 및 결측치 처리        |
| 데이터 변환 | 데이터 형식 및 단위 통일      |
| 데이터 분석 | 머신러닝 모델을 위한 데이터 |

---

## 이미지 슬라이드 1

![bg right height:400px](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI0WMc2zTnXQZyti1XoP_8sSQ-t7P-phhz6Q&s)

---

## 이미지 슬라이드 2

![bg left](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI0WMc2zTnXQZyti1XoP_8sSQ-t7P-phhz6Q&s)

---

## Grid

<div class="columns">
<div>

## 왼쪽 리스트
1
2
3
</div>
<div>

## 오른쪽 리스트
4
5
6
</div>
</div>

---

# <!--fit--> 이모지 사용 :rocket: :smile:

# <span style="color:grey">span태그 스타일</span> 텍스트