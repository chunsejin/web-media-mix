# arrows.app 사용법

### 1. 노드 제작

![image](https://user-images.githubusercontent.com/94276637/166173077-020858e7-d003-463f-b32e-9dc38e823a6b.png)

우리가 사용할 노드의 모습이다.

![image](https://user-images.githubusercontent.com/94276637/166172986-6d74141e-f53e-4e80-a231-49b695dea1a4.png)

"Add Node" 버튼을 클릭하여 노드를 만들 수 있다. 

![image](https://user-images.githubusercontent.com/94276637/166173062-ba8573b1-ef52-4b39-bc62-0c8ffefa0b5c.png)

또한, **노드의 테두리를 잡고 드래그 하는 것으로 간단하게 노드를 제작할 수 있다.**

![image](https://user-images.githubusercontent.com/94276637/166173364-7e098ce8-baf4-4a45-a415-d06ee72203ca.png)

이렇게 노드를 생성하면 노드 생성과 함께 관계도 같이 형성된다. 보통 노드의 테두리를 잡고 노드를 생성하는 방법을 많이 사용한다.<br><br><br>
노드의 테두리를 드래그해서 이미 존재하는 노드로 갖다대면, 관계 형성이 된다.

<br>

### 2. 표시선

![image](https://user-images.githubusercontent.com/94276637/166173751-03667338-3f85-4673-aee1-ecb81e4d9435.png)


노드를 드래그해서 노드를 주위를 돌려보면, 표시선이 생긴다. 이 표시선을 이용하여 노드를 예쁘게 배치할 수 있다.<br><br><br>

### 3. Node Caption and Relationshp 

![image](https://user-images.githubusercontent.com/94276637/166198468-c11fb7e5-d674-4ba5-bd51-4188e45f163f.png)


노드를 더블 클릭하면 Caption(노드 값)을 넣을 수 있습니다. 대안으로, 노드를 클릭하고 Enter를 눌러도 됩니다.
Caption을 다 넣으면 esc 키를 누르거나 노드 이외의 다른 곳을 클릭하면 됩니다.

![image](https://user-images.githubusercontent.com/94276637/166198753-3245c158-9842-42c8-b3fe-765053652b7a.png)

관계에도 Caption을 넣을 수 있습니다.<br><br><br>

### 3. Relationship 방향

![image](https://user-images.githubusercontent.com/94276637/166198968-3ff2f6db-6b25-4fc4-8e72-4b1df5eb0525.png)


Relationship 방향은 그려진 방향으로 가리킵니다. 반대로 방향을 바꾸고 싶으면 바꾸고 싶은 Relationship을 클릭하고 'Reverse'를 누르면 됩니다.<br><br><br>

### 4. Labels and Property(속성)

![image](https://user-images.githubusercontent.com/94276637/166199472-4c4574ba-6793-4aec-9d74-5b8b1a81b73d.png)


Label은 원하는 노드들을 하나의 set으로 그룹화 하는 기능을 합니다. 같은 label로 labeld 된 노드들끼리 하나의 set으로 그룹화됩니다.
**따라서, Label로 노드들의 역할/유형을 구분 지을 수 있습니다.** '+Label' 버튼을 눌러 Label을 추가할 수 있습니다.

![image](https://user-images.githubusercontent.com/94276637/166199585-a5c907e8-ff3f-41dc-b992-7b81a60a1150.png)


노드와 관계는 속성을 가질 수 있습니다. "+Property"를 눌러 속성을 추가할 수 있습니다.<br><br><br>

### 5. Styling

![image](https://user-images.githubusercontent.com/94276637/166199743-9b99f1a0-e033-4370-ae58-64ddf342ba50.png)


기본적으로 그래프를 그리면 빠른 스케치에 어울리게 간단하고 진한 스타일로 그려집니다. 

![image](https://user-images.githubusercontent.com/94276637/166199918-27ae138a-80c6-4da1-bf9a-64094d80c301.png)


"Thema" 버튼을 눌러서 원하는 스타일에 맞게 그래프 변경이 가능합니다. 

![image](https://user-images.githubusercontent.com/94276637/166200256-ce2f58f9-5584-4685-b9ba-d9020bffd199.png)

개별적으로 노드와 관계의 스타일을 변경하고 싶으면, 우선 원하는 노드 및 관계를 선택합니다. "Customize" 칸에서 선택된 노드와 관계의 스타일을 변경할 수 있습니다.
아무것도 선택하지 않은 채로 스타일을 변경하면 모든 노드와 관계에 적용됩니다. <br><br><br>

### 6. Exporting Images

![image](https://user-images.githubusercontent.com/94276637/166200533-077dd0a3-f9b1-4e50-b6d0-d5a36522bacd.png)


"Download/Export" 버튼은 작성한 그래프의 다운로드 및 공유 기능을 제공합니다.
PNG 이미지는 여러 해상도로 사용 가능하고, 정확히 그래프의 가장자리에서 잘라서 보여줍니다. 따라서 PNG 이미지는 남들에게 보여주는 Presentation에 완벽합니다.
벡터 그래픽이 필요한 경우, SVG 추출을 하면 됩니다. SVG는 이미지를 조정하는 경우 유용합니다. 예를 들어, Sketch에서 svg 파일을 들고오면, 각각의 그래프 요소를 수정가능합니다.
<br><br><br>

### 7. Cypher and Neo4j

![image](https://user-images.githubusercontent.com/94276637/166200995-8d26cd7a-a117-4de3-aaf0-9f161dd39aae.png)


Arrows.app의 Cypher 추출을 사용하여, Neo4j 데이터베이스에 작성한 그래프를 추가할 수 있습니다.
"Download/Export" 버튼을 선택하고, Cypher tab 을 누릅니다. Label과 속성이 포함된 모든 데이터를 받게 됩니다. 이 데이터는 복사하고 붙여놓을 수 있습니다.
Neo4j Desktop 이 있다면, "Run in Neo4j Browser" 버튼을 클릭합니다. <br><br><br>


### 8. 참고 출처

https://medium.com/neo4j/drawing-graphs-with-arrows-app-ee5735caa04d
