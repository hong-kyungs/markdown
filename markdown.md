<!-- Heading -->
<!-- 총 6가지 스타일의 heading이 있고, #이 하나면 자동으로 밑줄생김 -->

# Heading

## Heading

### Heading

#### Heading

##### Heading

###### Heading

paragraph

<!-- #을 붙이지 않으면 일반 텍스트 -->

<!-- Line : 언더스코어 3번-->

---

<!-- Text Attribute -->
<!-- ** 로 감싸면: bold, *로 감싸면: Italic, ~~로 감싸면: strikethrough -->

This is the **bold** text and this is the _Italic_ text and let's do ~~strikethrough~~.

<!-- quote -->

> Don't forget to code your dream.

<!-- bullet list -->

Fruits:

- 🍎
- 🍓

Other Fruits:

- 🍋
- 🍇
  <!-- number list -->
  numbers:

1. first

   - 🍎

     This is an red apple.

     ![Image description](https://images.unsplash.com/photo-1581047800850-0cb82075a02f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8cGFzdGVsJTIwYmVhY2h8ZW58MHx8MHx8&auto=format&fit=crop&w=800&q=60)

   - 🍏

2. second
3. thrid

<!-- Link : []에 원하는 단어나 문장, ()에 링크-->

click [here](https://www.naver.com/)

<!-- 문장안에서 링크를 넣으면 복잡해질 수 있으므로 단축키를 사용 -->

Make sure you check out [wes'][1] site.

[Wes][1] also teaches at [HackerYou][hack] where you can come and learn with him in person.

[1]: http://wesbos.com
[hack]: http://hackeryou.com

<!-- Image : ![]에 사진설명, ()에 주소-->

![Image description](https://images.unsplash.com/photo-1581047800850-0cb82075a02f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8cGFzdGVsJTIwYmVhY2h8ZW58MHx8MHx8&auto=format&fit=crop&w=800&q=60)

<!-- table -->

| Header | Description |
| ------ | ----------- |
| cell1  | cell2       |
| cell1  | cell2       |
| cell1  | cell2       |

<!-- :위치에 따라서 오른쪽정렬, 왼쪽정렬, 가운데정렬 -->

| Header | Description | Description2 |
| -----: | :---------- | :----------: |
|  cell1 | cell2       |    cell3     |
|  cell1 | cell2       |    cell3     |
|  cell1 | cell2       |    cell3     |

<!-- Code -->
<!-- `` 를 사용해서 코드만 하이라이트 -->

To print message in the console, use `console.log('your message')` and...

<!-- ```을 사용해서 코드블락, 해당코드 언어를 넣어주면 문법에 하이라이트 -->

```
console.log('your message')
```

```js
console.log('your message')
```

```diff
var x = 100;
- var y = 200;
+ var y = 200;
```

<!-- check list, github에서 작동 -->

To do :

- [ ] Get milk
- [x] Crack eggs
- [ ] Cook bacon
