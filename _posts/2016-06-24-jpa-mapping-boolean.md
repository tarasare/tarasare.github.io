---
published: true
layout: post
title: "Jpa Mapping Boolean Type"
tags:
- Catatan
- Spring Data Jpa
- Jpa Mapping
- Hibernate
categories:
  - Jpa
---

Kadang kala saya membutuhkan mapping boolean di project yang saya kerjakan, untuk magtasi masalah ini
biasanya saya menggunakan `annotation` seperti berikut :

###JPA2 (with Hibernate 3.6+)
~~~ Java
    @Column(name = "enabled", nullable = false, columnDefinition = "TINYINT(1)")
    private boolean enabled;
~~~


untuk referensi bisa cek pertanyaan yang ada di [stackoverflow](http://stackoverflow.com/a/10224905/4392207)
atau bisa dengan menggunakan converter [Wikibook](https://en.wikibooks.org/wiki/Java_Persistence/Basic_Attributes#Example_of_column_XML) 





