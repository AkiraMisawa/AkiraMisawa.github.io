extends: post.liquid

title: はじめて
author: q_msw
date: 05 Jan 2018 16:15:00 +0100
path: /:year/initial-post
tags: cobalt, math, rust, c++
---

社会に放牧されはや1年と10ヶ月あまり。

`Rust`と`C++`がすき。

日頃勉強してわかったことを気が向いたときに書く可能性があるくらいのもの。

このブログは`Rust`製静的サイトジェネレータ[Cobalt](https://github.com/cobalt-org/cobalt.rs)を使い、
[GitHub Pages](https://pages.github.com)で公開している。

各記事はMarkdownで書いて簡単なコマンドでpublichできるのでかんたんでとてもよい。


## 数式のテスト
現状数式を書く努力を怠っているため、画像を貼り付けることで対応する。

- 非定常非圧縮性Navier--Stokes問題
<img alt="Navier--Stokes equation" src="/img/posts/initial-post/ns.png" />


## コードのテスト
Markdownのfenced code blockと同じ記法で書けてよい。

- hello world in `Rust`
```rust
fn main() {
    println!("Hello my beautiful world!!");
}
```

- hello world in `C++`
```cpp
#include <iostream>

int main(void)
{
    std::cout << "Hello my beautiful world!" << std::endl;

    return 0;
}
```

ねこ
<img class="about-icon" alt="inu" src="/img/initial-candy.jpg" />
