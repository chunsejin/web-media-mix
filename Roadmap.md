# Roadmap
중간고사를 끝난 시점부터 교수님의 말씀을 참고해서 로드맵을 만들었습니다.  
일단 저희가 하는것은 웹툰 별로 적용사례를 추가하는것이아닌,  
틀을 만들어서 추후 크롤링 작업을 해서 데이터가 자동으로 들어가게 하는것입니다.
  
  
## main roadmap
![미디어 믹스 로드맵](https://user-images.githubusercontent.com/101037541/166185780-8666269c-2c43-4c22-a306-12ec942fcdf0.png)
<details>
<summary>1. 스키마 이해</summary>
<div markdown="1">       

    스키마는 데이터를 저장하기위한 틀인것 같습니다. 향후 작업을 위해 스키마에 대한 이해는 필수라고 생각하여 첫번째로 추가했습니다.
    잘 정리하여 Wiki에 올리면 좋을것 같습니다.

</div>
</details>

<details>
<summary>2. 이슈에 올라온 arrows 적용 사례 정리</summary>
<div markdown="1">       

    현재 방향이 데이터의 틀을 만들어 추후 크롤링한 데이터를 잘 넣어지게 하는것이 목표입니다.
    따라서 이슈에 올라온 웹툰 별로 실제 적용한 것들이 사용 안될 가능성이 큽니다. 
    하지만 다르게 사용 될 경우를 고려해 이슈에 올라온 arrows 자료들을 정리하는 것이 좋을것 같습니다. 

  
</div>
</details>

<details>
<summary>3. 모든 노드 통합</summary>
<div markdown="1">       

    PDF자료_arrows폴더에 저장된 모든 파일을 하나의 파일로 합치는 과정이 필요합니다. 
    최대한 모든 사람이 보기 쉽도록 가시성을 중시해서 만드시면 좋을것 같습니다.


</div>
</details>

<details>
<summary>4. 노드 수정(스키마 적용)</summary>
<div markdown="1">       

    a) 스키마를 이해한대로 데이터 틀을 제대로 만들어야합니다.
    b) 연결 관계 적기, 데이터를 넣을때 관계를 보고 넣기 때문에 이과정이 필요할듯합니다.
    c) 매화 추가되는 내용 넣을수있게 설계, 이것은 교수님이 언급하신 부분으로 하면 좋을것 같습니다.
</div>
</details>

<details>
<summary>5. 노드 확장(진출 가능한 영역추가)</summary>
<div markdown="1">       

    통합된 노드에서 추가적으로 확장 가능한 영역이 있다면 추가해주시면 감사하겠습니다. 
    ex) 웹툰 → 무대화

</div>
</details>

<details>
<summary>6. (추후) 크롤링, 적용되는지 확인, neo4j확장</summary>
<div markdown="1">       

    이부분은 neo4j만 하면 될것 같습니다. 크롤링은 안해도 될 것 같습니다. 
    하지만 이 프로젝트를 우리가 진짜 한다고 생각하며 하는것도 좋을것같습니다.
</div>
</details>


## sub roadmap
![Knight · SlidesCarnival의 사본](https://user-images.githubusercontent.com/100738390/166186953-ae19a469-4fba-4137-98d2-c7e9e6d757cd.png)

<details>
<summary>1. Neo4j</summary>
<div markdown="1">       

    저희가 하려하는 프로젝트는 최종적으로 Neo4j를 이용하여 구현됩니다. 하지만 Neo4j는 많은 명령어들이 있고, 시스템 또한 한눈에 알기는 어렵습니다.
    때문에, Neo4j의 기능과 명령어들을 대략적이라도 습득하는 것이 우선되어야합니다.
  
</div>
</details>

<details>
<summary>2. Community Standards</summary>
<div markdown="1">       

    Repository>Insights>Community Standards로 들어가시면 여러가지 Checklist가 있습니다.
    작성 기준(2022.05.02)으로, README,License만이 추가되어 있습니다. 
    Description, Code of Conduct, Contributing, Issue templates, Pull request template을 추가하시면 됩니다.
    예를 들어, Pull request를 할 때 필요한 내용들을 양식으로 만들어서 Pull request template을 만들어 주시면 됩니다.
  
</div>
</details>


<details>
<summary>3. Wiki 정리</summary>
<div markdown="1">       

    현재 Wiki는 Home에만 너무 많은 정보가 몰려 있습니다. 이는 가독성을 떨어뜨려 Wiki의 제 역할을 못하게 합니다.
    New Page 기능을 사용하여, 분류가 필요하다고 생각합니다.
    예를 들어 RDF,LPG에 관한 내용은 새로 페이지를 만드는 것이 좋을 것 같고, 
    이 둘의 차이점도 중요하기 때문에 보이게 작성해주시면 좋을 것 같습니다.

</div>
</details>

<details>
<summary>4. Projects</summary>
<div markdown="1">       

    이 단계는 필수적인 절차는 아니지만, Repository의 Projects기능을 사용하면,
    많은 사람들이 한 번에 프로젝트의 진행 상황을 알 수 있을 것 입니다.
    to-do 리스트와 기능이 비슷한 것 같습니다.

</div>
</details>

<details>
<summary>5. Readme 꾸미기</summary>
<div markdown="1">       

    현재 Readme는 내용의 큰 문제는 없지만, 사진,그림 등이 없어 가시성이 떨어집니다.
    저희의 프로젝트를 한 눈에 알 수 있는 이미지가 있으면 좋을 것 같아 제안해봅니다.

</div>
</details>
