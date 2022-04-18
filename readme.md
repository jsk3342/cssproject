# CSS Project

상기 프로젝트는 하단 링크를 통해 확인 가능합니다.

https://jsk3342.github.io/cssproject/

## 목표

박스 모델을 활용하여 원하는 위치에 레이아웃 잡아보기

### 어려운 점

### 1. h1 태그에 border가 보이지 않음

첫번째 아티클 요소에 있던 h1 태그에 border값을 지정해 주었는데 왠지 모르게 보더 값이 표현되지 않았습니다.
첫째 아티클의 자식 요소인 h1은 둘째 아티클 보다 하위 요소이기 때문에 보더값은 나오지 않았습니다. 그런데 왜 글씨는 나오게 될까요?

### 2. h1 border bottom 컨텐츠 크기에 맞게 조정

컨텐츠의 크기에 맞게 하기위해 inline-block을 쓰게 되면 이미지 옆으로 이동하게 됩니다. 해결하기 위해 이미지를 박스로 감싸서 블럭 레벨로 만들고 글씨를 내리면 될까요?
