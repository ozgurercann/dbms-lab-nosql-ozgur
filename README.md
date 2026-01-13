# NoSQL Performans Analizi: Redis, Hazelcast ve MongoDB

Bu proje, farklı NoSQL veri modellerinin (Key-Value, IMDG, Document) performansını karşılaştırmak için geliştirilmiş bir Spring Boot uygulamasıdır.

## 📌 Proje Özellikleri
- Uygulama başlangıcında **10.000 adet** öğrenci kaydı oluşturulur.
- Kayıtlar eş zamanlı olarak **Redis**, **Hazelcast** ve **MongoDB** veritabanlarına yazılır.
- Her veritabanı için özel endpointler üzerinden veri çekme işlemi yapılır.

## 🚀 Çalıştırma Talimatları
1. **Veritabanlarını Ayağa Kaldır:** `docker-compose up -d`
2. **Uygulamayı Derle ve Çalıştır:** `mvn clean compile` ve `mvn exec:java -Dexec.mainClass="app.Main"`

## 📊 Test Sonuçları (Siege)
Proje kapsamında 10 eş zamanlı kullanıcı ile toplam 1000 istek gönderilerek yapılan testlerin sonuçları rapor dosyasında ve videoda sunulmuştur.

- **GitHub:** https://github.com/ozgurercann/dbms-lab-nosql-ozgur
