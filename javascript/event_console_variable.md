x 라는건 대입연산자를 통해서 값이 바뀔 수 있다라는 뜻을 가지고 있는 변수다.
하지만 숫자 1은 언제나 1이기 때문에 바뀌지 않는 다는 뜻에서 상수라고 한다.
```
name = 'han'
alert("rasdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;asdfjk;
asdfjkl;asdjfkl;asdfjka"+name+"sdkfja;lsdfkl;jasdfjkl;asdiaopujassl;asdfjk;asdfjkl;asdjfkl;asdfjkv
asdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;a"+name+asdfjkl;asdjfkl;asdfjk;
asdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;a"+name+;asdfjkl;asdjfkl;asdfjk;asdfjkl;asdjfkl;asdfjk;"
name이라는 변수에 "han"을 대입했기때문에 "+name+"은 출력했을때 han으로 출력된다
```

`<style="background-color:balck;color:white;>`
배경화면은 검은색으로 바뀌고 글씨는 흰색으로 바뀐다

document.write(적고싶은 것);웹 페이지에다가 문장을 출력할때 사용한다

`<input type="button" value="hi" onclick="alert('hi')">(이벤트)`
버튼을 생성하고 버튼내용은 hi 누르게 되면 경고창에 hi라는 글씨가 뜨게된다

`<input type="text" onchange="alert('changed')">(이벤트)`
텍스트를 생성하고 텍스트안에 있는 내용을 수정하고 다른 곳을 클릭하면 체인지드 라는 경고창이 뜨게된다.

`input type="text" onkeydown="alert('key down')"(이벤트)`
텍스트를 생성하고 키를 누르면 키 다운이라는 경고창이 뜨게 된다.

`<h2 style="background-color:coral;color:powderblue">JavaScript</h2>`
백그라운드 색상은 코랄로 바뀌고 글씨 색상은 흰색으로 바뀐다.
css라는 언어로 디자인하고 싶을때는 스타일이라는 속성을 쓰고 그 안에다가 css에 속성이라는 문법을 사용하는 것
