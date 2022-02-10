## 문제 [10172번: 개-Java]
![10172](https://user-images.githubusercontent.com/98507442/153442706-d2f3b98f-0d8a-4434-9647-7766d2c91781.png)
## 풀이

~~~java
public class Main {

	public static void main(String[] args) {
		System.out.println("|\\_/|");
		System.out.println("|q p|   /}");
		System.out.println("( 0 )\"\"\"\\");
		System.out.println("|\"^\"`    |");
		System.out.println("||_/=\\\\__|");

	}

}
~~~

큰 따옴표 ( \" ) 나 백슬래시 ( \\ ) 는 단독으로 써서 출력할 수가 없다.  
그리고 결합된 그 문자를 Escape Sequence라고 하는데 백슬래시 ( \\ )와 문자 하나를 결합하여 나타낸다.  
<p align="center">
<img src="https://user-images.githubusercontent.com/98507442/153470934-95e04c5f-51a6-409c-b104-bcdc7fdec20b.png" width="300" height="450">
</p>
