# BrainFuckEx
The Extension of BrainFuck, X.

##What's new
BrainFuck 은 1차원 배열을 이용하나, 이 언어는 두개의 포인터로 2차원 배열을 사용합니다.
BrainFuck 으로 쓰여진 코드도 컴파일 가능하며, 새로운 기능이 4가지 있습니다.

BrainFuck uses 1 dimensional Array, But this lang uses 2 dimensional Array by two pointers.
It can compile pure BrainFuck codes, and there's are 4 new keywords.

^, v : 수직포인터를 조종합니다. >< 와 사용례가 같습니다.
       Controll the horizontal pointer. Same usage with ><.

'*' : 수평포인터가 가르키는 값, 즉 (v,0) 과 수직포인터가 가르키는 값 (0,h) 의 곱을 (v,h) 에 더합니다.
    Add product of two values which pointed by vertical pointer and horizontal pointer, at (v,h)

= : 프로그램을 끝냅니다.
    Terminate the program.
