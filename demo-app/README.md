ReactiveMongo sampleApp
=======================

2013 Ozgur Yazılım ve Linux Günleri
ReactiveMongo Workshop Etkinliği
Demo Uygulaması


Nedir?
------
* Bu uygulama Play2 Framework üzerinde geliştirilmiştir.
* Veritabanı MongoDB dir, veritabanı bağlantısı için ReactiveMongo sürücüsünü kullanır.
* Websocket bağlantısı üzerinden clientlardan alınan mesajları veritabanına yazar.
* Eş zamanlı olarak veritabanındaki değişikliği takip ederek yeni verileri tüm clientlara geri gönderir.


Uygulama Gereksinimleri
-----------------------
* > Java 1.6 
* sbt : http://www.scala-sbt.org/release/docs/Getting-Started/Setup.html
* Play2 Framework : http://www.playframework.com/download
* MongoDB (isteğe bağlı): http://www.mongodb.org/downloads (Uygulamanın bağlanabileceği bir MongoDB servisi halihazırda mevcut)
* İnternet bağlantısı(kurulum için, ayrıca uzak MongoDB serverına bağlanılacaksa)

Kurulum
-------
> `git clone https://github.com/kubudi/oylg2013-demoApp.git`  
> `oylg2013-demoApp/`  
> `sbt`  
> `run`  
> `http://localhost:9000`  
