# NaEunSoo.github.io
# 파이썬 기초 코딩 학습 샘플

파이썬 초보자를 위한 5개의 학습 샘플 코드입니다. 각 파일은 독립적으로 실행 가능하며, 파이썬의 핵심 개념을 다룹니다.

## 📚 샘플 목록

### 1️⃣ 변수와 데이터 타입 (`01_variables_and_types.py`)
**학습 내용:**
- 문자열 (String)
- 숫자 (Integer, Float)
- 불린 (Boolean)
- 리스트 (List)
- 딕셔너리 (Dictionary)
- 타입 확인 방법

**실행 방법:**
```bash
python 01_variables_and_types.py
```

---

### 2️⃣ 제어문 (`02_control_flow.py`)
**학습 내용:**
- if-elif-else 조건문
- for 반복문 (리스트, range, enumerate)
- while 반복문
- break와 continue
- 중첩 반복문 (구구단 예제)

**실행 방법:**
```bash
python 02_control_flow.py
```

---

### 3️⃣ 함수 (`03_functions.py`)
**학습 내용:**
- 기본 함수 정의
- 매개변수와 반환값
- 기본 매개변수 값
- 여러 값 반환
- 가변 인자 (*args, **kwargs)
- 실용적인 계산기 함수 예제

**실행 방법:**
```bash
python 03_functions.py
```

---

### 4️⃣ 리스트 연산 (`04_list_operations.py`)
**학습 내용:**
- 리스트 생성
- 요소 추가 (append, insert, extend)
- 요소 제거 (remove, pop)
- 정렬 (sort, sorted)
- 슬라이싱
- 유용한 메서드 (count, index, len, max, min, sum)
- 리스트 컴프리헨션
- 리스트 복사

**실행 방법:**
```bash
python 04_list_operations.py
```

---

### 5️⃣ 파일 처리와 예외 처리 (`05_file_and_exception.py`)
**학습 내용:**
- 파일 쓰기, 읽기, 추가
- 파일 한 줄씩 읽기
- 리스트와 파일 간 변환
- try-except 예외 처리
- try-except-else-finally 완전한 형태
- 실용적인 성적 관리 예제

**실행 방법:**
```bash
python 05_file_and_exception.py
```

**참고:** 이 파일을 실행하면 여러 텍스트 파일이 생성됩니다 (sample.txt, fruits.txt, test_file.txt, scores.txt)

---

## 🚀 시작하기

### 필요 사항
- Python 3.6 이상

### 전체 샘플 순서대로 실행하기
```bash
python 01_variables_and_types.py
python 02_control_flow.py
python 03_functions.py
python 04_list_operations.py
python 05_file_and_exception.py
```

## 💡 학습 팁

1. **순서대로 학습하세요**: 샘플은 난이도 순으로 구성되어 있습니다.
2. **코드를 직접 수정해보세요**: 값을 변경하거나 새로운 예제를 추가해보세요.
3. **주석을 읽으세요**: 각 코드에는 상세한 한글 주석이 포함되어 있습니다.
4. **에러를 두려워하지 마세요**: 에러 메시지를 읽고 이해하는 것도 중요한 학습입니다.
5. **실습하세요**: 배운 내용을 조합하여 자신만의 프로그램을 만들어보세요.

## 📖 추가 학습 자료

각 샘플을 완료한 후 다음 주제들을 학습하면 좋습니다:
- 클래스와 객체 지향 프로그래밍 (OOP)
- 모듈과 패키지
- 정규표현식
- 데이터베이스 연동
- 웹 크롤링
- 데이터 분석 (pandas, numpy)

---

**Happy Coding! 🐍**


# 🏫 공업고등학교 2학년 전자회로 성적 관리 프로그램

공업고등학교 2학년 전자회로 과목의 성적 데이터를 생성하고 관리하는 프로그램입니다.

## 📊 성적 구성

### 평가 비율
- **기말고사**: 60%
- **수행평가 1**: 13.33%
- **수행평가 2**: 13.33%
- **수행평가 3**: 13.33%
- **합계**: 100%

### 학급 구성
- **반 수**: 5개 반 (1반 ~ 5반)
- **학생 수**: 각 반 30명
- **총 학생 수**: 150명

### 등급 기준
| 등급 | 점수 범위 |
|------|-----------|
| A | 90점 이상 |
| B | 80점 이상 ~ 90점 미만 |
| C | 70점 이상 ~ 80점 미만 |
| D | 60점 이상 ~ 70점 미만 |
| F | 60점 미만 |

## 🚀 사용 방법

### 프로그램 실행
```bash
python electronics_grades.py
```

### 주요 기능

#### 1. 성적 데이터 자동 생성
- 정규분포를 따르는 현실적인 점수 생성
- 랜덤 학생 이름 생성
- 자동으로 총점 및 등급 계산

#### 2. CSV 파일 저장
- `electronics_grades.csv` 파일로 자동 저장
- Excel에서 바로 열어볼 수 있음
- UTF-8 BOM 인코딩으로 한글 완벽 지원

#### 3. 통계 정보 제공
- 전체 평균, 최고점, 최저점
- 등급별 분포 및 비율
- 반별 평균 점수

#### 4. 성적표 출력
- 반별 성적표 조회
- 깔끔한 표 형식 출력
- 모든 평가 점수 한눈에 확인

#### 5. 상위 학생 조회
- 전체 학생 중 상위 N명 조회
- 순위, 반, 이름, 총점 표시

## 📋 메뉴 구성

프로그램 실행 후 다음 메뉴를 사용할 수 있습니다:

1. **특정 반 성적표 보기** - 원하는 반의 전체 성적표 출력
2. **전체 통계 보기** - 전체 학생의 통계 정보 확인
3. **상위 학생 보기** - 성적 우수 학생 조회
4. **새로운 데이터 생성** - 새로운 랜덤 성적 데이터 생성
5. **종료** - 프로그램 종료

## 💾 출력 파일

### electronics_grades.csv
생성된 CSV 파일은 다음 컬럼을 포함합니다:

| 컬럼명 | 설명 |
|--------|------|
| 반 | 학급 번호 (1-5) |
| 번호 | 학생 번호 (1-30) |
| 이름 | 학생 이름 |
| 기말고사 | 기말고사 점수 (60%) |
| 수행평가1 | 첫 번째 수행평가 점수 (13.33%) |
| 수행평가2 | 두 번째 수행평가 점수 (13.33%) |
| 수행평가3 | 세 번째 수행평가 점수 (13.33%) |
| 총점 | 가중 평균 총점 |
| 등급 | 성적 등급 (A-F) |

## 📈 데이터 특징

### 점수 분포
- **정규분포** 기반 점수 생성
- 평균과 표준편차를 조정하여 현실적인 분포 구현
- 기말고사는 수행평가보다 약간 어렵게 설정

### 평가별 난이도
- **기말고사**: 평균 72점, 표준편차 15 (가장 어려움)
- **수행평가1**: 평균 78점, 표준편차 10
- **수행평가2**: 평균 75점, 표준편차 12
- **수행평가3**: 평균 80점, 표준편차 11 (가장 쉬움)

## 🔧 코드 구조

### 주요 함수

```python
generate_student_name()           # 랜덤 학생 이름 생성
generate_score()                  # 정규분포 점수 생성
calculate_total_score()           # 총점 계산 (가중 평균)
get_grade()                       # 등급 산출
generate_class_data()             # 한 반 데이터 생성
generate_all_classes()            # 전체 반 데이터 생성
save_to_csv()                     # CSV 파일 저장
print_statistics()                # 통계 정보 출력
print_class_data()                # 반별 성적표 출력
find_top_students()               # 상위 학생 조회
```

## 💡 활용 예시

### 1. 성적 데이터 분석 연습
```python
# CSV 파일을 읽어서 pandas로 분석
import pandas as pd

df = pd.read_csv('electronics_grades.csv', encoding='utf-8-sig')
print(df.describe())  # 기술 통계
print(df.groupby('반')['총점'].mean())  # 반별 평균
```

### 2. 시각화 연습
```python
import matplotlib.pyplot as plt

# 총점 분포 히스토그램
plt.hist(df['총점'], bins=20)
plt.xlabel('총점')
plt.ylabel('학생 수')
plt.title('전자회로 성적 분포')
plt.show()
```

### 3. 엑셀 활용
- CSV 파일을 Excel에서 열기
- 피벗 테이블로 분석
- 차트 및 그래프 생성

## 🎓 학습 목표

이 프로그램을 통해 다음을 학습할 수 있습니다:

1. **파이썬 기초**
   - 함수 정의 및 활용
   - 딕셔너리와 리스트 처리
   - 파일 입출력 (CSV)

2. **데이터 처리**
   - 랜덤 데이터 생성
   - 통계 계산
   - 데이터 정렬 및 필터링

3. **프로그램 설계**
   - 모듈화된 함수 구조
   - 사용자 인터페이스 (메뉴)
   - 에러 처리

## 🔄 커스터마이징

### 반 수 변경
```python
all_students = generate_all_classes(num_classes=3, students_per_class=30)
```

### 학생 수 변경
```python
all_students = generate_all_classes(num_classes=5, students_per_class=25)
```

### 평가 비율 변경
```python
def calculate_total_score(final_exam, perform1, perform2, perform3):
    # 기말 50%, 수행 각 16.67%로 변경
    total = (final_exam * 0.5) + (perform1 * 0.1667) + (perform2 * 0.1667) + (perform3 * 0.1667)
    return round(total, 2)
```

### 난이도 조정
```python
# 기말고사를 더 쉽게
final_exam = generate_score(mean=80, std_dev=10)
```

## 📚 추가 기능 아이디어

1. **성적 향상도 분석** - 수행평가 1, 2, 3의 추이 분석
2. **과락자 관리** - 특정 점수 미만 학생 별도 관리
3. **그래프 출력** - matplotlib으로 시각화
4. **성적 입력 기능** - 실제 점수 수동 입력
5. **출석 연동** - 출석률과 성적 상관관계 분석

---

**Happy Coding! 📊**

