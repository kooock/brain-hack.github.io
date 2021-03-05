---
layout: post
title:  "창업을 한다면 가장 먼저 내 편 부터 만들어야 한다"
author: 눼피샬
categories: [ 창업 ]
image: assets/images/16.jpg
beforetoc: "내 편은 누구일까? 왜 내 편이 중요한가? 어떻게 내편을 만들 수 있을까?"
toc: true
---

내가 단순히 용돈벌이 부업으로 하려고 했던 것을 창업을 하도록 키운 것도 내 편 이었고
내가 창업을 하자마자 거의 2달이 넘는 시간동안 절망과 좌절속에 허우적거렸던 가장 큰 이유 또한 내 편 이었고
절망을 딛고 일어나서 다시 삶을 변화시키도록 만들게 한 것도 내 편 이었다. 
결국 사람이 제일 어렵더라.


## 내가 이것을 한다고 했을 때, 아무도 내 편은 없었다.
내 인생을 송두리째 변화시킨 건 사경인 회계사의 강의였다. page2에서 구매한 사경인 회계사의 실전투자아카데미 18개의 강의 동영상은 지금의 내가 이러고 있는 것의 시작이기도 하다. 재무제표를 통해 기업을 분석하는 방법을 배우고 나서 정말 시야가 많이 넓어졌다. 그간 시스템 트레이딩의 애매함과 비합리성에 의구심을 품고 있을 때 나한테 해답을 주는 강의였다. 그렇게 뭔가 깨달음을 얻은 후에는 이렇게 혼자 깨닫기는 너무 아깝다고 생각했다. 나는 예전부터 배우면 써먹어야 한다고 생각하는 사람이었다. 그래서 강의 때 배운 모든 분석 방법을 자동으로 모든 상장사에 적용하고 그런 방식으로 필터링 된 종목을 추천해주는 서비스를 만들고 싶었다. 그렇게 나는 크롤러를 만들고 모든 상장사의 재무데이터를 DB에 저장하고 여러 SQL 스크립트를 통해 분석엔진 프로토타입을 만들었다. 그리고 분석 결과를 서빙할 수 있는 서버의 프로토타입 버전을 개발하였고, 안드로이드 앱의 프로토타입 버전을 개발하였다. 보이는 것은 허접했지만 나름 분석은 어느정도 괜찮게 되고 있었다. 그리고 주변사람들에게 나 이런거 만들고 있다고 했지만 주변의 사람들은 시큰둥했다. 니가 그런걸 어떻게 만드냐는 것이었다. 그리고 프로토타입을 보여줬을 때는 이게 정확하기는 한거 맞냐고 했다. 하고 있을때는 못한다고 하고 한 이후에는 제대로 된 게 아니라는 것이었다. 그렇다. 그 사람들은 내가 무엇을 어떻게 한 것이 중요한게 아니라 내가 그것을 만들고 성공시키면 안되는 것이엇다. 더 정확히는 자기보다 더 성공하면 안되는 것이었다. 이 것은 내가 스마트스토어를 한다고 했을때도 똑같이 들었던 말이다. 위탁판매로 판다고 했을때는 그렇게 팔 수는 없다고 했고 사입판매로 판다고 했을 때는 재고관리를 할 수 없다고 했고 제조사랑 직접 컨택하겠다고 했을 때는 그럴 수 있는 인맥이 없지 않냐는 소리를 들었다. 나를 걱정한다고 한다. 그래 걱정하겠지 내가 본인보다 더 잘 될까봐. 그리고 심리학적으로 뭔가를 한다고 했을 때 말리는 사람들은 무의식적으로 본인을 투영한다고 한다. 본인이라면 못할 것 같아서 하지말라고 한다는 것이다.


결국 나를 정말 생각하는 내편은 없는 것이었다. 안될 것도 되게 하고 싶어서 되게하려 하니까 됐다고 하네 고독하구만

....작성중 개졸리다. 밑에는 다시 작성해야지


## Writing code blocks

There are two types of code elements which can be inserted in Markdown, the first is inline, and the other is block. Inline code is formatted by wrapping any word or words in back-ticks, `like this`. Larger snippets of code can be displayed across multiple lines using triple back ticks:

```
.my-link {
    text-decoration: underline;
}
```

#### HTML

```html
<li class="ml-1 mr-1">
    <a target="_blank" href="#">
    <i class="fab fa-twitter"></i>
    </a>
</li>
```

#### CSS

```css
.highlight .c {
    color: #999988;
    font-style: italic; 
}
.highlight .err {
    color: #a61717;
    background-color: #e3d2d2; 
}
```

#### JS

```js
// alertbar later
$(document).scroll(function () {
    var y = $(this).scrollTop();
    if (y > 280) {
        $('.alertbar').fadeIn();
    } else {
        $('.alertbar').fadeOut();
    }
});
```

#### Python

```python
print("Hello World")
```

#### Ruby

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### C

```c
printf("Hello World");
```




![walking]({{ site.baseurl }}/assets/images/8.jpg)

## Reference lists

The quick brown jumped over the lazy.

Another way to insert links in markdown is using reference lists. You might want to use this style of linking to cite reference material in a Wikipedia-style. All of the links are listed at the end of the document, so you can maintain full separation between content and its source or reference.

## Full HTML

Perhaps the best part of Markdown is that you're never limited to just Markdown. You can write HTML directly in the Markdown editor and it will just work as HTML usually does. No limits! Here's a standard YouTube embed code as an example:

<p><iframe style="width:100%;" height="315" src="https://www.youtube.com/embed/Cniqsc9QfDo?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe></p>
