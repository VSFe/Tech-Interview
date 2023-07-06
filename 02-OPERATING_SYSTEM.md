## 운영체제

<details>
  <summary><h3>1. 시스템 콜이 무엇인지 설명해 주세요.</h3></summary>
<ul>
<li> 우리가 사용하는 시스템 콜의 예시를 들어주세요.</li>
<li> 시스템 콜이, 운영체제에서 어떤 과정으로 실행되는지 설명해 주세요.</li>
<li> 시스템 콜의 유형에 대해 설명해 주세요.</li>
<li> 운영체제의 Dual Mode 에 대해 설명해 주세요.</li>
<li> 왜 유저모드와 커널모드를 구분해야 하나요? </li>
<li> 서로 다른 시스템 콜을 어떻게 구분할 수 있을까요?</li>
</ul>
</details>

<details>
  <summary><h3>2. 인터럽트가 무엇인지 설명해 주세요.</h3></summary>
<ul>
<li> 인터럽트는 어떻게 처리하나요?</li>
<li> Polling 방식에 대해 설명해 주세요.</li>
<li> HW / SW 인터럽트에 대해 설명해 주세요.</li>
<li> 동시에 두 개 이상의 인터럽트가 발생하면, 어떻게 처리해야 하나요? </li>
</ul>
</details>

<details>
  <summary><h3>3. 프로세스가 무엇인가요?</h3></summary>
<ul>
<li> 프로그램과 프로세스, 스레드의 차이에 대해 설명해 주세요.</li>
<li> PCB가 무엇인가요?</li>
<li> 그렇다면, 스레드는 PCB를 갖고 있을까요?</li>
<li> 리눅스에서, 프로세스와 스레드는 각각 어떻게 생성될까요?</li>
<li> 자식 프로세스가 상태를 알리지 않고 죽거나, 부모 프로세스가 먼저 죽게 되면 어떻게 처리하나요?</li>
<li> 리눅스에서, 데몬프로세스에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>4. 프로세스 주소공간에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 초기화 하지 않은 변수들은 어디에 저장될까요?</li>
<li> 일반적인 주소공간 그림처럼, Stack과 Heap의 크기는 매우 크다고 할 수 있을까요? 그렇지 않다면, 그 크기는 언제 결정될까요?</li>
<li> Stack과 Heap 공간에 대해, 접근 속도가 더 빠른 공간은 어디일까요?</li>
<li> 다음과 같이 공간을 분할하는 이유가 있을까요?</li>
<li> 스레드의 주소공간은 어떻게 구성되어 있을까요?</li>
<li> "스택"영역과 "힙"영역은 정말 자료구조의 스택/힙과 연관이 있는 걸까요? 만약 그렇다면, 각 주소공간의 동작과정과 연계해서 설명해 주세요.</li>
<li> IPC의 Shared Memory 기법은 프로세스 주소공간의 어디에 들어가나요? 그런 이유가 있을까요? </li>
</ul>
</details>

<details>
  <summary><h3>5. 단기, 중기, 장기 스케쥴러에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 현대 OS에는 단기, 중기, 장기 스케쥴러를 모두 사용하고 있나요?</li>
<li> 프로세스의 스케쥴링 상태에 대해 설명해 주세요.</li>
<li> preemptive/non-preemptive 에서 존재할 수 없는 상태가 있을까요?</li>
<li> Memory가 부족할 경우, Process는 어떠한 상태로 변화할까요?</li>
</ul>
</details>

<details>
  <summary><h3>6. 컨텍스트 스위칭 시에는 어떤 일들이 일어나나요?</h3></summary>
<ul>
<li> 프로세스와 쓰레드는 컨텍스트 스위칭이 발생했을 때 어떤 차이가 있을까요?</li>
<li> 컨텍스트 스위칭이 발생할 때, 기존의 프로세스 정보는 커널스택에 어떠한 형식으로 저장되나요?</li>
<li> 컨텍스트 스위칭은 언제 일어날까요?</li>
</ul>
</details>

<details>
  <summary><h3>7. 프로세스 스케줄링 알고리즘에는 어떤 것들이 있나요?</h3></summary>
<ul>
<li> RR을 사용할 때, Time Slice에 따른 trade-off를 설명해 주세요.</li>
<li> 싱글 스레드 CPU 에서 상시로 돌아가야 하는 프로세스가 있다면, 어떤 스케쥴링 알고리즘을 사용하는 것이 좋을까요? 또 왜 그럴까요?</li>
<li> 동시성과 병렬성의 차이에 대해 설명해 주세요.</li>
<li> 타 스케쥴러와 비교하여, Multi-level Feedback Queue는 어떤 문제점들을 해결한다고 볼 수 있을까요?</li>
<li> FIFO 스케쥴러는 정말 쓸모가 없는 친구일까요? 어떤 시나리오에 사용하면 좋을까요? </li>
<li> 유저 스레드와 커널 스레드의 스케쥴링 알고리즘은 똑같을까요?</li>
</ul>
</details>

<details>
  <summary><h3>8. 뮤텍스와 세마포어의 차이점은 무엇인가요?</h3></summary>
<ul>
<li> 이진 세마포어와 뮤텍스의 차이에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>9. Deadlock 에 대해 설명해 주세요.</h3></summary>
<ul>
<li> Deadlock 이 동작하기 위한 4가지 조건에 대해 설명해 주세요.</li>
<li> 그렇다면 3가지만 충족하면 왜 Deadlock 이 발생하지 않을까요?</li>
<li> 어떤 방식으로 예방할 수 있을까요?</li>
<li> 왜 현대 OS는 Deadlock을 처리하지 않을까요?</li>
<li> Wait Free와 Lock Free를 비교해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>10. 프로그램이 컴파일 되어, 실행되는 과정을 간략하게 설명해 주세요.</h3></summary>
<ul>
<li> 링커와, 로더의 차이에 대해 설명해 주세요.</li>
<li> 컴파일 언어와 인터프리터 언어의 차이에 대해 설명해 주세요.</li>
<li> JIT에 대해 설명해 주세요.</li>
<li> 본인이 사용하는 언어는, 어떤식으로 컴파일 및 실행되는지 설명해 주세요.</li>
<li> Python 같은 언어는 CPython, Jython, PyPy등의 다양한 구현체가 있습니다. 각각은 어떤 차이가 있을까요? 또한, 실행되는 과정 또한 다를까요?</li>
</ul>
</details>

<details>
  <summary><h3>11. IPC가 무엇이고, 어떤 종류가 있는지 설명해 주세요.</h3></summary>
<ul>
<li> Shared Memory가 무엇이며, 사용할 때 유의해야 할 점에 대해 설명해 주세요.</li>
<li> 메시지 큐는 단방향이라고 할 수 있나요?</li>
</ul>
</details>

<details>
  <summary><h3>12. Thread Safe 하다는 것은 어떤 의미인가요?</h3></summary>
<ul>
<li> Thread Safe 를 보장하기 위해 어떤 방법을 사용할 수 있나요?</li>
<li> Peterson's Algorithm 이 무엇이며, 한계점에 대해 설명해 주세요.</li>
<li> Race Condition 이 무엇인가요?</li>
<li> Thread Safe를 구현하기 위해 반드시 락을 사용해야 할까요? 그렇지 않다면, 어떤 다른 방법이 있을까요?</li>
</ul>
</details>

<details>
  <summary><h3>13. Thread Pool, Monitor, Fork-Join에 대해 설명해 주세요.</h3></summary>
<ul>
<li> Thread Pool을 사용한다고 가정하면, 어떤 기준으로 스레드의 수를 결정할 것인가요? </li>
</ul>
</details>

<details>
  <summary><h3>14. 캐시 메모리 및 메모리 계층성에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 캐시 메모리는 어디에 위치해 있나요?</li>
<li> L1, L2 캐시에 대해 설명해 주세요.</li>
<li> 캐시에 올라오는 데이터는 어떻게 관리되나요?</li>
<li> 캐시간의 동기화는 어떻게 이루어지나요?</li>
<li> 캐시 메모리의 Mapping 방식에 대해 설명해 주세요.</li>
<li> 캐시의 지역성에 대해 설명해 주세요.</li>
<li> 캐시의 지역성을 기반으로, 이차원 배열을 가로/세로로 탐색했을 때의 성능 차이에 대해 설명해 주세요.</li>
<li> 캐시의 공간 지역성은 어떻게 구현될 수 있을까요? (힌트: 캐시는 어떤 단위로 저장되고 관리될까요?) </li>
</ul>
</details>

<details>
  <summary><h3>15.메모리의 연속할당 방식 세 가지를 설명해주세요. (first-fit, best-fit, worst-fit)</h3></summary>
<ul>
<li> worst-fit 은 언제 사용할 수 있을까요?</li>
<li> 성능이 가장 좋은 알고리즘은 무엇일까요?</li>
</ul>
</details>

<details>
  <summary><h3>16. Thrashing 이란 무엇인가요?</h3></summary>
<ul>
<li> Thrashing 발생 시, 어떻게 완화할 수 있을까요?</li>
</ul>
</details>

<details>
  <summary><h3>17. 가상 메모리란 무엇인가요?</h3></summary>
<ul>
<li> 가상 메모리가 가능한 이유가 무엇일까요?</li>
<li> Page Fault가 발생했을 때, 어떻게 처리하는지 설명해 주세요.</li>
<li> 페이지 크기에 대한 Trade-Off를 설명해 주세요.</li>
<li> 페이지 크기가 커지면, 페이지 폴트가 더 많이 발생한다고 할 수 있나요?</li>
</ul>
</details>

<details>
  <summary><h3>18. 세그멘테이션과 페이징의 차이점은 무엇인가요?</h3></summary>
<ul>
<li> 페이지와 프레임의 차이에 대해 설명해 주세요.</li>
<li> 내부 단편화와, 외부 단편화에 대해 설명해 주세요.</li>
<li> 페이지에서 실제 주소를 어떻게 가져올 수 있는지 설명해 주세요.</li>
<li> 어떤 주소공간이 있을 때, 이 공간이 수정 가능한지 확인할 수 있는 방법이 있나요?</li>
<li> 32비트에서, 페이지의 크기가 1kb 이라면 페이지 테이블의 최대 크기는 몇 개일까요?</li>
<li> C/C++ 개발을 하게 되면 Segmentation Fault 라는 에러를 접할 수 있을텐데, 이 에러는 세그멘테이션/페이징과 어떤 관계가 있을까요? </li> 
</ul>
</details>

<details>
  <summary><h3>19. TLB는 무엇인가요?</h3></summary>
<ul>
<li> TLB를 쓰면 왜 빨라지나요?</li>
<li> MMU가 무엇인가요?</li>
<li> TLB와 MMU는 어디에 위치해 있나요?</li>
<li> 코어가 여러개라면, TLB는 어떻게 동기화 할 수 있을까요? </li>
</ul>
</details>

<details>
  <summary><h3>20. 동기화를 구현하기 위한 하드웨어적인 해결 방법에 대해 설명해 주세요.</h3></summary>
<ul>
<li> volatile 키워드는 어떤 의미가 있나요?</li>
<li> 싱글코어가 아니라 멀티코어라면, 어떻게 동기화가 이뤄질까요?</li>
</ul>
</details>

<details>
  <summary><h3>21. 페이지 교체 알고리즘에 대해 설명해 주세요.</h3></summary>
<ul>
<li> LRU 알고리즘은 어떤 특성을 이용한 알고리즘이라고 할 수 있을까요?</li>
<li> LRU 알고리즘을 구현한다면, 어떻게 구현할 수 있을까요?</li>
</ul>
</details>

<details>
  <summary><h3>22. File Descriptor와, File System에 에 대해 설명해 주세요.</h3></summary>
<ul>
<li> I-Node가 무엇인가요?</li>
</ul>
</details>

<details>
  <summary><h3>23. 동기와 비동기, 블로킹과 논블로킹의 차이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 그렇다면, 동기이면서 논블로킹이고, 비동기이면서 블로킹인 경우는 의미가 있다고 할 수 있나요?</li>
<li> I/O 멀티플렉싱에 대해 설명해 주세요.</li>
</ul>
</details>
