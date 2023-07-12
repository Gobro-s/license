## System

-   무엇인가 하기 위해 구성한 체계
    -   즉, 목적에 맞춰서 만든 체계

## Infra

-   특정 앱을 활용한 서비스를 운영하기 위해 필요한 하드웨어, 운영체제, 미들웨어, 네트워크 등 시스템 기반을 총칭
    -   즉 IT Infra => System들의 기반 체계
    -   HardWare
    -   OS
    -   Network
    -   Middleware
        -   Nginx나 DB WAS 처럼 Software구성이지만 기능을 제공하기 위한 솔루션들 (브릿지 역할)

### 예 1.

-   채팅서비스를 홍길동은 휴대폰으로, 김아무개는 웹페이지로 이용중이라면 이들간 벌어지는 일은?
    -   Socket 통신
    -   TCP
    -   UDP
    -   RUDP - QUIC
    -   REST
    -   같은 일들이 벌어지고 있다.
    -   양측에서 서버로 커넥션이 만들어지고 송수신이 이루어진다.

### 예 2.

-   채팅서비스를 홍길동은 서울에서 휴대폰으로, 김아무개는 부산에서 웹페이지로 이용중이라면 이들간 벌어지는 일은?
    -   커넥션이 맺어지고
    -   데이터를 움직이게 되는데
    -   Router (OSI 7layer)
    -   TLS (SSL) -> Https
    -   Domain
    -   DNS (Domain Name Server)
    -   IP
    -   Firewall
    -   DMZ
    -   Load Balancing
    -   등등 ...

## System과 Infra의 관계

-   우선 Infra가 갖춰지고 System이 올라간다. 그 위에 Application이 합쳐긴 형태를 Service라 한다.
