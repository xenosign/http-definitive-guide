## 📚 HTTP 완벽 가이드 목차 (한글/영어 원제목 병기)

### 1부. HTTP: 웹의 기초 (Part I. HTTP: The Web's Foundation)

#### 1장. HTTP 개관 (Chapter 1. An Overview of HTTP)

* 1.1 HTTP: 인터넷의 멀티미디어 배달부 (HTTP: The Internet's Multimedia Delivery Service)
* 1.2 웹 클라이언트와 서버 (Web Clients and Servers)
* 1.3 리소스 (Resources)
* 1.4 트랜잭션 (Transactions)
* 1.5 메시지 (Messages)
* 1.6 TCP 커넥션 (TCP Connections)
* 1.7 프로토콜 버전 (Protocol Versions)
* 1.8 웹의 구성요소 (The Components of the Web)
* 1.9 시작의 끝 (The End of the Beginning)
* 1.10 추가 정보 (For More Information)

#### 2장. URL과 리소스 (Chapter 2. URLs and Resources)

* 2.1 인터넷의 리소스 탐색하기 (Navigating the Internet's Resources)
* 2.2 URL 문법 (URL Syntax)
* 2.3 URL 단축 (Shortened URLs)
* 2.4 안전하지 않은 문자 (Unsafe Characters)
* 2.5 스킴의 세계 (A Tour of the Schemes)
* 2.6 미래 (The Future)
* 2.7 추가 정보 (For More Information)

#### 3장. HTTP 메시지 (Chapter 3. HTTP Messages)

* 3.1 메시지의 흐름 (The Flow of Messages)
* 3.2 메시지의 각 부분 (The Parts of an HTTP Message)
* 3.3 메서드 (Methods)
* 3.4 상태 코드 (Status Codes)
* 3.5 헤더 (Headers)
* 3.6 추가 정보 (For More Information)

#### 4장. 커넥션 관리 (Chapter 4. Connection Management)

* 4.1 TCP 커넥션 (TCP Connections)
* 4.2 TCP의 성능에 대한 고려 (The Consideration of TCP Performance)
* 4.3 HTTP 커넥션 관리 (HTTP Connection Management)
* 4.4 병렬 커넥션 (Parallel Connections)
* 4.5 지속 커넥션 (Persistent Connections)
* 4.6 파이프라인 커넥션 (Pipelined Connections)
* 4.7 커넥션 끊기 (Close After Connection)
* 4.8 추가 정보 (For More Information)

---

### 2부. HTTP 아키텍처 (Part II. HTTP Architecture)

#### 5장. 웹 서버 (Chapter 5. Web Servers)

* 5.1 다채로운 웹 서버 (A Variety of Web Servers)
* 5.2 간단한 펄 웹 서버 (A Simple Perl Web Server)
* 5.3 진짜 웹 서버가 하는 일 (What a Real Web Server Does)
* 5.4 단계 1: 클라이언트 커넥션 수락 (Step 1: Accepting Client Connections)
* 5.5 단계 2: 요청 메시지 수신 (Step 2: Receiving Request Messages)
* 5.6 단계 3: 요청 처리 (Step 3: Processing the Request)
* 5.7 단계 4: 리소스의 매핑과 접근 (Step 4: Resource Mapping and Access)
* 5.8 단계 5: 응답 만들기 (Step 5: Building the Response)
* 5.9 단계 6: 응답 보내기 (Step 6: Sending the Response)
* 5.10 단계 7: 로깅 (Step 7: Logging)
* 5.11 추가 정보 (For More Information)

#### 6장. 프락시 (Chapter 6. Proxies)

* 6.1 웹 중개자 (Web Intermediaries)
* 6.2 왜 프락시를 사용하는가? (Why Proxies?)
* 6.3 프락시는 어디에 있는가? (Where Do Proxies Live?)
* 6.4 클라이언트 프락시 설정 (Client Proxy Configuration)
* 6.5 프락시 요청의 미묘한 특징들 (Subtleties of Proxy Requests)
* 6.6 메시지 추적 (Message Tracing)
* 6.7 프락시 인증 (Proxy Authentication)
* 6.8 프락시 상호운용성 (Proxy Interoperability)
* 6.9 추가 정보 (For More Information)

#### 7장. 캐시 (Chapter 7. Caching)

* 7.1 불필요한 데이터 전송 (Useless Data Transfers)
* 7.2 대역폭 병목 (Bandwidth Bottlenecks)
* 7.3 갑작스런 요청 쇄도(Flash Crowds) (Flash Crowds)
* 7.4 거리로 인한 지연 (Distance Delays)
* 7.5 적중과 부적중 (Hits and Misses)
* 7.6 캐시 토폴로지 (Cache Topologies)
* 7.7 캐시 처리 단계 (Cache Processing Steps)
* 7.8 사본을 신선하게 유지하기 (Keeping Copies Fresh)
* 7.9 캐시 제어 (Cache Controls)
* 7.10 캐시 제어 설정 (Setting Cache Controls)
* 7.11 자세한 알고리즘 (Detailed Algorithms)
* 7.12 캐시와 광고 (Caches and Advertising)
* 7.13 추가 정보 (For More Information)

#### 8장. 통합점: 게이트웨이, 터널, 릴레이 (Chapter 8. Integration Points: Gateways, Tunnels, and Relays)

* 8.1 게이트웨이 (Gateways)
* 8.2 프로토콜 게이트웨이 (Protocol Gateways)
* 8.3 리소스 게이트웨이 (Resource Gateways)
* 8.4 애플리케이션 인터페이스와 웹 서비스 (Application Interfaces and Web Services)
* 8.5 터널 (Tunnels)
* 8.6 릴레이 (Relays)
* 8.7 추가 정보 (For More Information)

#### 9장. 웹 로봇 (Chapter 9. Web Robots)

* 9.1 크롤러와 크롤링 (Crawlers and Crawling)
* 9.2 로봇의 HTTP (Robots' HTTP)
* 9.3 부적절하게 동작하는 로봇들 (Misbehaving Robots)
* 9.4 로봇 차단하기 (Blocking Robots)
* 9.5 로봇 에티켓 (Robot Etiquette)
* 9.6 검색엔진 (Search Engines)
* 9.7 추가 정보 (For More Information)

#### 10장. HTTP-NG (Chapter 10. HTTP-NG)

* 10.1 HTTP는 멈추지 않는다 (HTTP Doesn't Stop)
* 10.2 HTTP-NG 1.0 (HTTP-NG 1.0)
* 10.3 W3C의 HTTP-NG (The W3C's HTTP-NG)
* 10.4 추가 정보 (For More Information)

---

### 3부. 식별, 인가, 보안 (Part III. Identification, Authorization, and Security)

#### 11장. 클라이언트 식별과 쿠키 (Chapter 11. Client Identification and Cookies)

* 11.1 개별 접촉 (Individual Contact)
* 11.2 HTTP 헤더 (HTTP Headers)
* 11.3 클라이언트 IP 주소 (Client IP Address)
* 11.4 사용자 로그인 (User Login)
* 11.5 뚱뚱한 URL (Fat URLs)
* 11.6 쿠키 (Cookies)
* 11.7 추가 정보 (For More Information)

#### 12장. 기본 인증 (Chapter 12. Basic Authentication)

* 12.1 인증 (Authentication)
* 12.2 기본 인증 (Basic Authentication)
* 12.3 기본 인증의 보안 결함 (Basic Authentication Security Flaws)
* 12.4 추가 정보 (For More Information)

#### 13장. 다이제스트 인증 (Chapter 13. Digest Authentication)

* 13.1 다이제스트 인증의 개선점 (Digest Authentication Improvements)
* 13.2 요약 계산 (Digest Calculation)
* 13.3 보호 수준(Quality of Protection) 향상 (Quality of Protection Enhancements)
* 13.4 실제 상황에 대한 고려 (Practical Considerations)
* 13.5 보안에 대한 고려사항 (Security Considerations)
* 13.6 추가 정보 (For More Information)

#### 14장. 보안 HTTP (Chapter 14. Secure HTTP)

* 14.1 HTTP를 안전하게 만들기 (Making HTTP Secure)
* 14.2 디지털 암호학 (Digital Cryptography)
* 14.3 대칭키 암호법 (Symmetric-Key Cryptography)
* 14.4 공개키 암호법 (Public-Key Cryptography)
* 14.5 디지털 서명 (Digital Signatures)
* 14.6 디지털 인증서 (Digital Certificates)
* 14.7 HTTPS의 세부사항 (HTTPS Details)
* 14.8 진짜 HTTPS 클라이언트 (A Real HTTPS Client)
* 14.9 터널링 보안을 통한 프락시 (Proxying Security Through Tunnels)
* 14.10 추가 정보 (For More Information)

---

### 4부. 엔터티, 인코딩, 국제화 (Part IV. Entities, Encoding, and Internationalization)

#### 15장. 엔터티와 인코딩 (Chapter 15. Entities and Encodings)

* 15.1 메시지는 컨테이너다 (Messages Are Containers)
* 15.2 Content-Length: 엔터티의 길이 (Content-Length: The Length of the Entity)
* 15.3 엔터티 요약 (Entity Digests)
* 15.4 미디어 타입과 차셋(Charset) (Media Types and Charsets)
* 15.5 콘텐츠 인코딩 (Content Encoding)
* 15.6 전송 인코딩과 청크 인코딩 (Transfer Encoding and Chunked Encoding)
* 15.7 시간에 따라 바뀌는 인스턴스 (Time-Varying Instances)
* 15.8 검사기와 신선도 (Validators and Freshness)
* 15.9 범위 요청 (Range Requests)
* 15.10 델타 인코딩 (Delta Encoding)
* 15.11 추가 정보 (For More Information)

#### 16장. 국제화 (Chapter 16. Internationalization)

* 16.1 국제적인 콘텐츠를 다루기 위해 필요한 것 (What's Needed to Handle International Content)
* 16.2 문자집합과 인코딩 (Character Sets and Encodings)
* 16.3 다중언어 문자 인코딩 표준 (Multilingual Character Encoding Standards)
* 16.4 언어 태그와 HTTP (Language Tags and HTTP)
* 16.5 국제화된 URI (Internationalized URIs)
* 16.6 기타 고려사항 (Other Considerations)
* 16.7 추가 정보 (For More Information)

#### 17장. 내용 협상과 트랜스코딩 (Chapter 17. Content Negotiation and Transcoding)

* 17.1 내용 협상 기법 (Content Negotiation Techniques)
* 17.2 클라이언트 주도 협상 (Client-Driven Negotiation)
* 17.3 서버 주도 협상 (Server-Driven Negotiation)
* 17.4 투명 협상 (Transparent Negotiation)
* 17.5 트랜스코딩 (Transcoding)
* 17.6 다음 단계 (Next Steps)
* 17.7 추가 정보 (For More Information)

---

### 5부. 콘텐츠 발행 및 배포 (Part V. Content Publishing and Distribution)

#### 18장. 웹 호스팅 (Chapter 18. Web Hosting)

* 18.1 호스팅 서비스 (Hosting Services)
* 18.2 가상 호스팅 (Virtual Hosting)
* 18.3 안정적인 웹 사이트 만들기 (Building a Robust Web Site)
* 18.4 웹 사이트 빠르게 만들기 (Making a Web Site Fast)
* 18.5 추가 정보 (For More Information)

#### 19장. 배포 시스템 (Chapter 19. Publishing Systems)

* 19.1 배포 지원을 위한 FrontPage 서버 확장(FPSE) (FrontPage Server Extensions (FPSE) for Publishing Support)
* 19.2 WebDAV와 공동 저작 (WebDAV and Collaborative Authoring)
* 19.3 추가 정보 (For More Information)

#### 20장. 리다이렉션과 부하 균형 (Chapter 20. Redirection and Load Balancing)

* 20.1 왜 리다이렉트 할까? (Why Redirect?)
* 20.2 리다이렉트 할 곳 (Where to Redirect)
* 20.3 리다이렉션 프로토콜의 개요 (An Overview of Redirection Protocols)
* 20.4 일반적인 리다이렉션 방법 (General Redirection Methods)
* 20.5 프락시 리다이렉션 방법 (Proxy Redirection Methods)
* 20.6 캐시 리다이렉션 방법 (Cache Redirection Methods)
* 20.7 인터넷 캐시 프로토콜 (Internet Cache Protocol)
* 20.8 캐시 배열 라우팅 프로토콜 (Cache Array Routing Protocol)
* 20.9 하이퍼텍스트 캐싱 프로토콜 (Hypertext Caching Protocol)
* 20.10 추가 정보 (For More Information)

#### 21장. 로깅과 사용 추적 (Chapter 21. Logging and Usage Tracking)

* 21.1 로그란 무엇인가? (What Are Logs?)
* 21.2 로그 포맷 (Log Formats)
* 21.3 적중 계량하기 (Hit Metering)
* 21.4 사생활 보호에 대해 (On Privacy)
* 21.5 추가 정보 (For More Information)