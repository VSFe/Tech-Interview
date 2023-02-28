## 데이터베이스

<details>
  <summary><h3>1. Key (기본키, 후보키, 슈퍼키 등등...) 에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 기본키는 수정이 가능한가요?</li>
<li> 사실 MySQL의 경우, 기본키를 설정하지 않아도 테이블이 만들어집니다. 어떻게 이게 가능한 걸까요?</li>
<li> 외래키 값은 NULL이 들어올 수 있나요?</li>
<li> 어떤 칼럼의 정의에 UNIQUE 키워드가 붙는다고 가정해 봅시다. 이 칼럼을 활용한 쿼리의 성능은 그렇지 않은 것과 비교해서 어떻게 다를까요?</li>
</ul>
</details>


<details>
  <summary><h3>2. RDB와 NoSQL의 차이에 대해 설명해 주세요.</h3></summary>
<ul>
<li> NoSQL의 강점과, 약점이 무엇인가요?</li>
<li> RDB의 어떠한 특징 때문에 NoSQL에 비해 부하가 많이 걸릴 수 있을까요?</li>
  <li> NoSQL을 활용한 경험이 있나요? 있다면, 왜 RDB를 선택하지 않고 해당 DB를 선택했는지 설명해 주세요.</li>
</ul>
</details>


<details>
  <summary><h3>3. 트랜잭션이 무엇이고, ACID 원칙에 대해 설명해 주세요.</h3></summary>
<ul>
<li> ACID 원칙 중, Durability를 DBMS는 어떻게 보장하나요?</li>
<li> 트랜잭션을 사용해 본 경험이 있나요? 어떤 경우에 사용할 수 있나요?</li>
<li> 읽기에는 트랜잭션을 걸지 않아도 될까요?</li>
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
<li> ORDER BY/GROUP BY 연산의 동작 과정을 인덱스의 존재여부와 연관지어서 설명해 주세요.</li>
<li> 기본키는 인덱스라고 할 수 있을까요? 그렇지 않다면, 인덱스와 기본키는 어떤 차이가 있나요?</li>
<li> 그렇다면 외래키는요?</li>
</ul>
</details>

<details>
  <summary><h3>6. RDBMS, NoSQL에서의 클러스터링/레플리케이션 방식에 대해 설명해 주세요.</h3></summary>
<ul>
  <li>이러한 분산 환경에선, 트랜잭션을 어떻게 관리할 수 있을까요?</li>
  <li>마스터, 슬레이브 데이터 동기화 전 까지의 데이터 정합성을 지키는 방법은 무엇이 있을까요?</li>
  <li>다중 트랜잭션 상황에서의 Deadlock 상황과, 이를 해결하기 위한 방법에 대해 설명해 주세요.</li>
  <li>샤딩 방식은 무엇인가요? 만약 본인이 DB를 분산해서 관리해야 한다면, 레플리케이션 방식과 샤딩 방식 중 어떤 것을 사용할 것 같나요?</li>
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
<li> 앞 질문들을 통해 인덱스의 중요성을 알 수 있었는데, 그렇다면 JOIN의 성능도 인덱스의 유무의 영향을 받나요?</li>
</ul>
</details>

<details>
  <summary><h3>10. B-Tree와 B+Tree에 대해 설명해 주세요.</h3></summary>
<ul>
<li> 그렇다면, B+Tree가 B-Tree에 비해 반드시 좋다고 할 수 있을까요? 그렇지 않다면 어떤 단점이 있을까요?</li>
<li> DB에서 RBT를 사용하지 않고, B-Tree/B+Tree를 사용하는 이유가 있을까요?</li>
<li> 오름차순으로 정렬된 인덱스가 있다고 할 때, 내림차순 정렬을 시도할 경우 성능이 어떻게 될까요? B-Tree/B+Tree의 구조를 기반으로 설명해 주세요.</li>
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
  <li>가끔은 인덱스를 타는 쿼리임에도 Table Full Scan 방식으로 동작하는 경우가 있습니다. 왜 그럴까요?</li>
</ul>
</details>

