---
published: true
layout: post
title: "Cara Mudah Membuat Blog Di Github"
image: '/assets/img/tutorial/jekyll-theme.jpg'
description: "Pada tutorial saya kali ini kembali akan saya coba tuliskan tahapan dalam membuat sebuah blog yang di hosting pada github."
main-class: 'jekyll'
tags:
- blogging
- tutorial
- jekyll
twitter_text: "Cara Mudah Membuat Blog Di Github"
introduction: "Pada tutorial saya kali ini kembali akan saya coba tuliskan tahapan dalam membuat sebuah blog yang di hosting pada github."
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

<mark>USERNAME.github.io</mark>

Jika masih bingung silahkan kunjungi [Jekyllrb.com](https://jekyllrb.com/) atau jika anda merasa kesulitan untuk mengikuti perintah diatas silahkan anda bisa download dan install template Jekyll Bootstrap  di [Jekyllbootstrap](http://themes.jekyllbootstrap.com/) disini anda bisa langsung menginstall template tersebut dengan mengikuti petunjuk yang sudah diberikan pada halaman situs.

Masih juga bingung? anda dapat menghubungi saya di [Contact](https://antoncabon.github.io/about/) atau anda bisa melihat tutorial dengan video tentang cara membuat blog di github.

<iframe width="100%" height="350" src="https://www.youtube.com/embed/5cqzKDq5FLw" frameborder="0" allowfullscreen></iframe>

Sebagai rekomendasi untuk download template anda dapat mengunjungi url ini [Jekyll Theme](https://jekyllthemes.io/) dan disini anda bisa dengan bebas memilih mau template yang versi premium atau gratis, terserah anda.

Selamat mencoba dan semoga berhasil dan jangan pernah berhenti untuk belajar dan belajar !.
