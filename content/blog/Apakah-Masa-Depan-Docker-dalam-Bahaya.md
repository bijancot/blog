---
title: "Apakah Masa Depan Docker Dalam Bahaya ?"
description: "meta description"
image: "https://is3.cloudhost.id/panji-wp/blog-1/docker-wins.png"
date: 2022-01-20T19:12:48+07:00
draft: false
author: "Lubana Era"
tags: ["Diy", "Toy"]
categories: ["LifeStyle"]
---


{{< enter >}}
Halo semuanya!, apakabar? semoga teman-teman yang membaca artikel ini sedang ada dalam kondisi yang baik :D. Kalau saya sih lagi nulis tentang docker ditemenin pacar di sebelah hehe.

Sekarang kita fokus ke judul dari artikel ini sekarang, __*Masa Depan Docker dalam Bahaya?*__ . Bagi beberapa teman yang baru belajar docker pasti hal ini cukup membingungkan tapi saya akan coba membahas masalah ini secara runtut biat temen-temen bisa mendapatkan inti pembicaraan di sini.

## Apa Itu Docker ?

Docker adalah sebuah layanan server virtual berbasis container yang saat ini banyak digunakan oleh pengembang dan bisnis di seluruh dunia. Docker menerapkan konsep container-based virtualization dimana virtualisasi yang dilakukan docker berada pada level Operasi Sistem, berbeda dengan VirtualBox dan VMWare yang melakukan virtualisasi pada level pheripheral.

Jadi dengan docker teman-teman bisa membangun server complex yang attach-able. Bayangkan teman-teman bisa membangun server yang bisa dengan mudah di Deploy dan di Destroy dengan waktu yang sangat cepat. Kalau diibaratkan Docker ini seperti Lego, Jadi teman-teman bisa membangun server dengan sensasi seperti bongkar pasang lego. jadi Docker sangat cocok digunakan untuk sebuah perusahaan yang menerapkan konsep DevOps dalam membangun produknya.

Pada pendekatan penggunaannya Docker lebih baik digunakan untuk kebutuhan pengembangan, bukan untuk kebutuhan produksi. Karena pada awalnya ketika tahun 2016-2017 fokus docker adalah mengembangkan sebuah tools pengembangan yang bisa membuat environment pengembangan sama persis dengan environment production. Untuk lebih lengkapnya teman-teman bisa baca di <link sould be here>

## Bagaimana Docker dari Sisi Bisnis?

Docker adalah pemain besar dalam pasar container based virtualization. Tahun 2017-2018 bisa dibilang adalah taunnya container, pembahasan tentang docker dan kawan-kawannya semakin sering didengar di pertengahan tahun 2018, karena ini docker mendapatkan pendanaan yang tidak main-main. Sampai saat artikel ini ditulis kurang lebih pendanaan docker mencapai $300 Juta!, dengan $300 Juta teman-teman bisa membanjiri malang dengan cireng!!.

Hal tersebut tidak terlepas dari perkembangan Docker yang menjadi tools yang bersahabat untuk perusahaan yang menerapkan CI/CD dalam pengembangan aplikasi mereka. Kemajuan Docker juga dipengaruhi dengan tren DevOps yang semakin hari semakin menjadi di seluruh dunia. Banyak orang yang ingin aplikasi mereka disampaikan ke pengguna mereka menggunakan Docker karena fleksibelitas docker yang tidak main-main.

Pada akhirnya Docker tidak hanya menjadi solusi pengembangan aplikasi namun juga solusi environment produksi dari sebuah aplikasi. Akhirnya muncullah teknologi baru yaitu container Orchestration atau dalam bahasa Indonesia Orkestrasi Kontainer untuk management container sehingga dapat digunakan untuk kebutuhan produksi. Ide yang sangat cemerlang bukan? but it’s the reason of docker fall.

## *The King Has Fallen !*

Ini adalah kabar yang cukup buruk dan mengagetkan untuk beberapa orang, termasuk saya sebagaisalah satu fanboy Docker sendiri. Kabar ini pertama kali saya baca dari salah satu website yaitu Dzone.com dengan judul [Docker (Inc.) Is Dead](https://dzone.com/articles/docker-is-dead) selain itu beberapa website bisnis seperti forbes dan CNBC juga menulis artikel yang senada. Lalu apakah Docker benar-benar mati?.

Banyak artikel di internet yang mentebutkan Docker mengalami kemunduran. Mulai dari Milestone yang tidak lagi se-gahar dulu kemudian isu kegagalan mereka dalam mencapai IPO pada tahun lalu karena investasi yang tidak cukup kendati nilai investasi yang mereka miliki cukup fantastis. Banyak yang tidak menyadari Docker saat ini berlari namun dengan infus dan alat bantu pernafasan saat ini a.k.a sekarat dari sisi bisnis.

## Penyebab Kegagalan Docker

Jika dirinci dan diruntut ada beberapa alasan docker mengalami kesulitan dari sisi bisnis seperti ini, yaitu :

- Docker kalah saing dengan container orchestration lain
- Semakin banyak kompetitor
- Docker sangat tertinggal di Inovasi produk

## Docker kalah saing dengan container orchestration lain

Jadi pada tahun 2014-2016 Docker mengenalkan produk baru mereka yaitu Docker Swarm. Docker Swarm adalah sebuah container orchestration yang memiliki beberapa fitur kusus seperti routing mesh sehingga Docker swarm sangat cocok jika kita gunakan untuk mendeploy sebuah aplikasi yang berbasis micro services. Goal utama dari docker swarm adalah bisa memanage banyak container dalam saat bersamaan dengan mudah dan tidak repot.

Docker swarm terdengar menjanjikan bukan?, namun apa daya ternyata disaat yang hampir bersamaan muncul project serupa yang juga didukung perusahaan besar seperti Google. Yup, there is the big guy kubernetes container orchestration yang didukung oleh komunitas yang lebih besar dengan dukungan platform yang lebih fleksibel. Kubernetes menggebrak pasaran dengan kelebihan-kelebihan yang tidak dimiliki oleh docker swarm. Dari sini lah awal dari kejatuhan Docker semakin nampak, Docker gagal berperang bahkan sebelum perang itu terjadi.

## Semakin Banyak Kompetitor

Dewasa ini semakin banyak produk virualisasi berbasis container yang muali dikenalkan ke publik secara terbuka (open source) maupun enterprise based, dengan begitu bertambah pula saingan dari docker. Ada beberapa produk container based virtualization yang saat ini mulai banyak digunakan oleh pengembang. Diantaranya rkt dari coreOs yang telah diakuisisi oleh redhat foundation dan dijadikan project open adoption software, kemudian ada podman dan lxc yang mulai sering digunakan oleh pengembang belakangan ini.

# Kesimpulan

Dari semua bahasan yang telah ditulis, bukan berarti docker tidak akan digunakan lagi selamanya. Faktanya docker telah menjadi sebuah standar di indsutri. Bahkan saat ini jika diajukan sebuah pertanyaan startup mana yang tidak menggunakan docker? hampir semua startup pasti pernah atau sedang menggunakan docker untuk infrastruktur mereka. Selain itu dukungan komunitas untuk docker juga tidak main-main. Lalu apa yang harus kita khawatirkan?

Meskipun masih terasa jauh, langkah-langkah antisipasi jikalau hal-hal yang berkaitan dengan bisnis membuat pola pengembangan docker berubah juga harus diperhatikan. Bahkan baru-baru ini docker terlah merubah ketentuan dan pembatasan penggunaan [Docker hub](https://hub.docker.com/). Solusi paling sederhana adalah dengan membuat sebuah docker image repository private sendiri.

Itu saja yang kali ini bisa saya sampaikan, drop some comment guys! thx