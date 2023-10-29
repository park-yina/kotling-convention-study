# 오버로드 레이아웃
<br>
클래스 내에서 오버로드된 메소드들은 항상 서로 가까운 곳에 위치하게 두어야한다.

# 네이밍 규칙
<br>
코틀린에서 클래스와 패키지의 네이밍 규칙은 꽤나 심플하다:
<br>
🟥패키지의 이름은 항상 소문자로 구성하고, 밑줄문자를 사용하지 말아야한다
<blockquote>
org.example.project와 같은 형태로 작성
</blockquote>
🟥멀티 문자를 사용한 이름의 경우 통상적으로는 권장되지 않는다.
<br>
->만약 사용하고 싶은 경우 그냥 함께 연결하거나 camel케이스로 나타낼 수 있다.
<blockquote>
org.example.myProject와 같은 형태로 작성
</blockquote>
<br>
🟥클래스와 오브젝트 이름의 경우 첫시작을 대문자로 사용하고 camel케이스 역시 사용 가능하다.

### 함수명
<br>
함수 프로퍼티 지역변수는 소문자로 시작하고 camel케이스도 사용가능하다. 밑줄문자 사용 X
<blockquote>
var declarationCount = 1
</blockquote>
<br>
예외사안:클래스의 인스턴스를 만드는 팩토리 함수의 경우 반환타입과 동일한 이름 역시 사용가능합니다.
<blockquote>
interface Foo { /*...*/ }
class FooImpl : Foo { /*...*/ }
fun Foo(): Foo { return FooImpl() }
</blockquote>

### 테스트 메소드의 이름
<br>
벡틱(`)으로 묶인 공백도 이름에 사용 가능하다.
<br>
🟥이러한 이름은 안드로이드의 런타임에서는 지원X
<br>
밑줄문자 역시 테스트 메소드에서는 사용 가능하다.

