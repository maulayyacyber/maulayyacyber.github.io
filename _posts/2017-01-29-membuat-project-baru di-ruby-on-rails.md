---
layout: post
title: Membuat Project Baru di Ruby on Rails
subtitle: Belajar Ruby on Rails
bigimg: /img/blog.jpg
---


oke pertama sebelum kita membuat aplikasi dengan Ruby on Rails pastikan anda sudah menginstall Ruby dan Railsnya

ada beberapa opsi yang perlu diperhatikan untuk membuat sebuah project baru dii Rails, diantaranya yaitu :

**-d** : yaitu konfigurasi database yang ingin kamu pakai, secara default Rails menggunakan **sqlite3**, ada beberapa pilihan database yang bisa kamu pilih diantaranya yaitu : **mysql**, **oracle**, **postgresql**, dll.

**-j** : tidak menyertakan JavaScript

**-T:** tidak pakai **Test::Unit**

oke kali ini kita mencoba membuat sebuah project baru bernama blog

untuk kamu yang ingin menggunakan database sqlite (default) kamu bisa langsung ketik perintah berikut ini :

~~~
# terminal
rails new blog
~~~

jika kamu ingin pakai database mysql, kamu bisa pakai perintah berikut ini : 

~~~
# terminal
rails new blog -d mysql
~~~
