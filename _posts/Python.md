# 🌱파이썬 기초
### 📌변수
- 정수는 int
- 실수는 float
### 📌 문자열
- ✅ 문자열 인덱싱
1. 마지막 인덱스 번호는 "-1"
2. 첫 번째 인덱스 번호는 "0"으로 시작
- ✅ 슬라이싱
1. 변수[start:stop:step]
    ##### stop은 출력하고 싶은 문자의 다음 문자의 인덱스 번호
    ##### step은 점프 기능(생략 가능)
- ✅ 문자열 메서드
1. lower() ≫ 문자 전체를 소문자로 변환
2. upper() ≫ 문자 전체를 대문자로 변환
3. find() ≫ 찾지 못 하면 "-1" 출력
    ##### 문자가 시작하는 인덱스 번호를 찾아 그 값을 출력
4. index() ≫ 찾지 못 하면 error뜸
5. count() ≫ 문자 갯수
6. replace() ≫ 문자 교체
7. split() ≫ 문자열 나눔
    ##### 결과 : weniv - corp
```
s3 = "weniv corp"
s4, s5 = s3.split("-")
print(s3)
