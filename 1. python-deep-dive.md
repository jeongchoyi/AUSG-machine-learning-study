# 파이썬 딥다이브하기 :octocat:

## 파이썬?
귀도 반 로섬....^- ^ 생략 생략

## Zen of Python

```
Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one—and preferably only one—obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than right now.[n 1]
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea—let's do more of those!
```

## 파이썬의 특징
- 가독성
	- 코드의 블럭을 들여쓰기로 구분하여 문장이 깔끔함
- 문법이 간결하고 표현 구조가 인간의 사고 체계와 비슷함
	- 초보자가 배우기 쉬움
	- 유지 보수, 관리가 쉬움
	- 같은 내용을 구현할 때 비교적 코드 줄 수가 적음
- 독립적 플랫폼
	- 다양한 플랫폼에서 사용 가능
- 내/외부에 프레임워크, 라이브러리가 풍부함
	- 다양한 용도로 확장하기 좋음
	- 리눅스의 경우 pip를 사용하여 라이브러리를 설치함
- 생산성이 높음
- 다양한 분야에 사용 중
	- 데이터 분석, 머신러닝, 그래픽, 학술 연구 등
-  인터프리터 언어(동적 언어), 연산 속도가 C에 비해 30~70배 까지 떨어짐
	- CPU 발달로 해결이 되는 중
	- 접착성이 좋아서 C로 구현된 모듈을 쉽게 붙일 수 있음,
	  C로 구현하여 해결하거나 반대의 경우도 가능


## 파이썬의 기술
- 행렬 연산을 잘 해주기 위한 플랫폼
	- 넘피(Numpy), 사이파이(Scipy), 판다스(pandas) 등의 솔루션
- 텐서플로우
	- low level 머신러닝 언어
	- 빠름
- scikit-learn : 독보적인 파이썬 머신러닝 라이브러리
	- 자유로운 사용과 배포
	- 활발한 커뮤니티
	- 풍부한 documantation
	- 많은 튜토리얼, 예제 코드
	- 다른 파이썬의 과학 패키지와 연동
	- Numpy, Scipy 사용
- matplotlib : 그래프 그리기
- IPython, 주피터 노트북 : 대화식 개발

## 파이썬 배포판
- Anaconda
	- Numpy, Scipy, matplotlib, pandas, IPython, Jupyter Notebook, scikit-learn 포함
	- macOS, 윈도우, 리눅스 지원
	- 파이썬 과학 패키지가 없는 사람에게 추천
	- 바이너리 의존성 등의 문제 해결 위해 자체적인 패키징 매커니즘 가짐
	- 상용 라이브러리인 인텔 MKL 라이브러리도 포함
		- scikit-learn의 여러 알고리즘이 훨씬 빠르게 동작
- Enthought Canopy
	- 파이썬 2.7.x
- Python(x,y)
	- 윈도우 환경
 
- 파이썬을 이미 설치했다면
```python
pip install numpy scipy matplotlab ipython scikit-learn pandas pillow
```

## 파이썬이 ML에 선호되는 이유
- 범용 프로그래밍 언어의 장점
	- GUI나 웹 서비스 제작 가능
	- 기존 시스템과 통합 용이
- 매트랩*MATLAB*과 R 같은 특정 분야를 위한 스크립팅 언어의 편리함
- 데이터 적재, 시각화, 통계, 자연어 처리, 이미지 처리 등에 필요한 라이브러리
- 터미널 / 주피터 노트북*Jupyter Notebook* 같은 도구로 대화하듯 프로그래밍
- 반복 작업을 빠르게 처리하고 손쉽게 조작할 수 있음
- 메모리를 대신 관리함
