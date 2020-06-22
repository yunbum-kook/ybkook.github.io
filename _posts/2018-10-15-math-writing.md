---
title: '수학적 글쓰기에서의 문법 (원제: The Grammar According to West)'
date: 2018-10-15
permalink: /translation/math_writing
tags:
  - Douglas West
  - Mathematical Writing
---



**Original Article**: [Article](https://faculty.math.illinois.edu/~west/grammar.html) written by Douglas B. West

**Comment**: UIUC의 수학과 Douglas B. West 교수님께서 학생들의 수학 기술법을 오랜기간 관찰하며 기록한 "흔한 오류와 실수" 를 정리한 글입니다. 수학 풀이를 쓰거나 논문을 쓸 때도 자주 발견되는 실수라고 하니 참고하시면 좋을 거 같습니다. 상당히 긴 관계로 총 92개의 항목 중 일부분만 발췌해서 번역했습니다.

**Last Update**: Jun 21, 2020 (70 out of 92; the rest will be supplemented and polished on a regular basis)

* * *

__목차__


[수학적 형식 (1~27)](#mathematical-style-수학적-형식)  
[용어/표기법 (28~57)](#terminologynotation-용어표기법)  
[영어 사용 (58~81)](#english-usage-in-mathematical-writing-수학적-글쓰기에서-영어-사용)  
[비원어민을 위해 (82~92)](#mathematical-english-for-non-native-speakers-비원어민을-위한-수학적-영어)




## Mathematical Style (수학적 형식)

### 1. Abstract, Introduction, and Conclusion (초록, 도입부, 그리고 결론)

수학논문의 전반적인 구조와 함께 시작해보자. Abstract (초록) 은 간결한 선에서 가능한 많은 결과를 기술해야 한다. 이해에 있어 중요한 전문 용어들은 정의를 해줘야 한다. 특히 초록이 논문의 나머지로부터 떨어져나와 있을 수 있는 요즘 같은 시대엔, 초록은 그 자체로써 이해될 수 있어야 하며 따라서 ([2] 같이) 숫자가 매겨진 인용의 형태를 배제해야 한다.

논문의 첫 파트는 Introduction (도입부) 인데, 해당 파트는 다루고 있는 문제의 흥미를 끌고, 관련된 결과를 다루며, 초록에 언급된 결과들을 좀 더 완벽히 기술하고, 어쩌면 테크닉 혹은 논문의 구조 혹은 중요한 정의들을 정리할 수도 있겠다.

또한 도입부는 모든 "마무리 짓는 말, 마지막으로 짚고 넘어가는 말" 혹은 "핵심 추측"등을 포함해야한다. 일반적으로 마무리 짓는 말이 독립된 파트로 존재할 땐 그닥 의미가 없다. 그러한 형태의 마무리 짓는 말들은 오히려 장황함을 주거나 독자들이 도입부에서 주로 찾고자 하는 정보들을 포함하고 있다. 증명의 모든 세부사항들을 공부하는 독자들은 마지막 파트에 있는 요약문이 필요가 없고, 그렇지 않은 독자들은 굳이 마지막 파트로 갈 생각이 없다. 수학 연구 논문들은 독자들을 ‘설득’하려는 수필이나 소설처럼 읽히지 않는다. 즉, 에필로그가 필요없다는 것이다.

### 2. Definitions (정의)

정의되는 단어들은 이탤릭체나 볼드체로 구별되어야 한다. 이탤릭체가 사용될 때는 “called”나 “said to be”을 쓸 필요가 없다. 왜냐면 이탤릭체의 사용 자체가 해당 단어가 지금 정의되고 있다는 것을 알려주기 때문이다.

정의들은 “어떤 조건이 성립될 때, 어떤 대상들은 ‘이탤릭체(정의되는 단어)’라는 특징을 가진다”의 형태로 기술된다. 비록 "어떤 대상이 정의되고 있는 특징을 가진다는 것"과 "어떤 조건이 성립한다"는 건 필요충분조건 (if and only if) 으로 받아들여지긴 하지만, 그냥 필요조건 (if)만 쓴다. 이탤릭체는 독자들에게 이러한 상황을 알려준다.

영어가 모국어가 아닌 사람들이 기술하는 정의들은 때때로 필요없는 쉼표 (comma) 를 가지고 있다. 예를 들면 아래 문장들에서 쉼표는 생략돼야 한다.

"A _bipartite graph_, is a graph that is 2-colorable" (X)  
"A graph is _bipartite_, if it is 2-colorable" (X)

또한 위 문장에서 이탤릭체 적용의 차이를 주목하라. 형용사-명사 조합으로 쓰일 땐, 정의되고 있는 용어가 그러한 특징을 가지는 구조를 위한 이름이기에 bipartite graph 통채로 이탤릭체로 쓰여야 한다. 특징 그 자체가 (bipartite) 정의되고 술어 형용사 형태로 쓰일 땐, 오직 그 형용사만 이탤릭체로 쓰여야 한다.

### 3. Where

수식은 아직 정의되지 않은 표기법을 포함할 수도 있는데, 이는 해당 표기법의 정의가 수식을 뒤따라 (같은 문장안에) 나오는 경우만 가능하다. 여기서 수식을 쓰고 쉼표를 사용한 뒤 "where"를 사용해 정의를 소개하면 된다. 예를 들면, "If G is a bipartite graph, then χ'(G)≤Δ(G), where χ'(G) is the edge-chromatic number and Δ(G) is the maximum degree of G."와 같다.

“where”과 “such that”의 차이를 주의할 필요가 있는데 “where”은 앞선 표기법이 정의될 때 사용되고, “such that”은 이미 그 표기법이 정의되어 있고 그 표기법의 값을 제한시킬 때 사용한다.

(*예*: the set of all *p/q* such that *q=2* and *p* is an integer)

### 4. Double-Duty Definitions (두 가지 역할을 하는 정의)

어떤 대상이 정의되기 전까진 그 대상에 관한 기술을 할 수 없다. 비슷한 이치로, 표기법이 이전에 정의된 게 아니라면 (그 표기법이 의미하는) 대상에 관한 기술을 하는 수식의 일부에 표기법이 등장할 수 없다. 예를 들면, "The _neighborhood_ of a vertex _v_ is _N(v)={u : uv ∈ E(G)}_"는 부정확한 문장이다. 수식 이전에 등장한 주어 (The neighbor ~) 와 동사 (is)와 함께, 수식은 하나의 단위다. 예시로 든 문장은 _v_ 의 neighborhood를 특정한 수식으로써 정의하고 있지만 *N(v)* 에 관한 정의는 하지 않고 있다.

물론 문맥에 충분히 익숙한 독자들이라면 _N(v)_ 의 의미를 이해하는데 전혀 문제가 없겠으나, 왜 다른 독자들을 힘들게 해야하는가? 그냥 The _neighborhood_ of a vertex _v_, denoted _N(v)_, is _{u: uv∈ E(G)}",_ 혹은 "The _neighborhood_ _N(v)_ of a vertex _v_ is _{u: uv∈ E(G)}_"처럼 용어가 정의된 바로 다음 위치에 쓰면 된다.

널리 쓰이는 두 가지 역할의 정의는 "Let _G=(V, E)_ be a graph"다. 해당 문장은 _G=(V, E)_ 를 그래프로 정의하고 있다. 물론, 저자는 그래프에 대한 표기법과 노드 집합과 연결 집합을 동시에 소개할 의도를 가졌다. 하지만, "Let _G_ be a graph"로 쓴 후에 _V_ 와 _E_ 를 사용해 그래프의 노드 집합과 연결집합을 _V(G)_ 와 _E(G)_ 로 쓰는게 낫다.

좀 더 미묘한 예로는 "For each _1≤ i≤ n_"가 있다. i가 정의되기 전 에 부등식이 조건을 걸어버렸기 때문에 (주: each _i_ 로 한정짓기 전에 _1≤ i≤ n_ 가 등장해버려서), 표기법 _i_ 의 도입은 길을 잃은 셈이다. 수식은 하나의 단위기 때문에, 해당 문장은 문법적으로 각각의 부등식을 가르키게 된다. 원래 의도를 포함한 올바른 문장은 "For all _i_ such that _1≤i≤n_", "For _i∈[n]_", 그리고 "For _1≤i≤n_"등이 있다.

### 6. Separation of formulas (수식의 분리)

두 개의 수식을 콤마를 사용해 붙여쓰는 것을 피하라. 예를 들자면 “For x<0, _x²>0_”나 “For some _k_ with _k<n_, _n-k+f(n)<n/2_”의 경우에 가정인지 결론인지 헷갈릴 수도 있고 독자들로 하여금 읽는 도중 앞으로 다시 돌아가게 할 수도 있다. 단지 쉼표 뿐만 아니라 독자들의 이해를 돕는 말을 추가로 적어주는게 좋다. 예를 들자면 “it follows that”이나 “we have”등이 있다.

[반면에, "we have"는 수식을 분리하기 위함이 아닐 땐 생략돼야 할 어색한 구문이다. 예를 들면, "By the preceding theorem, we have A= B" 대신에 "By the preceding theorem, A=B"가 선호된다.]

예를 들면
"When _k=2_, _G_ is Eulerian.” → “When _k=2_, the graph _G_ is Eulerian"
"For every bipartite graph _G_, _χ(G)≤2_" → “If _G_ is bipartite, then _χ(G)≤2_".

### 7. Initial notation (표기법으로 시작하는 문장)

절대 문장을 표기법으로 시작하지 말라. “_G_ is” 대신 “The graph _G_ is”와 같이 구체적으로 기술하거나 표기법으로 시작하는 것을 피하기 위해 다른 방식으로 기술하자. 이 규칙으로 하여금 논문 속 수학이 더욱 쉽게 읽힐 수 있다. 이 목차의 원리는 6번의 '수식의 분리'와 유사하다.

### 8. Lists of size (두 개의 대상으로 이루어진 리스트)

"Let _x, y_ be vertices in _G_"라고 흔히들 쓰지만 문법적으로 어긋나있다. "My friends John, Mary came to dinner." 같이 쓰지 않듯 말이다. 일반적으로, 두 개의 대상으로 이루어진 리스트 안의 쉼표는 그 두 개 대상의 각각에 대해 논할 땐 “and”로 바뀌어야 한다. 예를 들어 “If _x, y_ are adjacent”는 “If _x_ and _y_ are adjacent” 혹은 “If _{x, y}_ is a pair of adjacent vertices”로 적혀야 한다.

_예외_: 최소 3개 이상으로 이뤄진 리스트에 대해선, “and”의 생략이 큰 혼동을 주진 않고 오히려 포함시키는게 어색하다. “Let *x, y*, and *z* be the vertices”가 잘 읽히긴 하지만, “Let *x, y, z* be the vertices of *T*”또한 괜찮다.

또 다른 예외는 “Choose *x, y ∈ V(G)*”다. 여기서 포함 관계는 각 변수와 노드 셋 *V(G)* 사이에 있고, 이런 것들을 하나의 수식으로써 받아들인다. 하지만 등호 (=) 에 대해 사용하는 건 피해야 하는데, 이는 독자들로 하여금 이해하기 위해 불필요한 머뭇거림을 야기한다.

### 9. Parenthetic or wordless restrictions (괄호를 통한 조건)

수학을 표현하는 많은 저자들은 쉼표를 통해서 혹은 괄호를 사용해 조건을 부여하면서 추가적인 설명들을 생략한다. 이런 것들은 읽기를 어렵게 만든다. 표기법을 감싸는 괄호는 수학적 대상이기 때문에 단어를 대체할 수 없다. "Let _m(m≤n)_ be the size" 같은 문장은 오로지 저자에게만 쉽게 다가온다.

_다른 예시_:
"Suppose there is an edge _xy_ (≠*e*) in _G_" → "Suppose that _G_ has an edge _xy_ other than _e_".  
"For _k≤m_ (_k_ even)" 혹은 "For _k≤m_, _k_ even" → "For _k≤m_ with _k_ even"  
"Consider _a<sub>i</sub>_ (_1≤i≤n_)" → "Consider _a<sub>i</sub>_ for _1≤i≤n_"

### 10. Mixing words and notation (단어와 표기법을 섞는 행위)

단어들은 표기법과 관계기호로 비교될 수 없다. "Consider a graph _G_ with maximum degree _≤ k_"와 같이 쓰지 말라. 문법적으로 이런 문장은 부등호가 어디에 작용하는지 말해주지 않는다. 한 쪽이 단어들로 쓰인다면, 저러한 관계도 단어로 기술되어야 한다.

비슷한 원칙들이 논리기호에 적용된다. 단어들을 대체하기 위해 ∃, ∀, ⇒, iff 등을 쓰지 말라. 다만 렉쳐노트의 공간을 아끼기 위해 쓰인 축약된 표기법은 이러한 제한을 따를 필요는 없다.

### 11. Statements of implication (“Let… Then”)

흔히 쓰는 “Let _hypothesis_. Then _conclusion."_ 형태는 문법적으로 부정확하다. “Then”이 접속사의 역할을 하기 때문에 두번째 문장은 문장이 아니다. 더 간단한 형태의 “If _hypothesis_, then _conclusion_’.”가 더 읽기 쉽고 문법적으로 정확하며, 조건문이라는 수학적 센스에 더 부합하다. 가정이 많아 문장이 너무 길어지는 경우에는 약간의 창의성을 이용해, 가장 중요한 가정을 제외한 나머지 내용들을 Let 등으로 먼저 적은 뒤 남겨뒀던 가정을 if/then 구조로 적어주는 것이다.

“then”이란 단어가 문장 초반부에 쓰이면 “Then we left”에서와 같이 시간적 의미를 가지고 있다. 수학에선 then의 논리적 연역 성격이 더 일반적이기 때문에 저러한 시간적 의미로는 (혼란을 피하기 위해) 드물게 쓰여야 한다.

문장 앞에 쓰여 시간적 의미를 지니게 되는 then은 Now 혹은 Next로 바꿈으로써 혼동을 줄이고 특히 증명에서는 좀 더 정확한 의미를 전달할 수 있다.

한 문장 안에 “Let …, then …”을 쓰는 것도 비슷하게 문제가 있다.

### 12. Words of hypothesis: “If”, “When”, “For”, “Since” (가정을 위한 단어들)

쉽게 이해시키기 위해선 “If”로 시작한 문장은 추후에 “, then”으로써 결론을 지어야한다. 여기서 “then”은 생략해선 안 되고 쉼표는 then 앞에 써줘야 한다. “Since f is the squaring function, if _x=0_ then _f(x)=0_”에서와 같이 쉼표로 시작한 절 (if _x=0_ then _f(x)=0_) 에 있는 간단한 논리적 암시 구조에선 생략될 수 있다.

“then”을 생략함으로써 가독성이 개선될 수 있는 경우엔, 해당 문장은 “When” 혹은 “For”로 시작하는게 낫다. (주: If hypothesis, conclusion으로 썼을 때 가독성이 개선되는 거 같다면 차라리 When hypothesis, conclusion의 형태가 낫다는 것이다) 여기서 when과 for 절 이후에 쉼표는 여전히 쓰여져야 한다. “Since”로 시작하는 문장구조는 “When” 혹은 “For”로 시작하는 문장구조와 같다. 즉, 쉼표가 Since 절 이후에 등장해야 된다는 것이다. “Since” 혹은 “Because” 이후에 결과절(concluding clause)은 “then” 혹은 “so”로 시작할 수 없다. 즉, then은 오직 if와만 함께 쓰인다.

### 13. “As” and “For” introducing reasons (이유 설명을 위한 “As”와 “For”)

영어에서 “as”와 “for”는 결론절이 주어진 후 이유를 언급할 때 쓰인다. 예를 들면, "I ate early today, for I was hungry," or "He stopped writing his answer, as time had expired.”등이 있다. 특히 비원어민 독자들에게 혼란을 야기할 수 있기 때문에 수학적 글쓰기에선 이를 금지하자. “As”는 “like”와 유사한 의미로 쓰이기도 하고, “for”는 영역을 특정하기 위해 가장 자주 쓰인다. 다음 두 문장을 비교해보라. "The degree is at least one, for a vertex in the neighborhood" & "The degree is at least one, for a vertex in the neighborhood is not isolated.”. 여기서 “for”의 의미는 다르지만 독자들은 문장이 끝날 때까지 차이를 알 수 없다.

### 14. Words of conclusion : Hence, Thus, Therefore (결론을 위한 단어)

결론을 기술할 때 문장을 시작할 단어들이 필요한데 위 세 가지 단어들이 쓰일 수 있다. 나는 이 중에서 Therefore을 가장 형식적으로 여기는데, 주요 결과를 소개할 때 사용하며 쉼표와 함께 쓴다. Hence나 Thus는 한 음절이라서 글이 너무 끊기지 않게끔 쉼표 없이 논증의 흐름을 나타내기 위해 쓴다.

### 15. By theorem X (정리 X에 의해)

"Since _G_ has at least _3n-5_ edges, by Theorem X, we know that _G_ is not planar."란 문장을 살펴보자. 여기서 정리 X에 의해 앞 조건이 성립한다는 것인가 혹은 뒤의 결론이 성립한다는 것인가? 독자들은 저자의 의도를 알 수 없기때문에, “by theorem X”는 명확한 의미표시 없이는 절대 이유와 결론 사이에 놓여선 안 된다. 쉼표를 생략하는게 더 분명해지기도 한다: "Since _G_ has at least _3n-5_ edges, by Theorem X we know that _G_ is not planar" 혹은 "Since _G_ has at least _3n-5_ edges by Theorem X, we know that _G_ is not planar". 하지만 2번째 대안은 “By theorem X, _G_ has at least _3n-5_ edges, and therefore _G_ is not planar.” 로 쓰는게 낫다.

### 16. "So" and "So that"

“So”는 다른 의미로도 쓰일 수 있기 때문에, 결론 문장을 시작하기엔 너무 비형식적이다. “But”과 같이 “So”는 접속사로써 쓰는게 가장 좋다. 또한 접속사로써 쓰일 때, so앞엔 semicolon이 아닌 쉼표가 와야한다. So를 활용한 문장형태는 결론이 짧은 경우에 잘 쓰인다: “The graph has no odd cycles, so it is bipartite”. 그리고 so가 접속사로 쓰인 경우 that을 붙이지 말라. 따라서 “We have _x²=0_, so that _x=0_.” 는 “We have _x²=0_, so _x=0_.”가 돼야한다.

### 17. "Such that" vs "So that"

“So that”은 “in such a way that”을 의미한다. “Such that”은 어떤 대상에 조건을 부과할 때 사용하고 “So that”은 특정한 방식으로 행위를 취할 때 사용하라. 즉, so that은 동사를 필요로 하고 그 행위가 어떻게 되는지 기술한다. 반면 such that은 명사에 조건을 건다.

"Consider a graph such that no vertex is isolated"와 "Color the graph so that no two adjacent vertices have the same color"을 비교해보라. such that 이후의 내용은 앞선 그래프 (명사) 를 수식하지만, so that 이후의 내용은 coloring (동사) 이 어떤 식으로 행해지는지 설명한다.

### 18. Assume, Suppose, and Let

Assume되는 서술은 전반에 걸쳐 참이라고 여겨지는 공리다. Suppose되는 것은 가정이다. 따라서 suppose나 suppose that은 귀류법 등을 시작함에 있어 더욱 적합하다. 반면 we may assume은 논증이나 대칭성에 (따라 앞으로 참이 될) 결론을 도입한다. “Assume for a contradiction that” 대신에 “Suppose to the contrary that”을 쓰고 “By way of contradiction” 대신엔 “Toward a contradiction, suppose that”을 쓰자.

“Suppose” vs “Suppose that” : 가정 혹은 결론의 단어들 뒤에는, 뒤따르는 것이 동사를 동반한 clause(절)이면 that을 붙이고, 뒤따르는 것이 그냥 명사일 경우 that을 생략한다. 예를 들면 “Suppose _x+y<10_”과 “Suppose that f is a proper coloring”이 있다. 하지만 이 차이는 관계 기호(relational symbol)을 동사로 여기느냐 명사로 여기느냐에 따라 다소 논쟁의 여지가 있다. 이런 애매한 상황을 위한 해결책은 “Suppose _G_ is a graph”보다 “Let _G_ be a graph”를 쓰는 것이다.

### 19. Universal quantifiers (보편 양화사)

다양한 상황에서 any란 단어는 some(어떤)과 all(모든) 모두를 뜻할 수 있기 때문에 부정확할 수 있다. 하나의 대상을 일컫을 땐 each 혹은 every를 보편 양화사로 사용하는게 더 명확하다. any의 사용을 피하는 게 필수는 아니다. 오해를 일으키지 않는지 확인하며 현재 문맥에서의 any의 쓰임을 평가하라.

부정관사(a, an)을 보편 양화사로 사용하는 것은 다음과 같이 꽤 위험할 수도 있다: "Prove that a bipartite graph has no odd cycle." 몇몇 독자들(주로 학생들)은"a"를 "하나" 혹은 "몇몇"으로 해석하고, 보편성을 존재성으로 바꿔버릴 수도 있다. every를 사용하는게 더 명확하다. 결론 전에 must는 보편성을 의미할 수도 있으나 주로 불필요하다.

### 20. Position of universal quantifiers (보편 양화사의 위치)

논리 수식에선, 수식이 성립하는 조건을 구체화하는 양화사는 수식 전에 놓인다. 말로 풀어쓸 땐, 하나의 보편 양화사는 마지막에 위치하면 더 쉽게 읽힐 수 있다. 또한 이런 순서는 결론을 강조하기도 한다. 예를 들어 "For every graph _G_ that is bipartite, _χ(G)≤2_"보단 "Always _χ(G)≤2_ when _G_ is bipartite"로, 그리고 "for _1≤i≤n, a<sub>i</sub>∈S_"보단 "_a<sub>i</sub>∈S_ for _1≤i≤n_"가 낫다.

### 21. "Less" vs "Fewer"

숫자를 비교할 때 less를 쓰고 객체의 집합을 일컫을 때 fewer를 사용하라. 예를 들어 "the number of edges is less than _k_", "the graph has fewer than _k_ edges", "_G'_ has fewer edges than _G_".처럼 말이다.

### 23. "Estimate"

많은 수학자들은 "estimate"란 단어를 "bound"의 의미를 생각하고 사용한다. 실제론 "now we prove an upper bound on this quantity"를 의미할 때 "now we estimate this quantity"로 쓰는 식으로 말이다. 영어에선 estimate는 approximate(근사하다)를 의미한다.

### 24. Possessives on notation (표기법의 소유격)

“Let _x_ and _y_ be _v_’s neighbors”라 쓰지 말자. 대신에 항상 “of” (the neighbors of _v_)를 사용해라. 또한 “the _a<sub>i</sub>_’s” 대신에 주로 each _a<sub>i</sub>_" 혹은 "_a<sub>1</sub>, …, a<sub>n</sub>_"가 더 선호된다. 표기법의 소유격 혹은 복수형태는 비형식적인 구두 소통에서 쓰여야 한다.

### 25. Nested proofs (증명 안의 증명)

증명 안에 또 다른 증명을 넣지 말라. 현재 증명이 끝나기 전까지 새로운 증명환경이 들어서선 안 된다.

### 27. Numerals and spelled numbers (숫자와 풀어쓰기)

표준적인 영어 쓰기에선 10 미만의 숫자는 철자를 모두 풀어쓰고 (2 → two), 10 이상은 숫자로 쓴다. 수학적 글쓰기에선 이러한 구분 짓는 기준이 다르다. 10 미만의 숫자는 객체의 수량을 나타내는 형용사로 쓰일 때만 풀어쓴다. 어떤 양이 가지는 값을 지정할 땐 숫자로 남아있어야 한다.

_예시_:
"The two vertices both have degree 3"  
"A cycle of length 4 has four edges"  
"Consider a 4-vertex path"  
"Consider a path with four vertices"

  

## Terminology/Notation (용어/표기법)

### 28. Definition symbol ":=" (정의 기호)

이런 어색한 기호는 결코 필요하지 않고 문법적 오류를 범하기 쉽다. 몇몇 수학자들은 이 기호를 사용해 기호 이전의 수식을 기호 이후의 수식으로 정의하기 위해 사용한다. 만약 이 기호가 "Let _[n]:={1,…,n}_” 같은 문장에서 쓰인다면 동사 자체가 표기법 _[n]_ 가 정의되고 있음을 의미하기에 정의기호는 필요치 않다. 만약 "Consider a coloring of _[n]:={1,…,n}_” 같은 문장에서 쓰인다면 다음과 같이 새로 쓰여야한다: "Consider a coloring of _[n]_, where _[n]={1,…,n}_”.

### 29. “Such that” in set definitions: “:” vs “|” (집합 정의안의 조건기호)

많은 이유로 “:”가 “\|”보다 좋은 선택이다. “\|”는 수학에서 이미 많은 용도(집합의 크기, 나눔 기호)로 쓰이고 있다. 또한 Latex 환경에서 단순히 “:”가 아닌 “\colon\\,”으로 써야 한다.

### 30. Sequences, series, and lists

수학에서 sequence란 정의역이 자연수인 함수다. 이산 수학자들은 이 용어를 순서가 있는 유한 집합을 위해 남용하기도 한다. 이러한 대상을 위한 좋은 이름은 바로 list다. _n_-tuple은 길이가 _n_ 인 list다. 길이 _n_ 인 sequence라고 하는 건 용어의 남용이다.

영어에서의 series는 수학에서의 쓰임새와 정반대다. 영어에서 series란 “World Series” 혹은 “A Series of Unfortunate Events”와 같이 유한한 사건으로 구성되지만, 수학에선 급수 (infinite series)이다.

### 31. The second element of a list (목록의 두번째 원소)

"_v<sub>1</sub>,v<sub>2</sub>,…,v<sub>n</sub>_"란 표현은 원소들이 첫 _n_ 개의 자연수들로 색인됐다는 것을 나타내기 위함이다. 하지만 두 번째 원소를 생략해도 의미는 같기 때문에 두 번째 원소는 필요치 않다. 관습상 리스트안에 색인들은 따로 기술하지 않는 이상 연속하다. 또한 "_v<sub>1</sub>,v<sub>2</sub>,…,v<sub>n</sub>_” 같은 표현은 _n=1_ 인 경우를 제거하기도 한다.

### 32. A list with relations (관계를 가지는 목록)

"Let _x<sub>1</sub>≤…≤x<sub>n</sub>_ be a list of integers"란 문장에서 저자는 (1) 목록의 원소를 도입하고, (2) 원소들 간에 부등식 관계를 부여할 의도였을 것이다. "Let _x<sub>1</sub>≤…≤x<sub>n</sub>_ be integers such that _x<sub>1</sub>≤…≤x<sub>n</sub>_."로 쓰거나 중복을 줄이기 위해서 "Let _x<sub>1</sub>,…,x<sub>n</sub>_ be integers, indexed in nondecreasing order."로 쓰자.

### 33. Variable equal to list (변수를 목록으로 설정)

많은 수학자들이 "for _m ∈ {1,…,n}_" 혹은 “for _1≤ m≤ n_”를 위해 "for _m=1,2,…,n_”와 같이 쓴다. "for _m=1,2,…,n_” 같은 표현은 _m_ 의 값을 숫자의 목록(a list of numbers)으로 설정하기 때문에 수학적으로 틀렸다.

### 38. Two-word adjectives (복합형용사)

두 개의 단어가 합쳐진 복합단어는 명사 전에 위치하는 경우 하이픈(-)으로 연결되어야 한다. 특히 “vertex-transitive” 같이 첫번째 단어가 명사일 때 특히나 필수적이다. 흔한 오류는 “polynomial time algorithm”인데 여기처럼 형용사로 쓰이면“polynomial-time”같이 쓰여야한다. 반면 해당 표현이 다른 것을 수식하는 게 아니면 하이픈은 생략된다: "The algorithm runs in polynomial time".

_추가적 예시_: "graph-theoretic techniques", "straight-line drawing"

### 39. Adverbs and “well-known” (부사와 "well-known")

명사 혹은 형용사와 다르게 부사는 형용사를 수식할 수 있다. 따라서 하이픈 없이 "strongly connected digraph" and "simply connected region”와 같이 쓸 수 있다.

부사 “well”은 가능성 있는 예외다. 우리는 “well-known theorem”에서 “well-known”이란 조합을 하나의 특수한 용어로 생각한다. “well-defined”도 같은 식으로 쓰인다.

### 45. “Maximal” vs “maximum”

많은 수학자들이 두 단어를 바꿔가며 쓰곤 한다. Maximum은 숫자나 크기를 비교할 때 쓰고 maximal은 집합이나 다른 대상을 비교할 때 쓰면 두 개를 유용하게 구분지을 수 있다.

이러한 구분한 납득가능하고 많은 상황(_예_: maximum antichain, maximum independent set)에서 정립됐지만 혹시 있을 지 모른 혼동은 “largest”와 “smallest” 를 사용함으로써 방지할 수 있다.

### 47. “Induct on” and “By induction”

“We induct on n”란 표현은 편리하지만 옳진 않다. 주어진 가정으로부터, 우리는 결론을 연역(deduce)한다. 즉, deduct하는 것이 아니다. 귀납법(the method of induction)을 사용할 때는, 반드시 “we use induction on n”라고 쓴다. 또한 귀납법 가정(induction hypothesis)을 언급할 때, “By induction”이 아닌 반드시 “By the induction hypothesis”라 써야한다.

### 52. "Pairwise" and "mutually"

구식 수학은 집합 안의 모든 쌍이 만족하는 이항관계(binary relation)를 표현하기 위해 구식 단어인 “mutually”를 사용한다. 현대 수학은 pairwise를 의미하기 위해 mutually을 사용하는 것을 피해야 한다.

### 56. Setminus (집합의 뺄셈)

Latex에서의 setminus 명령어는 집합의 뺄셈을 의미한다. 따라서 원소의 삭제를 표기하기 위해 해당 명령어를 사용하는 건 혼란을 주거나 다소 구식이다. “_G\setminus e_” 대신에 “_G-e_”를 사용하라.

### 57. “Left hand side” (좌변)

“hand side”란 표현은 없다. 설령 적절히 left-hand side로 하이픈을 사용하더라도 “hand”는 없다. 그냥 “left side”로 쓰라.

  

##  English usage in mathematical writing (수학적 글쓰기에서 영어 사용)

### 58. Introductory words (도입부 단어)

"nevertheless", "for example", "to the contrary", "on the other hand"와 같은 단어 혹은 구문들은 문장의 나머지 부분과 쉼표로 분리되어야 한다.

### 60. "which" vs "that"

다음 두 문장은 다른 의미를 가진다.

a) "She will attend our meetings that concern calculus."  
b) "She will attend our meetings, which concern calculus."

문장 a는 여러 미팅 중 그녀는 미적분학 관련 미팅만 참여하고 아마 나머지는 참여하지 않느다는 의미를 가진다. 문장 b는 모든 미팅은 미적분학과 관련이 있고 그녀는 모든 미팅을 참여한다는 것이다. 일상 영어에서 이 차이는 더욱 명확하다.

a) "I have two shirts that need cleaning." (내 2개의 셔츠가 세탁이 필요)
b) "I have two shirts, which need cleaning." (나는 오직 2개의 셔츠만 가지고 있음)

관계대명사 후의 구절이 다뤄지고 있는 종류에 대해 추가적 제한을 구체화하는 경우, 정확한 대명사는 "that"이고 that 후에 따라오는 구절은 그 종류 중 어떤 대상이 다뤄지고 있는지를 알려준다. 만약 추후의 구절이 종류의 전체에 대해 다루고 있다면 "which"를 사용해야 된다. that과 which 모두 사용가능해 보인다면, "어떤 특징을 가지는"을 의미하기 위해서 that을 쓰고, "그것의 모든 것"을 일컫는다면 which를 쓰라. 대개 which 직전에 쉼표가 적절하다. 수식되는 단어에 부정관사 (a, an)이 쓰인다면 that이 주로 정확하다.

### 61. Immediacy of antecedents (관계대명사의 인접성)

뒤에 추가적 설명을 수반하는 which, that, where 혹은 다른 단어들을 사용할 때, 뒤따라오는 절은 가장 가까운 대상을 수식한다. 예를 들어 "an embedding of _G_ on a surface which has no crossings"는 "embedding이 crossing이 없음"이 아니라 "surface가 crossing이 없음"을 의미한다. Embedding에 적용되는 crossing에 대한 코멘트를 위해선 "On a specified surface, consider an embedding of _G_, which has no crossings"으로 써야한다. 여기서 "which"가 적합한 이유는 모든 embedding이 crossing이 없기 때문이다. (참고로 embedding이란 crossing이 없는 drawing을 뜻한다)

### 62. The naked "This" (명백한 This)

This가 문장의 주어로 사용될 때, this가 가리키는 대상은 가장 최근에 쓰인 명사다. 만약 의도한 대상이 이전의 문단이거나 다른 대상이라면 단순히 “This implies” 대신에 “This discussion implies” 혹은 “This inequality implies”로 쓰는 편이 좋다. 이 문제를 이해하는 또 다른 방식은 this를 대명사가 아닌 형용사로 생각하는 것이다.

### 63. "Every", "distinct", "unique"

every는 “각각의 하나에 대한”을 뜻하는 단수다. 따라서 “all values” 혹은 “every value”로 쓰지 “all value” 혹은 “every values”로 쓰지 않는다.

distinct는 different와 같은 의미를 지닌다. 두 개의 대상은 다를 수 있지만, 하나의 대상은 다를 수 없다. 따라서 “Every value is distinct”는 틀린 문장이다.

unique는 현재 기술하는 대상이 하나임을 듯한다. 이는 해당 대상이 다른 대상들과 다르다는 의미가 아니다. 어떤 학생들은 "The function f maps the points in A to unique points in B”가 _f_ 가 injective(단사함수)로 이해하는데 틀린 것이다. 이는 A의 모든 점을 B의 유일한 한 점으로 대응시킨다는 것이다.

distinct와 unique의 차이는 다음 문장을 통해서 이해될 수 있다. “Our website has one million unique visitors”는 말이 안 되는 문장이다. 문장의 의도는 수백만의 클릭 중 백 만명의 다른 방문자가 있다는 것이다. Unique 방문자가 있다는 것은 다른 방문자들이 없다는 것이다.

### 64. Contraction (축약)

수학적 글쓰기는 형식적이기에, can’t나 won’t 같은 축약어는 피해야 한다. 이런 단어들은 증명의 분위기와 어울리지 않는 약식(informality)을 야기한다.

### 65. “I.e.” vs “e.g.”

i.e.와 e.g.는 라틴어 구의 약자이다. i.e.는 that is를 뜻하고 직전에 언급했던 것을 재서술하거나 설명할 때 쓰인다. e.g는 “for example”을 뜻하고 예를 든다. 형식적인 수학적 글쓰기에선 약자는 축약과 같다. i.e.나 e.g. 같은 표현들은 피하는게 낫다. 덧붙이자면, that is나 for example가 i.e.나 e.g.보다 시각적 구별에 있어 낫다.

### 66. Different than

“A differs than B”라 적는 것은 옳지 않다. 비슷한 이유로 “A is different than B”라고 적어서도 안 된다. 정확한 표현법은 “A is different from B”이다.

### 67. Abstract nouns and articles (추상명사와 관사)

어떤 물체보다 추상적인 개념을 가르키는 명사는 관사를 필요로 하지 않는다. 예를 들어 graph colorability는 애매한 (막연한) 개념이기 때문에 “Next we discuss the graph colorability”라고 쓰지 않는다. 반면 chromatic number는 추상적일 수도 혹은 구체적일 수도 있다. 따라서 "Next we discuss chromatic number”로 사용해 일반적인 개념을 의미할 수도 있고, 혹은 graph가 chromatic number를 하나만 가지기 때문에 "Next we discuss the chromatic number of this graph”로 사용할 수도 있다.

함수 혹은 모수는 숫자를 각각의 정의역 대상에 부여한다. 부여된 결과값은 각각의 대상에 대해 고유하기 때문에 오직 하나의 선택지 밖에 없다. 따라서 "the graph has a chromatic number 3" 혹은 "the vertex has a degree 3" 같이 말하지 않는다. 앞선 문장들은 이런 대상이 한 개 이상의 값을 가질 수 있음을 의미한다. “What is the degree of this vertex? (이 꼭지점의 차수는 얼마인가?)”에 대한 답으로 “This vertex has degree 3 (이 꼭지점의 차수 3을 가진다)”는 가능하지만 “This vertex has a degree 3”은 불가능하다.

비록 "The degree of this vertex is 3”는 맞는 표현이지만 “This vertex has the degree 3”로 쓰진 않는다. 다음 문장 "Every graph has an even number of vertices with odd degree, which means that the list of vertex degrees has even sum.”을 살펴보자. 여기서 “even number”은 관사 an을 필요로 한다. 왜냐면 우리는 지금 ‘어떤 타입의 숫자가 쓰이는 지’에 대해 얘기하고 있기 때문이다. 뒷 부분의 “odd degree”와 “even sum”은 관사를 필요로 하지 않는데, 이는 꼭지점이나 목록이 만족시키거나 그러지 않은 ‘특성(조건)’들이기 때문에다. 특징을 상기시킬 땐 관사는 적합하지 않다.

또한 관사는 개념적 명사와 함께 쓰이지 않는다. 우리는 “This chair has value \\$100”라고 얘기하지 “This chair the value \\$100”라 하지 않는다. 여기서 “value”와 “degree”는 추상적 특징이다. 또 다른 예시로는 “I receive compensation for my work”라고 하지 "I receive a compensation for my work.”라 하지 않는다. 급여(compensation)는 수량이긴 하지만, 여기선 ‘급여를 받는다’는 추상적 개념만 의도됐다. 따라서 관사를 쓰지 않는다.

유사하게 추상적 성질 또한 관사를 필요로 하지 않는다. "because the transitivity of A implies the transitivity of B”가 아니라 "because transitivity of A implies transitivity of B”로 쓴다.

### 68. Possessives and titles (소유격과 제목)

정관사 the는 유일성을 명시한다. 소유격 또한 이러한 역할을 한다. 따라서 소유격과 the를 함께 쓰는건 부정확하다. 예를 들어 “the Greene’s Theorem”이 아닌 “Greene’s Theorem”로 쓴다.

두 저자의 결과를 논할 땐 각 저자에게 소유격을 붙일 수 없다. 따라서 “the Greene—Kleitman Theorem”으로 쓴다. 여기서 the는 “Greene--Kleitman Theorem”이란 제목을 가지는 유일한 대상을 위한 정관사 역할을 한다.

### 70. Adjectival forms of names (이름의 형용사 형태)

몇몇 그래프 이론학자들은 “Hamilton cycle”이라곤 하면서 결코 “Abel group”이라고 하진 않는다. 수식어는 형용사여야 하기 때문에 가능하다면 형용사 형태의 이름을 쓰는게 좋다: “Hamiltonian cycle”. 유사하게 “Euler circuit”이 아니라 “Eulerian circuit”이다. **하지만**, 몇 가지는 그 자체로써 오래 쓰여 바꾸기 어렵기도 하다: "Fibonacci numbers" and "Catalan numbers”.

### 71. Conjunctions and commas (접속사와 쉼표)

구두점을 문장을 형성하는데 특히 쉼표는 독자로 하여금 (그렇게 하는게 이해를 도울 때) 그 위치에서 잠시 멈추는 것을 장려한다. 생략된 쉼표는 독자들이 문장을 이해하기 위해 멈추고 다시 읽도록 할 수도 있다. 하지만 과도한 쉼표는 논리의 흐름을 방해한다.

두 개의 (완전한) 절은 접속사를 활용해 붙여 쓸 수 있는데, 접속사 앞엔 쉼표가 필요하다. 접속사의 예로는 and, but, the, so 등이 있다. 접속사는 두 개를 잇는 역할이기 때문에 문장은 접속사로 시작할 수 없다.

_예외_: 두번째 절이 접속사 자체를 포함하는 경우 상황은 복잡해진다. 다음 두 문장 "If A, then B holds and C holds”과 "If A, then B holds, and C holds”을 비교해보라. 첫번째 문장에선 A가 B와 C를 이끌어냄은 명확하다. 두번째 문장에선 의미가 불분명하다. 오직 하나의 쉼표 기호만 있고 그룹을 표시하기 위해 문장들을 괄호로 묶지 않기 때문에, 같은 그룹 내의 두 문장은 짧은 접속사는 쉼표 없이 쓰여야 한다.

### 72. Semicolons (;) (세미콜론)

복문(compound sentences)은 두 개의 완전한 문장이 두 개를 분리하는 접속사 없이 구성한다. 이러한 형태는 두번째 문장이 첫번째 문장을 부연설명할 때 주로 쓰인다. 이러한 복문은 두 부분을 분리하기 위해 쉼표가 아닌 세미콜론(;)이 필요하다. 접속사 전에 세미콜론을 사용하지 말라.

### 73. Excessive commas (과도한 쉼표)

절은 주어와 동사를 필요로 한다. and가 두 개의 불완전한 문장 (주어와 동사 모두를 가지고 있진 않음) 을 잇는 경우엔 and 전에 쉼표가 없는게 좋다. 따라서 "We will prove the lemma, and then the theorem”에서의 쉼표는 틀렸다. 쉼표를 지우거나 혹은 두번째 절에 주어와 동사를 추가해줘야 한다.

### 74. Serial commas (연달은 쉼표)

Serial comma (이하 sc) 는 목록의 맨 마지막에서 두번째 대상 (the next-to-last element) 뒤에 오는 쉼표다 (주: A, B, and C에서 B 직후의 쉼표를 의미). 위키피디아는 [sc의 사용](https://en.wikipedia.org/wiki/Serial_comma )에 대해 다루고 있다. 이런 상황에서 쉼표를 사용하는게 일반적으로 가장 안전하다. 예를 들어 다른 의미를 가지는 “Under the conditions _1≤ i, k≤ r_ and _m_ even”와 "Under the conditions _1≤ i, k≤ r_, and _m_ even”를 비교해보라.

### 75. Appositives (동격)

동격이란 앞선 혹은 뒤에 있는 명사 혹은 명사구를 대체하거나 설명하는 또 다른 명사 혹은 명사구다. 동격을 생략함으로써 더 깔끔하고 여전히 완전한 문장을 만들 수 있기도 하고, 그리고 동격 안의 추가정보가 문법적으로 필수적이진 않다는 특징을 가진다. 이러한 동격은 쉼표로 시작되어야 한다: "His book, the best book on the subject, took years to write”. 이 문장의 중간에 있는 동격은 한 쪽에만 (시작 혹은 끝 부분) 쉼표가 있어선 안 된다.

동격이 충분히 짧거나 본질적 의미를 가지는 경우 쉼표는 생략된다: “My friend Bob is a student”. 수학적 글쓰기에선 표기법을 소개할 때 비슷한 상황이 적용된다: "The _degree_ _d(v)_ of a vertex _v_ is the number of neighbors of _v_”. 여기서 _d(v)_ 는 간단한 동격이다.

### 76. Passive voice (수동태)

훌륭한 영어 작가는 수동태의 사용을 최소로 한다. 일반적으로 받아들여지는 이 원칙은 수학적 글쓰기에도 해당된다. 능동태는 설명을 더욱 매력적으로 만들어준다. 예를 들어 "It is sufficient to show”보다 "It suffices to show”가 낫다. 그럼에도 수동태의 신중한 사용 또한 적절하다.

### 77. "Above"와 "Below"

이 단어들은 부사고 명사로 직접적으로 수식하는 게 아니다. 따라서 “the above graph”와 “the below figure”는 부정확한 표현이다. “the graph shown above” 혹은 “the figure located below”의 축약형으로써 “the graph above” 혹은 “the figure below”로 쓸 수 있다.

### 78. "Either"

either이란 단어는 exclusive or (둘 중 하나만 성립) 을 뜻한다. 만약 정의 자체에 의해서 나머지 하나가 배제될 수 있다면 either이란 단어는 불필요하다.

### 79. “We have been proving”

조동사 have를 필요로 하는 완료형 시제를 쓰지 말라. “In Section 3 we have been analyzing” 혹은 “in [4] we had shown”같은 구문들은 문법적으로 틀렸거나 혼동을 준다. “In section 3 we analyzed” 혹은 “in [4] we show” 같은 단순 시제가 항상 대부분 낫다. 미래형도 배제할 수 있다. “in Section 4 we will show”보단 “in Section 4 we show”가 낫다. 이에 대한 이유는 전체 글을 하나의 단위로 보고 현재에 일어나는 것으로 인식하는 것이다)

### 80. Words containing “non” (non을 포함하는 단어)

영어에서 어떤 단어가 접두사 non에 의해 부정될 땐 하이픈을 중간에 넣어준다. 시간이 흐르면서 하이픈 된 단어가 그 자체로서 받아들여지며 “non”을 의미에 포함시켜 부정의 의미가 사라지게 된다. 이런 익숙함은 하이픈을 생략시킨다. 수학에서 그런 예로는 "nonsingular", "nontrivial", "nonzero", and "nonconstructive" 등이 있고, 여기에 하이픈을 넣는 것은 이제는 독자들에게 거슬린다.

### 81. Placement of citations (인용의 위치)

참고 문헌의 특정 대상을 가르키는 숫자 (주: [2] 같은 것) 는 언급하는 결과 문장의 뒤가 아닌 저자의 이름 뒤에 와야한다.

## Mathematical english for non-native speakers (비원어민을 위한 수학적 영어)

### 82. "Bound of"

많은 비원어민들은 "bound on"을 의미하고 싶을 때 "bound of"를 사용한다. _x≤ k_ 가 주어졌을 때 upper bound **of** _k_ **on** *x* 을 가지고 있는 셈이다. 여기서 "bound on *x*" 대신에 "bound of *x*"를 사용하면 모수를 비교할 때 혼동을 줄 수 있다.

### 83. "few" vs "a few"

"few"는 "많지 않은 (거의 없는)"을 의미하나 "a few"는 "여럿"을 뜻한다. "In this paper we prove few good results"란 문장은 이 페이퍼는 의미있는 걸 아무것도 하지 않았다는 것이다. 반면 "In this paper we prove a few good results"는 이 페이퍼는 읽을 가치가 있다는 것이다.

### 84. "Usual"

영어의 별난 점 중 하나가 형용사로써 usual이란 단어는 정관사인 the를 필요하다는 것이다. "In this section we consider only usual chromatic number" 대신에 "In this section we consider only the usual chromatic number"로 써야한다. (관사가 없는 언어를 사용하는 사람들의 흔한 실수다)

### 85. "Partial case"

영어에선 하나의 결과가 다른 결과의 "partial case"라고 하지 않는다. "special case"라고 한다. 하지만 추측의 special case를 증명한 것을 partial result라고 하는 것은 맞는 표현이다.

### 86. "Pass" vs "Pass through"

영어에선 "pass"란 단어는 "go by without entering (스쳐간다)"를 의미한다. 따라서 어떤 꼭지점을 pass하는 경로는 사실 그 꼭지점을 거치지 않는다는 것이다. 경로 _P_ 가 꼭지점 _v_ 를 거친다는 것은 "_P passes through v_"로 표현해아 한다.

### 87. "Can not"과 "may be"

"can not"은 영어에서 존재해선 안 되는 표현이다. "can not"의 논리적 의미는 반드시 실패한다기보단 실패할 수도 있다는 것이다. 반드시 실패한다는 것은 "cannot"의 의미다.

"may be"라는 표현은 다음과 같이 동사로 쓰일 때 영어에선 존재하지 않는 표현이다: "It may be true" & "This may be the only component". 하지만 절의 시작부에 나타날 땐, 다음과 같이 "maybe"란 단어가 의도됐을 가능성이 크다 ("Maybe this proof will work"). 이 상황에선 다른 동사 "work"가 있고 초반부 표현이 (동사가 아닌) "possibly"를 의미함을 주목하라.

### 88. "A joint work"

우리는 "a theorem"과 "a result"라고 표현하는데, 두 단어(theorem, result)는 명확하고 구체적인 대상이기 때문이다. 반면에 "work"이란 단어는 abstract noun(추상명사)기 때문에 부정관사인 "a"를 필요로 하지 않는다. "This is a work of mine" 대신에 간단히 "This is work of mine"로, 그리고 "This is a joint work"이 아니라 "This is a joint work"으로 쓴다. 여기서의 "work"은 "a work of art" or "the complete works of Shakespeare"에서의 쓰임새와는 다르다. 수학에선 "work"은 "research"와 동일한 의미다.

### 89. "Evidently"

몇몇 비원어민들은 "clearly"를 위해 "evidently"를 사용한다. 이런 표현은 엄밀한 관점에서 틀린건 아니지만, 이는 원어민들에게 있어 다른 의미를 내포하고 있다. 이런 사실과 더불어 원어민들은 항상 "clearly"를 사용하고 "evidently"를 결코 사용하지 않기에, 저자가 무엇을 의미하는지 혼동을 줄 수 있다. "Evidently"를 "Clearly"로 항상 바꾸라. ("Evidently"는 "apparently"에 꽤 유사한데, 이는 미국영어에서 "성립"보단 "성립하는 것으로 보인다"를 의미한다)

### 90. "Principal" vs "Principle"

"Principal"은 형용사인 "foremost" (가장 중요한)를 뜻하고 수학적으론 "principal minor"로 쓰인다. "Principle"은 "the Pigeonhole principle"에서와 같이 아이디어 혹은 방법과 유사한 명사다.

### 91. More excess commas (과다한 쉼표)

정의에서 "is" 전이나 후에 쉼표는 필요없다. 또한 "show"와 "that" 사이에도 필요없다.

### 92. More expressions not used in English (영어에서 안 쓰이는 표현들)

"contradicts to" → "contradicts"  
"decompose to" → "decompose into"  
"necessary conditions of" → "necessary conditions for"  
"discuss about" → "discuss"  
"studied about" → "studied"  
"equals to" → "equals" 혹은 "is equal to"  
"to precise" → "to make precise" (precise는 동사가 아님)  
"a same argument" → "the same argument" 혹은 "a similar argument"  
"joint" (동사로 사용) → "join" (joint는 동사 아님)  
"specially" → "especially" 혹은 "special" (specially는 단어 아님)  
"usual coloring" → "ordinary proper coloring"  
"We pick up" → "We consider"