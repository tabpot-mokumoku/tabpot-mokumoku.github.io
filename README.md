## README

### Requirement

- git
- ruby 2.4.2
- bundler

### 環境の作り方について

- [エントリを投入する環境の作り方について](https://tabpot-mokumoku.github.io/mokumoku/2018/01/19/yamane.html)

### エントリ投入の方法

基本的なすすめ方について以下に列挙します。

- [リポジトリ](https://github.com/tabpot-mokumoku/tabpot-mokumoku.github.com/)の Issue でもくもくなネタを宣言します
- 作成した Issue の ID と自分の ID をもとに branch を作ります (例：yamanetoshi-1)
- /_posts/yyyy-mm-dd-<自分のid>.md を作成して、とりあえず「自分の名前」および「作成した Issue へのリンク」を作成します
- フォーマットについては例を以下に示します
- Pull Request を作ります
- もくもくしたり参加者と情報交換したりしてください
- もしかすると自己紹介タイムを設けるかもしれません

エントリの投入方法については以下も参考にしてください。

- [エントリの投入の方法について](https://tabpot-mokumoku.github.io/mokumoku/2018/01/18/yamane.html)

### Pull Request について

- 二名以上のレビュを受けてください。
- 可能であれば二人目のレビュアさんが merge してあげてください。

### フォーマット

以下な形です。(_posts/2018-01-17-welcome-to-jekyll.markdown)

```
---
layout: post
title:  "Welcome to Jekyll!"
date:   2018-01-17 13:17:52 +0900
categories: jekyll update
---
You窶冤l find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll窶冱 GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
```

未だ `rake generate` などで雛形が作成される訳ではありません。

## License

[GPLv2](http://www.gnu.org/licenses/gpl-2.0.html)
