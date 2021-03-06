---
title: Install
title: 安装
next:
  title: Set up an editor
  title: 设置编辑器
  path: /get-started/editor
toc: false
---

Select the operating system on which you are installing Flutter:

你想要把 Flutter 安装到如下哪个操作系统里呢？

<div class="card-deck mb-8">
{% for os in site.os-list %}
  <a class="card" href="/get-started/install/{{os | downcase}}">
    <div class="card-body">
      <header class="card-title text-center m-0">
        {{os}}
        <i class="fab fa-{{os | downcase}}"></i>
      </header>
    </div>
  </a>
{% endfor %}
</div>

{{site.alert.important}}
  If you're in China, first read [Using Flutter in China](/community/china).
  
  如果你在中国的网络环境下使用 Flutter，请先看一下[这篇文章](/community/china)，查看是否需要对网络环境进行特别设置。
{{site.alert.end}}

