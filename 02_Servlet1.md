# Servlet1

## 목차

[Servlet](#Servlet)

[Gradle](#Gradle)

[Life Cycle](#Life-Cycle)

[HTTP](#HTTP)

[GET](#GET)

[POST](#POST)

<br>

## Servlet

서블릿은 JVM 기반에서 웹 개발을 하기 위한 명세서이자 API다.

JAVA를 실행하려면 JRE가 필요하듯이 서블릿을 실행하려면 WAS가 필요하다.

<br>

## Gradle

그래들은 메이븐과 같은 빌드 도구다.

간단히 자바에서 라이브러를 편리하게 추가할 수 있는 도구다.

<br>

## Life Cycle

서블릿의 생명주기는 초기화, 서비스, 소멸 3단계로 구성되어 있다.

1. Start
2. Initialize (초기화)
3. Service (서비스)
4. Destroy (소멸)
5. Unload

<br>

## HTTP

서블릿은 HTTP 요청을 처리할 수 있다.

<br>

## GET

서블릿은 doGet 메서드로 GET 요청을 응답할 수 있다.

doGet 메서드는 HttpServletRequest 클래스의 인스턴스 request로 요청을 받고, HttpServlerResponse 클래스의 인스턴스 response로 응답할 수 있다.

<br>

## POST

서블릿은 doPost 메서드로 POST 요청을 응답할 수 있다.

doPost 메서드는 HttpServletRequest 클래스의 인스턴스 request로 요청을 받고, HttpServlerResponse 클래스의 인스턴스 response로 응답할 수 있다.
