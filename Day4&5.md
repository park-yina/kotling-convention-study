# 프로퍼티명
<br>
프로퍼티(const로 표시된 프로퍼티나 최상위 레벨의 val 속성 오브젝트:깊은 수준의 불변 데이터를 가진 사용자 정의 get함수가 없는)의 경우
<br>
대문자를 사용하거나 스크리밍 스네이크 케이스라고 불리는 underscore-separated를 사용해야 합니다.<br>

>예시
><br>
>const val MAX_COUNT = 8<br>
val USER_NAME_FIELD = "UserName"
<br>
행동이나 가변데이터의 속성을 가진 오브젝트 혹은 최상의 레벨의 이름은 카멜 케이스를 사용하여 나타낸다<br>

>val mutableCollection: MutableSet<String> = HashSet()
<br>
싱글톤 객체를 참조하는 프로퍼티명의 경우 객체(오브젝트)의 이름과 동일한 스타일을 사용한다
<br>
enum 상수의 경우 스크리밍 스네이크 케이스와 대문자 모두 사용가능하고,upper cammel케이스 또한 사용가능하다.


# backing프로퍼티(지원속성)의 이름
