---
published: true
layout: post
title: "Cara Mengganti Port Server Springboot"
tags:
- Catatan
- Springboot
categories:
  - Springboot Properties
---

Default-nya springboot berjalan di port `8080`, Namun kita dapat mengaturnya dengan dua cara
- Tambahkan `server.port=8081` pada `application.properties`
- Yang kedua yaitu dengan menambahkan `-Dserver.port=8081` di command line



Screenshoot :

![Cara Mengganti Port Server Springboot](/wp-content/uploads/img/24-06-2016/cara-mengganti-port-server-springboot.PNG)

Untuk lebih jelasnya saya bisa melihatnya di [Spring Boot Documentasi](http://docs.spring.io/spring-boot/docs/current-SNAPSHOT/reference/htmlsingle/#howto-change-the-http-port)



