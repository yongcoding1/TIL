# 제어문
___
다중 반복문 한 번에 탈출 : break + Label 문법 이용
> 예시
```java
out:
for (int i=0; i<10; i++) {
	for(int j=0; j<10; j++) {
	  if(j==3)
		break out;
	System.out.println(i + "," + j);
	 }
}
```
