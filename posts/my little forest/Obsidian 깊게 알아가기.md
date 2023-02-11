# 새롭게 알게 된 점들

### Link to a heading
특정 메모의 특정 헤딩에 링크하려면 [[Obsidian Tutorial#5/6 : 8 Hotkeys You Need]]  메모 제목의 끝에 해시태그 표시를 하고 원하는 헤딩을 선택하면 된다. 
헤딩이 하위레벨을 가지고 있으면 또 해시태그를 붙여서 선택가능하다, 이렇게...
[[Obsidian Tutorial#5/6 : 8 Hotkeys You Need#하위제목]]


### Link to a block in a note
특정 블럭을 링크하고 싶으면 링크를 거는 노트 제목끝에 해시태그와 캐럿(^)을 붙인다. 이렇게..
[[Obsidian Tutorial#^cb1458]]
자동으로 블럭 identifier가 추가된다.
블럭에 이름을 정해주고 링크하고 싶으면 원하는 블럭 끝에다 blank^quote-name 으로 지정한 후에 해당 블럭명을 선택해도 된다 : [[Obsidian Tutorial#^quote-named-by-me]]





# 궁금한 점들

### 회사와 집의 컴에서 모두 작업할 수 있는 방법은?
--> 구글 드라이브 이용해서 성공함! [[Synchronization]]

### quote이름을 바꿀때 관련된 모든 내용이 씽크되는 방법은?

### 외부 링크를 거는 방법
싱글 브래킷 안에는 보일 내용을, 바로 이어진 괄호안에는 링크 URL을 적으면 된다.
이렇게... [위키싱가포르](https://ko.wikipedia.org/wiki/%EC%8B%B1%EA%B0%80%ED%8F%AC%EB%A5%B4)

### 외부 소스를 노트 안에 넣는 방법
다음과 같은 방법으로 하면 된다.  (실제 소스는 편집모드가 아닐때는 안보이므로 눈에 보이도록 각 글자마다 블랭크를 넣음)
< i f r a m e   s r c = "INSERT YOUR URL HERE" > < / i f r a m e >
만일 위키 싱가포르 페이지를 넣고 싶다면..
<iframe src="https://ko.wikipedia.org/wiki/%EC%8B%B1%EA%B0%80%ED%8F%AC%EB%A5%B4"></iframe>

여러 가지 attribute를 원하는 크기,방식을 정할 수도 있다.
name, width/height, sandbox 등의 attribute 사용가능
<iframe src="https://ko.wikipedia.org/wiki/%EC%8B%B1%EA%B0%80%ED%8F%AC%EB%A5%B4" name="싱가포르" width="500px" height="100px" sandbox="allow-presentation"></iframe>


### 깃허브를 이용하여 퍼블리시하기
두 가지 템플릿을 테스트 했는데, 간단버전 (Jekyll 템플릿) 은 심플해서 보기 좋긴 했지만, 나중에 복잡해지면 너무 체계가 없을 것 같아서 기존 블로그와 좀더 비슷한 포맷의 MindStone 템플릿을 사용하기로 했다.
Netlify라는 클라우드 서비스를 이용해서 퍼블리시 했다. 
현재 구글 드라이브로 연동되는 폴더를 다시 깃허브에 연동시켜서 수정 내용을 퍼블리시하는 방법을 시험 중이다.
자세한 내용은 여기서..[[깃허브를 이용해 퍼블리시하기]]

#옵시디언사용팁 