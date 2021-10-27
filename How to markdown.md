마크다운 제목만들기
==============

    마크다운 제목만들기
    ==============

<br>

마크다운 제목만들기
--------------

    마크다운 제목만들기
    --------------

<br>

# 마크다운 문서 제목 예제
## 마크다운 문서 제목 예제
### 마크다운 문서 제목 예제
#### 마크다운 문서 제목 예제
##### 마크다운 문서 제목 예제
###### 마크다운 문서 제목 예제

<br>

    # 마크다운 문서 제목 예제
    ## 마크다운 문서 제목 예제
    ### 마크다운 문서 제목 예제
    #### 마크다운 문서 제목 예제
    ##### 마크다운 문서 제목 예제
    ###### 마크다운 문서 제목 예제


<br>


## BlockQuote

> BlockQuote
> > BlockQuote
> > > BlockQuote

    > BlockQuote
    > > BlockQuote
    > > > BlockQuote

<br><br>

## 박스만들기

    다음과 같은 문자를 넣을수 있는 박스를 만들수 있다.
    만드는 방법은 Tab으로 공백을 넣으면 된다.

    다음과 같이 줄 변경도 된다.

    1. 숫자도 입력 가능하다.
    2. 그럼 이상..

<br><br>


## 코드넣기

```js

    class ShoppingList extends React.Component {

    render() {
        return(
            <div className="shopping-list">
            <h1>Shopping List for {this.props.name}</h1>
            <ul>
            <li>Instagram</li>
            <li>WhatsApp</li>
            <li>Oculus</li>
            </ul>
    </div>);
            }
    }

    // 사용 예제: <ShoppingList name="Mark" />

```
또는 **Tab** 으로 인텐션을 주면 된다.

<br><br>




## 문단 간격만들기

마지막 문장끝에서 두개이상의 공백으로 줄바꿈을 만들어준다.


    두개이상의 공백으로 줄바꿈을__  
    만든다.
    <br> 태그 사용 가능

    <br><br>

<br><br>


## 소스코드 입력방법

    ```js   

    코드내용

    ``` 끝내면 된다.

    맥OS 자판에서 control + command + space 로 특수문자에서 선택한다.

    ```css
    ```html
    ```c#
    ```python

아래 코드는 ```js 형식으로 코드를 보여준다.

```js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

<br><br>

## 1. 링크만들기

[마크다운 설명](https://github.com/ssh521/MarkDown/blob/main/How%20to%20markdown.md)

    [마크다운 설명](https://github.com/ssh521/MarkDown/blob/main/How%20to%20markdown.md)


## 2. 이미지 링크 넣기
[![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)

    [![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/)


[![이미지](https://ssl.pstatic.net/tveta/libs/1360/1360832/077e2ae155657dc01da3_20211012095236566.jpg)](https://siape.veta.naver.com/fxclick?eu=EU10041892&calp=-&oj=ZagUyei1lSj8n5t8ydpSQplJ%2BFOJVa4Jd6FVwXuxQ84DlmoRKqQkYscf1clqz3HVwOG9WtyOxzyG3ZKjUtYQl1fuCmrWF3govwZg%2BzeW8CI4As11kbk%2BddEWmfdY7wJVmIZZNRX97ws&ac=8431072&src=5400424&br=3643340&evtcd=P901&x_ti=1312&tb=&oid=&sid1=&sid2=&rk=d56700c08914d674b3e0acf04e4f29b0&eltts=eGwXpVaC%2BbvTr7rHNuhYuA%3D%3D&lu=&brs=Y&){:width="50%" height="50%"}