 
**overriding**
-부모,자식 클래스가 같은 이름의 메서드를 가지고 있을 때, 부모클래스가 가지고 있는 메서드를 자식클래스에서 변경하여 실행시키는 방법.  
-결과적으로, 부모클래스가 가지고 있는 기본적인 기능을 자식클래스에서 필요에 따라 변경 가능하다.
-자식클래스에서 부모클래스의 메서드를 호출하기 위해서는 자식클래스에 super라는 것을 사용해야 한다. EX)return super.메서드();  
-overriding을 하기 위해선 메서드의 이름, 리턴 타입, 매개변수의 타입, 순서, 개수가 같아야 한다.(메서드의 서명=시그니쳐)  

**overloading**  
-같은이름의 메서드여도 서로 다른 매개변수를 가지고 있게 정의할 수 있는 방법.  
-단, 리턴타입이 다르면 안된다. EX)(void A = void A) -> O // (void A = int A) -> X  
-매개변수의 이름도 같아야 하나?  

**컴파일**  
-window+R -> cmd -> 경로이동 -> javac 컴파일할 자바파일이름.  

**패키지 import**  
Inheritance = 패키지 이름  
Calculator2 = Inheritance패키지에 속한 클래스중 하나.  

import Inheritance.*; //패키지의 모든 클래스를 가져올 때?   
import Inheritance.Calculator2; //패키지 내의 가져오고 싶은 클래스만.  
