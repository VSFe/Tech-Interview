## 데이터베이스

<details>
  <summary><h3>1.Key (기본키, 후보키, 슈퍼키 등등...) 에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 기본키는 수정이 가능한가요?</li>
<li> 외래키 값은 NULL이 들어올 수 있나요?</li>
</ul>
</details>


<details>
  <summary><h3>2. RDB와 NoSQL의 차이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> NoSQL의 강점이 무엇인가요?</li>
<li> RDB의 어떠한 특징 때문에 NoSQL에 비해 부하가 많이 걸릴 수 있을까요?</li>
</ul>
</details>


<details>
  <summary><h3>3. 트랜잭션이 무엇이고, ACID 원칙에 대해 설명해 주세요.</h3></summary>
<ul>
<li> ACID 원칙 중, Durability를 DBMS는 어떻게 보장하나요?</li>
<li> 트랜잭션을 사용해 본 경험이 있나요? 어떤 경우에 사용할 수 있나요?</li>
</ul>
</details>

<details>
  <summary><h3>4. 트랜잭션 격리 레벨에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 모든 DBMS가 4개의 레벨을 모두 구현하고 있나요? 그렇지 않다면 그 이유는 무엇일까요?</li>
<li> 만약 MySQL을 사용하고 있다면, (InnoDB 기준) Undo 영역과 Redo 영역에 대해 설명해 주세요.</li>
  <li> 그런데, 스토리지 엔진이 정확히 무엇을 하는 건가요?</li>
</ul>
</details>

<details>
  <summary><h3>5. 인덱스가 무엇이고, 언제 사용하는지 설명해 주세요.</h3></summary>
<ul>
<li> 일반적으로 인덱스는 수정이 잦은 테이블에선 사용하지 않기를 권합니다. 왜 그럴까요?</li>
<li> 앞 꼬리질문에 대해, 그렇다면 인덱스에서 사용하지 않겠다고 선택한 값은 위 정책을 그대로 따라가나요?</li>
</ul>
</details>

<details>
  <summary><h3>6. RDBMS, NoSQL에서의 클러스터링/레플리케이션 방식에 대해 설명해 주세요.</h3></summary>
<ul>
  <li>이러한 분산 환경에선, 트랜잭션을 어떻게 관리할 수 있을까요?</li>
  <li>마스터, 슬레이브 데이터 동기화 전 까지의 데이터 정합성을 지키는 방법은 무엇이 있을까요?</li>
  <li>다중 트랜잭션 상황에서의 Deadlock 상황과, 이를 해결하기 위한 방법에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>7. 정규화가 무엇인가요?</h3></summary>
<ul>
<li> 정규화를 하지 않을 경우, 발생할 수 있는 이상현상에 대해 설명해 주세요.</li>
<li> 각 정규화에 대해, 그 정규화가 진행되기 전/후의 테이블의 변화에 대해 설명해 주세요.</li>
<li> 정규화가 무조건 좋은가요? 그렇지 않다면, 어떤 상황에서 역정규화를 하는게 좋은지 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>8. View가 무엇이고, 언제 사용할 수 있나요?</h3></summary>
<ul>
<li> 그렇다면, View의 값을 수정해도 실제 테이블에는 반영되지 않나요?</li>
</ul>
</details>

<details>
  <summary><h3>9. DB Join이 무엇인지 설명하고, 각각의 종류에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 사실, JOIN은 상당한 시간이 걸릴 수 있기에 내부적으로 다양한 구현 방식을 사용하고 있습니다. 그 예시에 대해 설명해 주세요.</li>
<li> 그렇다면 입력한 쿼리에서 어떤 구현 방식을 사용하는지는 어떻게 알 수 있나요?</li>
</ul>
</details>

<details>
  <summary><h3>10. B-Tree와 B+Tree에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 그렇다면, B+Tree가 B-Tree에 비해 반드시 좋다고 할 수 있을까요? 그렇지 않다면 어떤 단점이 있을까요?</li>
<li> DB에서 RBT를 사용하지 않고, B-Tree/B+Tree를 사용하는 이유가 있을까요?</li>
</ul>
</details>

<details>
  <summary><h3>11. DB Locking에 대해 설명해 주세요.</h3></summary>
<ul>
<li> Optimistic Lock/Pessimistic Lock에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>12. 트래픽이 높아질 때, DB는 어떻게 관리를 할 수 있을까요?</h3></summary>
<ul>
</ul>
</details>

<details>
  <summary><h3>13. Schema가 무엇인가요?</h3></summary>
<ul>
  <li>Schema의 3계층에 대해 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>14. DB의 Connection Pool에 대해 설명해 주세요.</h3></summary>
<ul>
  <li>DB와 Client가 Connection을 어떻게 구성하는지 설명해 주세요.</li>
</ul>
</details>

<details>
  <summary><h3>15. Table Full Scan, Index Range Scan에 대해 설명해 주세요.</h3></summary>
<ul>
</ul>
</details>

