
## 투명도 관련 속성들

**opacity**

- 사용도: ⭐⭐⭐⭐⭐ (매우 높음)
- 중요도: 필수급
- 주요 상황: 호버 효과, 모달 배경, 로딩 상태 표시
- 특징: 요소 전체(텍스트 포함)가 투명해짐

**rgba()**

- 사용도: ⭐⭐⭐⭐⭐ (매우 높음)
- 중요도: 필수급
- 주요 상황: 배경색만 투명하게 하고 싶을 때, 오버레이 효과
- 특징: 색상만 투명하게, 텍스트는 선명하게 유지


```css
/* 실무 예시 */ 
.modal-overlay { 
	background: rgba(0, 0, 0, 0.7); /* 검은 반투명 오버레이 */ 
	} 
	
.glass-effect { 
	background: rgba(255, 255, 255, 0.2); 
	backdrop-filter: blur(10px); /* 유리창 효과 */ 
	}
```


## 그라데이션 (Gradient)

**linear-gradient**

- 사용도: ⭐⭐⭐⭐ (높음)
- 중요도: 중요
- 주요 상황: 버튼 디자인, 배경 장식, 브랜드 컬러 표현

```css
/* 최신 문법 (웹킷 접두사 필요 없음) */ 
background: linear-gradient( 
	to bottom, /* 방향 */ 
	#bfd255 0%, 
	#8eb92a 50%, 
	#72aa00 51%, 
	#9ecb2d 100% 
	); 
	
/* 다양한 방향 */ 
background: linear-gradient(45deg, red, blue); 
background: linear-gradient(to right, red, blue);
```

