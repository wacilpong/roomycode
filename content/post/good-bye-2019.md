---
title: "Good bye 2019"
date: "2019-12-27"
tags: ["회고"]
draft: true
---

난생 처음 쓰는 회고. 아주 간단하게 월별로 내가 뭘 했는지 한번 기록해보자.

### <b style="color: red;">1월, 2월</b>

##### **프론트엔드 개발자로 한 걸음**

이때는 초대권 기반의 티켓 전달 서비스 회사에 다녔는데, 처음으로 프론트엔드 개발자 포지션으로 1년여간 일했다. Angular 프레임워크로 된 기존 프로젝트를 유지보수 및 개발했고, 굉장히 규모가 작은 스타트업이어서 프론트엔드 전담개발, 서비스 기획, UI/UX, 심지어 IR까지 했던... 나는 언론정보학과(!)를 전공하여 발표에 그나마 능했던 직원으로서, VC 앞에서 발표까지 했다. 발표가 나쁘진 않았던 모양인지, 성공적으로 투자유치까지 했었다.
<br><br>

### <b style="color: red;">3월</b>

##### **이직을 결심하게 된 이유**

1년여간 다녔던 회사에서 처음으로 마크업도 제대로 해보고, SPA도 처음 다뤄봐서 의미는 있었지만, 협업에 대한 갈망이 커졌다. 다른 개발자들과 코드리뷰도 하고 함께 토론하면서 발전하고 싶다는 생각이 커졌다. 물론 우리의 친구인 구글과 스택오버플로우, 그리고 정보의 바다인 웹과 함께라면 얼마든지 발전할 수 있겠지만...! 혼자 있으면 확실히 나태해진다. 부정할 수 없다. 특히 개발자가 혼자여서 실무 위주로 빠르게 일을 쳐내야 했기 때문에 더더욱 구조에 대한 고민이나 코드 품질에 대한 생각을 먼저 하기가 어려웠다. 그래서 이직을 결심했다.
<br><br>

##### **React? Angular? 채용과정에서의 과제**

이번에 내가 지원했던 대부분의 회사는 알고리즘 테스트보다는 과제 위주였다. 대부분의 회사 주업무가 React 기반의 서비스 개발이었으나, 과제에서는 어떤 프레임워크 or 라이브러리를 쓰든, 혹은 바닐라로 하든 상관없는 곳이 대부분이었다. 그런데 내가 지원한 회사의 과제들이 규모가 작고, 상태관리를 어떻게 할 것인지가 중요한 과제들이었기 때문에 주로 React를 사용해서 과제를 제출했다. 이때 React를 처음 써봤는데, 뭔가 앵귤러를 할 때와 굉장히 다른 느낌이었다. 단방향으로 이루어지는 데이터 흐름이 이해하기 어려웠고, `props`와 `state` 개념도 잘 와닿진 않았다.
<br>

다만, React는 함수형과 정말 궁합이 잘 맞는다는 생각이 들었다. 함수형, 함수형 말만 들었지 도대체 어떻게 쓰는 것인가 이해가 가지 않았는데, React의 가장 핵심 메소드라고 할 수 있는 `setState()`자체가 함수형스러웠다! 왜냐하면 이 녀석은 항상 새로운 객체를 반환한다. 따라서 객체는 불변함을 유지하게 될 뿐만 아니라, 불변해야만 이전 state를 기억하여 재렌더링을 일으킬 수 있다. 하지만 아쉽게도 과제를 빠르게 끝내야 했기에 제대로 이해하지 못한 채로 기능구현에 급급하여 제출해서 아쉬웠다.
<br><br>

##### **공부, 공부, 공부!**

그리고 과제를 하면서 깨달은 것은, 생각보다 내가 알던 세계는 너무 좁았다는 것이다. 부끄럽게도 자바스크립트 문법 자체를 헷갈려서 오래 걸리거나 해내지 못한 게 태반이었다. 객체의 불변성을 유지하면서 코드를 작성하는 연습조차 되어있지 않았다. 이러한 이직과정을 통해 자바스크립트에 대한 부족함을 많이 느껴 좌절했지만, 학습에 대한 동기부여가 되기도 했다.
<br><br>

### <b style="color: red;">4월, 5월</b>

##### **React 묻고 리팩토링 더블로 가!**

과제를 제출했던 회사들 중에 한곳에 합격하여 현재도 다니고 있다. 들어와서 몇달은 React 생태계에 대한 이해와, 자바스크립트를 공부했다. 그런데 기존에 있던 코드품질이 생각보다 좋은 편이 아니어서 리팩토링까지 함께 해야했다. 리덕스로 거의 모든(!!) 상태를 관리하고 있던 프로젝트여서, 상황에 맞게 분리시키는 작업과 더불어 React `v16.8`에서 도입된 hooks를 이용해 클래스형 컴포넌트들을 함수형 컴포넌트로 리팩토링했다. 내가 들어왔을 때는 큰 기능 하나를 만들어야했기 때문에 기능구현을 하면서 진행했다.
<br><br>

##### **Typescript에 대한 얇고 쓸모있는 깨달음**

이 과정에서 기존 코드나 React 생태계, 심지어 자바스크립트도 제대로 모른 채로 진행해서 삽질을 좀 많이 했다. 그래도 별 수 있나. 모르는 부분은 집에서 새벽까지 했다... 해당 프로젝트에 `typescript`도 얹었다. 여기서 또! 부끄러웠던 지점은, 앵귤러로 개발할 때는 타입스크립트의 소중함을 몰랐다는 것... 꼭 필요한 부분도 아닌데 `any`로 타입을 허용해 타입스크립트의 장점을 활용하지 못했다. 그런데 이번 기회에 ts를 좀더 심도있게 해보면서 활용할 지점이 많다는 걸 알았다.
<br>

1. 간단하게는 API 혹은 외부 데이터에 대한 타입을 알 수 있다는 점만으로도 해당 데이터를 예측할 수 있으니 생산성이 올라갔다.<br>
2. 또한 컴파일 단계에서 걸러주니 타입에러가 날 염려가 없다. 자바스크립트는 의도치 않은 타입 에러를 내는 경우가 많다. 돔 렌더링이 이루어지지 않았는데 참조하려고 한다거나, 정의되지 않은(`undefined`) 프로퍼티나 메소드를 참조하려고 한다거나...<br>
3. 그리고 코드가 Testable하게 쓰여진다! 실제로 테스트코드를 작성했는지 여부와 무관하게, 지정하지 않은 타입이 들어올 수 없는 안전한 코드를 작성하게 된다. 즉, 들어오는 값에 대해 어느정도 제어할 수 있고, 어떤 값이 반환될 지도 알 수 있기 때문이다.
   <br><br>

##### **예상치 못한 변수의 등장**

그리고 예상치 못한 변수가 있었는데, 바로 백오피스 페이지였다. 웹팀이 맡아야 하는 프로젝트가 두개였는데, 그중 Ruby on Rails로 작성된 프로젝트이다. 말이 rails이지 그냥 JQuery로 굉장히 선언적으로 작성되어있는 프로젝트였다. 내가 들어오기 전부터도 유지보수가 정말 힘들다고 알려준 프로젝트여서 마음을 졸이며 확인했는데... WOW! 그나마 다행(?)이었던 건, 옛날에 SI유지보수할 때와 비슷한 코드라는 점이었다. 빠르게 성장한 회사이고, 앞선 개발자 분들도 시간에 쫓기며 빠르게 쳐내야 했다고 들어서 이해했다. 언제나 모든 회사의 레거시는 일단 존중해야 한다고 생각한다! 하지만 문제가 터질 때마다 해결하기 정말 힘들었던 건 사실이다.
<br><br>

### <b style="color: red;">6월</b>