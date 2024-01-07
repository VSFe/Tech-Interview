## 네트워크

<details>
  <summary><h3>1. 쿠키와 세션의 차이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 세션 방식의 로그인 과정에 대해 설명해 주세요.</li>
<li> HTTP의 특성인 Stateless에 대해 설명해 주세요.</li>
<li> Stateless의 의미를 살펴보면, 세션은 적절하지 않은 인증 방법 아닌가요?</li>
<li> 규모가 커져 서버가 여러 개가 된다면, 세션을 어떻게 관리할 수 있을까요?</li>
</ul>
</details>

<details>
  <summary><h3>2. HTTP 응답코드에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 401 (Unauthorized) 와 403 (Forbidden)은 의미적으로 어떤 차이가 있나요?</li>
<li> 200 (ok) 와 201 (created) 의 차이에 대해 설명해 주세요.</li>
<li> 필요하다면 저희가 직접 응답코드를 정의해서 사용할 수 있을까요? 예를 들어 285번 처럼요. </li>
</ul>
</details>

<details>
  <summary><h3>3. HTTP Method 에 대해 설명해 주세요.</h3></summary>
<ul>
<li> HTTP Method의 멱등성에 대해 설명해 주세요.</li>
<li> GET과 POST의 차이는 무엇인가요?</li>
<li> POST와 PUT, PATCH의 차이는 무엇인가요?</li>
<li> HTTP 1.1 이후로, GET에도 Body에 데이터를 실을 수 있게 되었습니다. 그럼에도 불구하고 왜 아직도 이런 방식을 지양하는 것일까요?</li>
</ul>
</details>

<details>
  <summary><h3>4. HTTP에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 공개키와 대칭키에 대해 설명해 주세요.</li>
<li> 왜 HTTPS Handshake 과정에서는 인증서를 사용하는 것 일까요?</li>
<li> SSL과 TLS의 차이는 무엇인가요?</li>
</ul>
</details>

<details>
  <summary><h3>5. 웹소켓과 소켓 통신의 차이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 소켓과 포트의 차이가 무엇인가요?</li>
<li> 여러 소켓이 있다고 할 때, 그 소켓의 포트 번호는 모두 다른가요?</li>
<li> 사용자의 요청이 무수히 많아지면, 소켓도 무수히 생성되나요?</li>
</ul>
</details>

<details>
  <summary><h3>6. HTTP/1.1과 HTTP/2의 차이점은 무엇인가요?</h3></summary>
<ul>
<li> HOL Blocking 에 대해 설명해 주세요.</li>
<li> HTTP/3.0의 주요 특징에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>7. TCP와 UDP의 차이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> Checksum이 무엇인가요?</li>
<li> TCP와 UDP 중 어느 프로토콜이 Checksum을 수행할까요?</li>
<li> 그렇다면, Checksum을 통해 오류를 정정할 수 있나요? </li>
<li> TCP가 신뢰성을 보장하는 방법에 대해 설명해 주세요.</li>
<li> TCP의 혼잡 제어 처리 방법에 대해 설명해 주세요.</li>
<li> 왜 HTTP는 TCP를 사용하나요?</li>
<li> 그렇다면, 왜 HTTP/3 에서는 UDP를 사용하나요? 위에서 언급한 UDP의 문제가 해결되었나요?</li>
<li> 그런데, 브라우저는 어떤 서버가 TCP를 쓰는지 UDP를 쓰는지 어떻게 알 수 있나요?</li>
<li> 본인이 새로운 통신 프로토콜을 TCP나 UDP를 사용해서 구현한다고 하면, 어떤 기준으로 프로토콜을 선택하시겠어요?</li>
</ul>
</details>

<details>
  <summary><h3>8. DHCP가 무엇인지 설명해 주세요.</h3></summary>
<ul>
<li> DHCP는 몇 계층 프로토콜인가요? </li>
<li> DHCP는 어떻게 동작하나요?</li>
<li> DHCP에서 UDP를 사용하는 이유가 무엇인가요?</li>
<li> DHCP에서, IP 주소 말고 추가로 제공해주는 정보가 있나요?</li>
<li> DHCP의 유효기간은 얼마나 긴가요?</li>
</ul>
</details>

<details>
  <summary><h3>9. IP 주소는 무엇이며, 어떤 기능을 하고 있나요?</h3></summary>
<ul>
<li> IPv6는 IPv4의 주소 고갈 문제를 해결하기 위해 만들어졌지만, 아직도 수많은 기기가 IPv4를 사용하고 있습니다. 고갈 문제를 어떻게 해결할 수 있을까요?</li>
<li> IPv4와 IPv6의 차이에 대해 설명해 주세요.</li>
<li> 수많은 사람들이 유동 IP를 사용하고 있지만, 수많은 공유기에서는 고정 주소를 제공하는 기능이 이미 존재합니다. 어떻게 가능한 걸까요?</li>
<li> IPv4를 사용하는 장비와 IPv6를 사용하는 같은 네트워크 내에서 통신이 가능한가요? 가능하다면 어떤 방법을 사용하나요? </li>
<li> IP가 송신자와 수신자를 정확하게 전송되는 것을 보장해 주나요?</li>
<li> IPv4에서 수행하는 Checksum과 TCP에서 수행하는 Checksum은 어떤 차이가 있나요?</li>
<li> TTL(Hop Limit)이란 무엇인가요? </li>
<li> IP 주소와 MAC 주소의 차이에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>10. OSI 7계층에 대해 설명해 주세요.</h3></summary>
<ul>
<li> Transport Layer와, Network Layer의 차이에 대해 설명해 주세요.</li>
<li> L3 Switch와 Router의 차이에 대해 설명해 주세요.</li>
<li> 각 Layer는 패킷을 어떻게 명칭하나요? 예를 들어, Transport Layer의 경우 Segment라 부릅니다.</li>
<li> 각각의 Header의 Packing Order에 대해 설명해 주세요.</li>
<li> ARP에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>11. 3-Way Handshake에 대해 설명해 주세요.</h3></summary>
<ul>
<li> ACK, SYN 같은 정보는 어떻게 전달하는 것 일까요?</li>
<li> 2-Way Handshaking 를 하지않는 이유에 대해 설명해 주세요.</li>
<li> 두 호스트가 동시에 연결을 시도하면, 연결이 가능한가요? 가능하다면 어떻게 통신 연결을 수행하나요?</li>
<li> SYN Flooding 에 대해 설명해 주세요.</li>
<li> 위 질문과 모순될 수 있지만, 3-Way Handshake의 속도 문제 때문에 이동 수를 줄이는 0-RTT 기법을 많이 적용하고 있습니다. 어떤 방식으로 가능한 걸까요?</li>
</ul>
</details>

<details>
  <summary><h3>12. 4-Way Handshake에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 패킷이 4-way handshake 목적인지 어떻게 파악할 수 있을까요?</li>
<li> 빨리 끊어야 할 경우엔, (즉, 4-way Handshake를 할 여유가 없다면) 어떻게 종료할 수 있을까요?</li>
<li> 4-Way Handshake 과정에서 중간에 한쪽 네트워크가 강제로 종료된다면, 반대쪽은 이를 어떻게 인식할 수 있을까요?</li>
<li> 왜 종료 후에 바로 끝나지 않고, TIME_WAIT 상태로 대기하는 것 일까요? </li>
</ul>
</details>

<details>
  <summary><h3>13. www.github.com을 브라우저에 입력하고 엔터를 쳤을 때, 네트워크 상 어떤 일이 일어나는지 최대한 자세하게 설명해 주세요.</h3></summary>
<ul>
<li> DNS 쿼리를 통해 얻어진 IP는 어디를 가리키고 있나요?</li>
<li> Web Server와 Web Application Server의 차이에 대해 설명해 주세요. </li>
<li> URL, URI, URN은 어떤 차이가 있나요? </li>
</ul>
</details>

<details>
  <summary><h3>14. DNS에 대해 설명해 주세요.</h3></summary>
<ul>
<li> DNS는 몇 계층 프로토콜인가요? </li>
<li> UDP와 TCP 중 어떤 것을 사용하나요?</li>
<li> DNS Recursive Query, Iterative Query가 무엇인가요?</li>
<li> DNS 쿼리 과정에서 손실이 발생한다면, 어떻게 처리하나요?</li>
<li> 캐싱된 DNS 쿼리가 잘못 될 수도 있습니다. 이 경우, 어떻게 에러를 보정할 수 있나요?</li>
<li> DNS 레코드 타입 중 A, CNAME, AAAA의 차이에 대해서 설명해주세요.</li>
<li> hosts 파일은 어떤 역할을 하나요? DNS와 비교하였을 때 어떤 것이 우선순위가 더 높나요?</li>
</ul>
</details>

<details>
  <summary><h3>15. SOP 정책에 대해 설명해 주세요.</h3></summary>
<ul>
<li> CORS 정책이 무엇인가요?</li>
<li> Preflight에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>16. Stateless와 Connectionless에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 왜 HTTP는 Stateless 구조를 채택하고 있을까요?</li>
<li> Connectionless의 논리대로면 성능이 되게 좋지 않을 것으로 보이는데, 해결 방법이 있을까요?</li>
<li> TCP의 keep-alive와 HTTP의 keep-alive의 차이는 무엇인가요?</li>
</ul>
</details>

<details>
  <summary><h3>17. 라우터 내의 포워딩 과정에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 라우팅과 포워딩의 차이는 무엇인가요?</li>
<li> 라우팅 알고리즘에 대해 설명해 주세요.</li>
<li> 포워딩 테이블의 구조에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>18. 로드밸런서가 무엇인가요?</h3></summary>
<ul>
<li> L4 로드밸런서와, L7 로드밸런서의 차이에 대해 설명해 주세요.</li>
<li> 로드밸런서 알고리즘에 대해 설명해 주세요.</li>
<li> 로드밸런싱 대상이 되는 장치중 일부 장치가 문제가 생겨 접속이 불가능하다고 가정해 봅시다. 이 경우, 로드밸런서가 해당 장비로 요청을 보내지 않도록 하려면 어떻게 해야 할까요?</li>
<li> 로드밸런서 장치를 사용하지 않고, DNS를 활용해서 유사하게 로드밸런싱을 하는 방법에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>19. 서브넷 마스크와, 게이트웨이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> NAT에 대해 설명해 주세요. </li>
<li> 서브넷 마스크의 표현 방식에 대해 설명해 주세요.</li>
<li> 그렇다면, 255.0.255.0 같은 꼴의 서브넷 마스크도 가능한가요?</li>
</ul>
</details>

<details>
  <summary><h3>20. 멀티플렉싱과 디멀티플렉싱에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 디멀티플렉싱의 과정에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>21. XSS에 대해서 설명해 주세요.</h3></summary>
<ul>
<li> CSRF랑 XSS는 어떤 차이가 있나요?</li>
<li> XSS는 프론트엔드에서만 막을 수 있나요?</li>
</ul>
</details>
