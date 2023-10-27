# 디렉토리 구조(폴더 구조)

<br>
순수한 코틀린 프로젝트에서, 권장되는 폴더구조는 보통 루트 패키지를 생략하는 패키지 구조를 따른다.<br>
예를 들어, 프로젝트 내에 있는 모든 코드가 'org.example.kotlin'의 패키지와 그것의 서브 패키지(하위 패키지)에 있다면
<br>
org.example.kotlin패키지와 있는 파일들은 반드시 소스루트의 바로 아래에 두어야하며,
<br>
org.example.kotlin.network.socket 내의 파일들은 반드시 network/socket 하위 디렉토리 내 소스루트에 두어야한다.

> JVM: 코틀린과 자바를 함께 쓰는 프로젝트 내에서, 코틀린 소스파일들은 자바의 소스파일과 같은 소스 루트 내에 위치해야만 하고<br>
같은 폴더구조를 따라야만 한다" 각각의 파일들은 선언에 해당되는 디렉토리에 저장되어야만 한다.

![예시 이미지](https://github.com/park-yina/kotling-convention-study/assets/111878820/3b902199-025a-4505-8fc5-3dede39651b8)
