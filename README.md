# python


## 자료형
#### 숫자형
* 정수 : 123, -20 ,0  
* 실수:  123.45 , -432.55 , 6.08e9  
* 8진수: 0o456, 0o123  
* 16진수: 0xFF, 0x0D, 0x0A

```
a = 10
b = 20
c = a + b
d = b - a
print(c,d,)
```

### 문자열
1. 큰 따옴표 : "Hello World! it\'s"  
2. 작은 따옴표 : '대한민국'  
3. 큰 따옴표 3개 : """Hello!"""  
4. 작은 따옴표 3개 : 
'''Life is too short.
You need python'''

### 변수  
* 문자 또는 밑줄로 시작( beta, _kim )
* 대소문자를 구분. (sum,Sum,SUM)
* 영문자,숫자,밑줄(A-z,0-9,_)  
* 파이썬 키워드는 사용 불가

```
myName = "Juno Min"   # 카멜 표기법 : 낙타혹처럼 중간 대문자 사용
my_Name = "민준호"   #스네이크 표기법 : _가들어감
MyName = "min"    #파스칼 표기법 : 대문자가 듬섬듬섬
_my_Name = "korea"
MYNAME = "Min"
my2name = "12345"
# 2myname = 
# my-name = 
# my name =     안되는 변수들 : 숫자가 앞에 나오는 변수,-가 들어가는 변수,띄어쓰기가 들어가는 변수
myStr = '123' # 123이라는 글자로 지정
myNum = 123 # int 숫자로 지정

print(myStr , myNum)
print(type(myStr))
print(type(myNum))
```
여러개 변수 할당

```
x,y,z = "포도","딸기","수박"
print(x)
print(y)
print(z)

```
a=b=c="오렌지"
print(a)
print(b)
print(c)
```
fruits = ["포도","딸기","수박"]
x,y,z = fruits
print(x)
print(y)
print(z)
```
x = "Life"
y = "is"
z = "Beautiful"
print(x,y,z)
print(x+y+z)  # 띄어쓰기 유무의 차이점이 있다.
```
a = 1
b = 2
c = 3
print(a,b,c)
print(a+b+c)     # 숫자는 위 텍스트와 출력이 다르다는걸 알수있음.
```
### 데이터 유형  
+ 텍스트  
+ 숫자   
+ 불(bool)  

```
a = 100
b = 200
sum = a + b
min = b - a
div = b/a
print(a,'+', b , '=',sum )
print(b,'-', a , '=',min)
print(b, '/', a, '=',div)   # 보여지는 연산과정을 출력하고싶을때
```



