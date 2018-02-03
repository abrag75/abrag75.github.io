---
layout: post
title: Penulisan markdown
subtitle: Tata cara penulisan teks markdown
gh-repo: github
gh-badge: [star, fork, follow]
image: /img/avatar-icon1.png
tags: [Komputer]
---

Dalam Penulisan [markdown](http://markdowntutorial.com/) sangatlah mudah dan efisien di bandingkan dengan menulis web statik menggunakan syntak syntak **HTML**.  Bagi yang belum paham silahkan pahami terlebih dahulu bagaimana cara menggunakan syntak markdown ini [5 Menit Belajar syntak markdown](http://markdowntutorial.com/ "Belajar Markdown").
contoh syntak penulisan menggunakan markdown
Teks Bold
```bold
**Here is some bold text**
```
Hasilnya

**Here is some bold text**

Heading
```h1
## Here is a secondary heading
```
Hasilnya

## Here is a secondary heading

Tabel:
```table
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
```
Hasilnya

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

Penyisipan gambar
```gambar
![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)
```
Hasilnya

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Penulisan Syntak
```code
~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~
```
hasilnya

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Kemudian syntax dengan highlight:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

dan syntak higlight dengan line numbers:
{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}


## Boxes
untuk box notifikasi:

### Notification
```note
{: .box-note}
**Note:** This is a notification box.
```
hasilnya

{: .box-note}
**Note:** This is a notification box.

### Warning
```warning
{: .box-warning}
**Warning:** This is a warning box.
```
hasilnya

{: .box-warning}
**Warning:** This is a warning box.

### Error
```error
{: .box-error}
**Error:** This is an error box.
```
hasilnya

{: .box-error}
**Error:** This is an error box.

Nah cukup mudah bukan bagaimana cara menggunakan markdown