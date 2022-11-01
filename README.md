# rottoProgram_python
단순한 로또 번호를 랜덤으로 출력하는 프로그램
기본형식과 함수를 만들어 출력하는 두가지 버전의 소스코드

[ 기본형식 ]
1) random 모듈을 import
2) 변수 list에 빈 리스트를 선언함
3) for문을 통해 6번의 숫자를 뽑음
4) random.randrange(1,46)을 변수 넘에 넣음 --> 로또 번호는 1~45
5) if문을 이용해 중복없는 반복을 시행
6) 만약 랜덤으로 돌린 num이 list에 있다면 다시 랜덤을 돌림
7) list에 num값을 append
8) list안에있는 로또 번호 출력

[ 함수를 이용한 형식 ]
1) random 모듈을 import
2) def random_num(): 함수 선언, 매개변수는 없음
3) 변수 list에 빈 리스트를 선언함
4) for문을 통해 6번의 숫자를 뽑음
5) random.randrange(1,46)을 변수 넘에 넣음 --> 로또 번호는 1~45
6) if문을 이용해 중복없는 반복을 시행
7) 만약 랜덤으로 돌린 num이 list에 있다면 다시 랜덤을 돌림
8) return list를 해주어서 값을 리턴
9) a 변수에 함수 random_num()을 호출한 값을 넣음
10) print로 로또 번호 a를 출력

# Sorce Code
[ 기본형식 ]

![image](https://user-images.githubusercontent.com/70150896/199138676-38609efe-1a8e-491e-81a2-7c6ba0b3e6e1.png)

[ 함수를 이용한 형식 ]

![image](https://user-images.githubusercontent.com/70150896/199138774-b5646ce2-f139-4e58-bd2c-de779a02db51.png)
