## 문제 [10171번: 고양이-Java]
![10171](https://user-images.githubusercontent.com/98507442/153439862-59190b62-e53f-44db-8b77-3bb61db19dfe.png)

## 풀이
오답노트: print()문에서 역슬래시(\)를 사용하려면 역슬래시 2개를 연달아 입력해야 한다. print(\); (X) -> print(\\); (O)
~~~java
public class Test {
	public static void main(String[] args) {
		System.out.println("\\    /\\");
		System.out.println(" )  ( ')");
		System.out.println("(  /  )");
		System.out.println(" \\(__)|");
	}
}
~~~
