# 🐍 Python Basics  

## 📖 개요 (Overview)  
이 리포지토리는 **파이썬 기초 학습을 위한 자료**를 정리한 공간입니다.  
**Google Colab / Jupyter Notebook** 환경에서 활용할 수 있는 **예제 코드 & 실습 자료**를 포함하고 있습니다.  

초보자도 쉽게 따라올 수 있도록 기초 개념부터 단계적으로 학습할 수 있으며, 실습을 통해 프로그래밍 역량을 키울 수 있습니다.  

## 📌 학습 목차 (Table of Contents)  

1. **Notebook 사용법** 📓  
   - Jupyter Notebook 및 Google Colab 사용 방법  
   - 셀 실행, 코드 작성, Markdown 활용  

2. **파이썬 변수와 자료형** 🔢  
   - 변수 선언과 사용법  
   - 숫자형 (int, float, complex)  
   - 논리형 (bool)  

3. **파이썬 문자열 다루기** 🔡  
   - 문자열 인덱싱과 슬라이싱  
   - 문자열 메서드 (`replace()`, `split()`, `join()` 등)  

4. **컬렉션 데이터 타입** 📂  
   - 리스트 (`list`)  
   - 튜플 (`tuple`)  
   - 딕셔너리 (`dict`)  
   - 집합 (`set`)  

5. **연산자 (Operators)** ➕  
   - 산술 연산자 (`+`, `-`, `*`, `/`)  
   - 비교 연산자 (`==`, `!=`, `>`, `<`)  
   - 논리 연산자 (`and`, `or`, `not`)  
   - 비트 연산자 및 멤버십 연산자  

6. **조건문과 반복문 (Condition & Loop)** 🔄  
   - `if-elif-else` 조건문  
   - `for` / `while` 반복문  
   - 리스트 컴프리헨션 활용  

7. **함수 (Functions)** 🎯  
   - 함수 정의 및 호출  
   - 매개변수와 반환값  
   - 람다 함수 (`lambda`)  

8. **클래스 (Object-Oriented Programming)** 🏗  
   - 클래스와 객체 생성  
   - 생성자 (`__init__`)와 인스턴스 메서드  
   - 상속과 다형성  

9. **모듈과 패키지 (Modules & Packages)** 📦  
   - 모듈 불러오기 (`import`)  
   - 표준 라이브러리 활용 (`math`, `datetime` 등)  
   - 패키지 구조와 활용  

10. **예외 처리 (Exception Handling)** ⚠  
   - `try-except` 블록 활용  
   - `finally`와 `raise`  

11. **정규식 (Regular Expressions)** 🔍

정규식은 문자열에서 특정 패턴을 검색하거나 조작할 때 사용하는 강력한 도구입니다. 파이썬에서는 `re` 모듈을 사용하여 정규식을 다룰 수 있습니다.

**주요 함수**
- `re.match()` : 문자열의 시작에서 정규식과 일치하는지 확인
- `re.search()` : 문자열에서 첫 번째로 일치하는 부분을 찾음
- `re.findall()` : 일치하는 모든 부분을 리스트로 반환
- `re.sub()` : 문자열에서 정규식과 일치하는 부분을 다른 문자열로 교체

**정규식 기본 문법**
- `.` : 임의의 문자
- `\d` : 숫자 (0-9)
- `\w` : 알파벳이나 숫자
- `\s` : 공백 문자
- `*`, `+`, `?` : 반복 횟수 지정

**정규식 예제**
```python
import re

# 이메일 추출
text = "문의사항은 contact@example.com 또는 info@domain.com으로 보내주세요."
emails = re.findall(r"\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}\b", text)
print(emails)  # ['contact@example.com', 'info@domain.com']

## 🛠 환경 설정 (Setup)  

### 📌 필수 환경  
- **Python 3.x** ([다운로드](https://www.python.org/downloads/))  
- **Jupyter Notebook** 또는 **Google Colab**  
- 추가 패키지 설치 (필요시)  
  ```bash
  pip install numpy pandas matplotlib
