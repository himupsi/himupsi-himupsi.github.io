-----
title: Javascript 스터디(작성중)
summary: JavaScript is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions...
thumbnail: js.png
createDate: 202103011200
category: 스터디
tags: [ Javascript ]
-----

## Javascript를 다시 들어다 보자.

취업을 준비하며 이것 저것 공부하다 보니 Front-End 개발자인데도 javascript를 대한 생각보다 지식이 부족한 것을 깨닫게 되었다.  
초심으로 돌아가 Javascript를 다시 공부하며 이 포스트에 정리해서 작성해 볼 예정이다.

## 공부할 것들

### Javascript 함수가 어떻게 동작하는지 이해가 쉽게 설명해준 동영상이 있어 링크를 추가한다.

* [유튜브 - 이벤트 루프는 무엇입니까?](https://www.youtube.com/watch?v=8aGhZQkoFbQ&list=LL&index=1&t=5s)

### Javascipt 개발자가 알아야 하는 개념이라고한다.

영어로 되어어 있어 하나하나보려면 시간이 걸릴 것 같다.  
참고로 `🚀 2018년 깃허브 최고의 오픈소스 프로젝트 중 하나로 선정되었습니다!` 이렇게 쓰여 있다.

* [Github 페이지 - 모든 자바스크립트 개발자가 알아야 하는 33가지 개념](https://github.com/leonardomso/33-js-concepts)


### 제일 좋은 자습서

* [MDN Web Docs - Javascript](https://developer.mozilla.org/ko/docs/Web/JavaScript)

### Javascript 메모리 관리

이전 직장 상사분을 오랜만에 만나 그 동안 못했던 이야기를 나누다 **클로저**가 뭔지 아냐고 물어보셔서 자신있게 알고 있다고 했다. 그 다음 질문이 그러면 함수는 (생명주기가) 끝났는데 클로저거 참조하는 변수는 왜 살아있냐고 물으셨다. 나는 여기까지 생각해 본적이 없어서 머뭇거리며 **클로저가 사용하는 변수는 가비지 컬렉션이 안되나...** 이렇게 말할 수 밖에 없었다. 해주신 이야기로는 그 변수가 레퍼런스 되고 있기 때문에 가비지 컬렌션이 안된다고 하셨다. Javascript 메모리 관리에 알아 야 할 것같아 아래의 링크를 추가한다.

* [블로그 - 자바스크립트 및 NodeJS 메모리 누수 피하기 (+ 메모리 구조, 가비지 컬렉터)](https://aerocode.net/378)