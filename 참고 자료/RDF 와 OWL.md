### Triples & URIs

주어(노드) - 동사(엣지) - 목적어(노드)

일반적으로 URI는 주어나 동사에 사용된다. 목적어는 URI이거나 Literal(number, string)로 나타냄.
Literal는 Type을 가질 수 있음. Triple의 장점은 여러 URI 소스들을 구조 변경 없이 하나의 데이터베이스로 가져올 수 있음.

예시: <http://example.com/person/harry> <http://familyontology.net/1.0#hasFather> <http://example.com/person/charles>

### RDF(Resource Descripion Framework) 
웹상의 자원 정보를 표현하기 위한 규격이다. 상이한 메타 데이터간의 효율적인 자원 교환을 가능하게 해준다.
RDF는 triple을 정의하는 방법이다. 'subject' 'predicate' 'object'
rdf:type을 통해 무슨 역할인지 정의 가능? 

ex) :Tolkin :wrote :LordOfTheRings 같은 Linked Graph가 쌓이고 쌓여 방대한 지식 그래프를 구축할 수 있다.

### rdfs(RDF Schema) 
주어 동사 목적어를 대표하는 클래스 또는 관계 정의 가능. OOP 개념과 비슷하다.

### OWL(web ontology language)
무엇을 쓰는지 정의한다 RDF에 비해 더 많은 vocabulary 제공
RDF를 사용하면 오직 목적어만 표현가능하고 RDFS는 클래스를 표현하고,상속을 도와준다. 
하나 하나의 매우 좁은 의미의 Triples를 짤려면 다른 vocabulary가 필요함. OWL이 그런 일을 한다.
사람의 나이에 양수만 들어가게 하는 기능도 수행 가능


RDF -> RDFS -> OWL -> MyWebApp 
표현(구현)되는 순서라고 한다.


자료 출처
https://stackoverflow.com/questions/1740341/what-is-the-difference-between-rdf-and-owl
