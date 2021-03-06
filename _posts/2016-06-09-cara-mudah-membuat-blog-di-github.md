---
published: true
layout: post
title: "Easy Steps to Create a Blog On Github"
date: 2016-06-09 01:38:37
image: '/assets/img/tutorial/jekyll-theme.jpg'
description: "Pada tutorial saya kali ini kembali akan saya coba tuliskan tahapan dalam membuat sebuah blog yang di hosting pada Github.com"
main-class: 'jekyll'
tags:
- blogging
- tutorial
twitter_text: "Easy Steps to Create a Blog On Github"
introduction: "Pada tutorial saya kali ini kembali akan saya coba tuliskan tahapan dalam membuat sebuah blog yang di hosting pada Github.com"
---

Pada tutorial saya kali ini kembali akan saya coba tuliskan tahapan dalam membuat sebuah blog yang di hosting pada <kbd>Github.com</kbd>, hal yang pertama sekali perlu anda lakukan adalah membuat sebuah akun di [Github](https://github.com), kemudian setelah anda membuat akun hal berikutnya adalah membuat sebuah <kbd>new repository</kbd> dengan judul <kbd>USERNAME.github.io</kbd>, ganti <mark>USERNAME</mark> dengan nama domian anda. 

![Cara Membuat Blog di Github](/assets/img/tutorial/jekyll-theme.jpg)

Setelah semua tahapan diatas dilakukan hal berikutnya adalah menginstall template <kbd>Jekyll Bootstrap</kbd> yang akan anda gunakan pada blog anda tersebut.

Masukkan perintah ini ke terminal anda dalam direktori blog yang ingin anda buat:

{% highlight css linenos%}
git clone https://github.com/plusjade/jekyll-bootstrap.git USERNAME.github.io
cd USERNAME.github.com
git remote set-url origin git@github.com:USERNAME/USERNAME.github.com.git
git push origin master
{% endhighlight %}

Setelah anda lakukan perintah diatas maka secara ajaib blog anda sudah bisa dilihat pada url:

<code class="filter">USERNAME.github.io</code>

Jika masih bingung silahkan kunjungi [Jekyllrb.com](https://jekyllrb.com/) atau jika anda merasa kesulitan untuk mengikuti perintah diatas silahkan anda bisa download di dan install template Jekyll Bootstrap  di [Jekyllbootstrap](http://themes.jekyllbootstrap.com/) disini anda bisa langsung menginstall template tersebut dengan mengikuti petunjuk yang sudah diberikan pada halaman situs.

Masih juga bingung? silahkan hubungi saya di [Contact](https://antoncabon.github.io/about/) atau ingin melihat tutorial dengan lengkap dengan videonya cek disini [Video Tutorial Bagi Pemula](https://antoncabon.github.io/github-pages-and-jekyll-video-untuk-pemula/) 

Selamat mencoba dan semoga berhasil.


