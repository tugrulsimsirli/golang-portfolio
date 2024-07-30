# Projeler ve Görev Listesi

Bu projeler, Golang ile backend geliştirme becerilerini sergilemek ve çeşitli yazılım mimarilerini uygulamak için tasarlanmıştır. Her bir proje belirli teknolojiler ve mimari yaklaşımlar kullanılarak geliştirilmiştir.

## 1. Pastebin Klonu

**Amaç**: Kullanıcıların metin veya kod parçacıklarını paylaşabileceği basit bir backend uygulaması.

**Teknolojiler**: Gin veya Echo, Gorm, PostgreSQL/MongoDB

**Mimari**: Modüler Mimari ve Repository Pattern

**Görevler**:
- [ ] Kullanıcı kimlik doğrulama (JWT)
- [ ] CRUD işlemleri (metin/kod parçacığı)
- [ ] Paylaşım linki oluşturma
- [ ] Görüntülenme istatistikleri toplama
- [ ] Dokümantasyon

## 2. RESTful API İle Kitap Yönetim Sistemi

**Amaç**: Basit bir kitap yönetim sistemi API'si.

**Teknolojiler**: Gin veya Echo, Gorm, PostgreSQL

**Mimari**: RESTful Mimari ve Service Layer Pattern

**Görevler**:
- [ ] Kullanıcı kimlik doğrulama (JWT)
- [ ] CRUD işlemleri (kitap)
- [ ] Arama ve filtreleme
- [ ] Service Layer
- [ ] Dokümantasyon

## 3. Görev Yönetim Sistemi (To-Do List)

**Amaç**: Kullanıcıların görevlerini yönetebileceği basit bir backend uygulaması.

**Teknolojiler**: Gin veya Echo, Gorm, PostgreSQL

**Mimari**: Clean Architecture ve CQRS (Command Query Responsibility Segregation)

**Görevler**:
- [ ] Kullanıcı kimlik doğrulama (JWT)
- [ ] CRUD işlemleri (görev)
- [ ] Kategoriler
- [ ] CQRS
- [ ] Dokümantasyon

## 4. Gerçek Zamanlı Chat Uygulaması

**Amaç**: Gerçek zamanlı mesajlaşma özelliklerine sahip bir chat uygulaması.

**Teknolojiler**: Gin veya Echo, Redis (veya PostgreSQL), WebSocket

**Mimari**: Event-Driven Architecture ve Microservices

**Görevler**:
- [ ] Kullanıcı kimlik doğrulama (JWT)
- [ ] WebSocket
- [ ] Mesaj geçmişi
- [ ] Event-Driven Architecture
- [ ] Dokümantasyon

## 5. Finansal İşlemler Takip Uygulaması

**Amaç**: Kullanıcıların gelir ve gider işlemlerini takip edebileceği bir uygulama.

**Teknolojiler**: Gin veya Echo, Gorm, PostgreSQL

**Mimari**: Domain-Driven Design (DDD) ve Repository Pattern

**Görevler**:
- [ ] Kullanıcı kimlik doğrulama (JWT)
- [ ] CRUD işlemleri (gelir/gider)
- [ ] Raporlama
- [ ] DDD
- [ ] Dokümantasyon
