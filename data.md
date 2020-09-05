JAVA 노트

*데이터의 크기  
8bit -> 1byte ->
1024byte -> kilobyte
1024kilobyte -> 1megabyte 
1024megabyte -> 1gigabyte 
1024gigabyte -> 1terabyte 
1024terabyte -> 1petabyte 
1024petabyte -> 1exabyte 
1024exabyte-> 1zettabyte
1024zettabyte -> 1yibbyte

///////////////////////////////////////////  

*데이터타입 (경우에 따라 필요한 데이터 타입을 사용하면 된다.)   
1.정수형 데이터타입   
byte(1byte) = -128 ~ 127

short(2byte) = -32,768 ~ 32,767

int(4byte) =  -2,147,483,648~2,147,483,647 (가장 처리 속도가 빠르고 충분한 수를 표현 가능하기에 int를 주로 쓴다.)

long(8byte) = -9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807  
  
2.실수형 데이터타입  
float(4byte) = ±(1.40129846432481707e-45 ~ 3.40282346638528860e+38)  

double(8byte) = ±(4.94065645841246544e-324d ~ 1.79769313486231570e+308d) 

3.문자 데이터타입  
char(2byte) = 모든 유니코드 문자

*형변환  
-표현범위가 좁은 데이터 타입에서 표현범위가 넓은 데이터 타입으로만 형변환이 가능하다.  
EX) byte -> short,int,double....

