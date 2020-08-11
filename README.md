# 제목 

**Markdown** 파일 연습용 파일입니다.


# 가장 큰 제목

## 두번째로 큰 제목

### 세번째로 큰 제목

#### 세번째로 작은 제목

##### 두번째로 작은 제목

###### 가장 작은 제목

별 하나로 묶으면 *이탤릭체가 된다*는 사실.

별 두개로 묶으면 **강조체 된다**는 사실.

틸드 두개로 묶으면 ~~취소선이 된다~~는 사실.

백 쿼터로 묶으면 코드체가 되어 `int a = 100;` 을 코드 폰트로 보여줄 수 있다는 사실.

> ">" 을 문장 맨 앞에 쓰면 인용구 스타일로 쓸 수 있다는 사실. 

>> ">>" 을 쓰면 이렇게 됩니다.

문장을 한번 개행하면 띄어지지가 않습니다.
보세요. 한번 개행했는데 띄어지지가 않습니다. 

**Markdown** 에서는 이렇게 두 번 개행해야 띄어집니다.

두 번 개행하니까 띄어지죠.


- 아이템입니다. 

  - 하위 아이템이에요. 두번 띄어써야 합니다.

    - 더 하위 아이템입니다. 

      이렇게 문장을 같은 레벨로 쓸 수 있습니다.
  
  - 아무말 

- 아무말 

1. 순서 아이템은 이렇게 1. 로 시작합니다.

2. 두번째 순서 아이템

    - 순서 아이템의 하위 아이템을 쓰려면 네 번 띄어써야 합니다. 

3. 그 다음 순서 아이템이에요. 

  - 순서 아이템의 하위 아이템을 두번 띄어 쓰면 이렇게 하위 레벨로 랜더링되지 않습니다.


  개발자들이 가장 자주 사용하는 검색 엔진은 [Google](https://www.google.com) 입니다. 

한동대생들이 항상 이용하는 사이트는 [Hisnet](http://hisnet.handong.edu) 입니다. 

한동대 로고는 다음과 같습니다.

![logo](https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/HGU-Emblem-eng2.png/150px-HGU-Emblem-eng2.png) 

로컬에 저장되어 있는 이미지를 사용할 수도 있습니다. 

![스폰지](sponge.png) 

> 이 경우 `sponge.png` 가 로컬에 존재해야 합니다. 

```shell
$ git init
$ docker run -it ccss17/ubuntu
``` 
 
```python
s = "Python 문법 하이라이팅"
print s
```

```
s = "하이라이팅이 되지 않습니다."
print s
```

|첫번째|두번째|세번째|
|:---:|:---:|:---:|
|1|2|3|
|a|b|c|

계속 되는 내용이 있는데

---

내용이 전환되면 이렇게 분할선을 넣으면 좋습니다.