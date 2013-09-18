---
layout: post
title:  "Apakah hover akan punah"
date:   2013-04-20 10:29:41
---

Dengan berkembangnya perangkat mobile yang menggunakan touch screen apakah akan membuat pseudo class <code>:hover</code> punah?

Mungkin pseudo class <code>:hover</code> adalah pseudo class pertama yang kalian pelajari. Atau mungkin satu-satunya yang kalian pelajari. fitur kecil yang paling sering digunakan untuk membuat interaksi yang interaktif saat kita mengarahkan cursor mouse pada element tertentu.

Kata kuncinya adalah cursor mouse. pada perangkat mobile yang mendukung interaksi berupa touch screen, <code>:hover</code> state tidak bisa digunakan karena tidak menggunakan mouse. Namun menggunakan jempol sebagai alat interaksi.

##SOLUSI UNTUK WEB DEVELOPER?

Solusi untuk mengatasi keterbatasan fungsi <code>:hover</code> pada perangkat touch screen bisa dibilang cukup mudah. Beberapa web developer menggunakan aktivasi dengan menggunakan mouse click. Metode ini juga digunakan oleh [Twitter Bootstrap](http://twitter.github.io/bootstrap/components.html#buttonDropdowns).

[csscience](http://csscience.com/accordion/) menggunakan pendekatan menggunakan accordion apabila sebuah drop down menu dibuka pada perangkat mobile.

##KESIMPULAN

Memang sangat disayangkan apabila di masa depan fitur :hover telah hilang. Bisa dikatakan hampir semua jenis interaksi menggunakan fitur ini. Yang menjadi pertanyaan sekarang, apakah mobile adalah masa depan?
