# hwrdtm.github.io

## Overriding Jekyll Minima Theme

This website is initialized via `jekyll new <name>` command, which uses the Minima Jekyll theme. With this theme, a lot of the [default styles, assets and content is provided via the gem](https://jekyllrb.com/docs/themes/), and is thus hidden from this repository. You can view the path of the Minima theme with `bundle info --path minima`.

To override these defaults, simply create files with similar naming at similar paths in this repo. At the time of writing this, there have already been some overrides.

## Example Post Markdown

```markdown
---
layout: post
title: "Welcome to Jekyll!"
date: 2020-06-08 20:54:17 -0700
categories: jekyll update
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
```
