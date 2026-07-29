# CRM-Database-Application
A desktop-based Customer Relationship Management (CRM) application built with C# and SQL Server.


#  Mobility & Ride-Hailing Database Management System
A comprehensive, relational database architecture designed for a ride-hailing and mobility service (similar to Uber/Bolt), featuring dynamic user segmentation, location-based matching, multi-tiered incentives, and automated commission logic.

---

## 📌 Project Overview (English)

** This project is an end-to-end mobility platform combining a robust SQL relational database with a C# Windows Forms Executive Admin Panel. Designed with Industrial Engineering and Data Analytics principles, the system processes ride-hailing workflows, driver-passenger segmentations, financial performance, and live database queries.


### 🚀 Key Features & C# Admin Panel Capabilities
* **Executive Login & Role Architecture:** Fullscreen splash screen followed by role selection and secure admin authentication.
* **Passenger & Driver Management:** Dynamic filtering via DataGridView and ComboBoxes based on tier segments (Bronze, Silver, Gold, VIP) with real-time total count labels.
* **Risk Management Engine:** One-click filtering to highlight high-risk drivers with performance ratings below 3.0.
* **Promotional Dashboards:** Centralized campaign and driver incentive tracking with live active count indicators.
* **Executive Analytics & Data Visualization:**
  * Trip volume distribution by cities.
  * Passenger gender demographic distribution.
  * Top 5 drivers generating the highest revenue.
  * Hourly demand peak intensity charts during the day.
  * Real-time platform total revenue and total distance metrics.
* **Live Database Query Console:** Built-in SQL terminal allowing execution of custom relational queries (e.g., `SELECT * FROM Passengers WHERE City='İstanbul'`) directly from the UI.


## 🛠️ Relational Database Schema / Tables

* **`Passengers` / `PassengerSegments`:** Rider profiles, ratings, and tier constraints.
* **`Drivers` / `DriverSegments` / `Vehicles`:** Driver profiles, vehicle specs, and tier-based commission rules.
* **`Districts` / `DriverServiceAreas`:** Operational zones and driver coverage preferences.
* **`Trips`:** Core operational logs linking passengers, drivers, vehicles, and start/end locations.
* **`Payments` / `Ratings`:** Transaction details, payment errors, and mutual feedback scores.
* **`Campaigns` / `Incentives` / `Assignments`:** Promotional engines for riders and performance bonuses for drivers.
* **`SupportRequests`:** Centralized customer support and issue-tracking system.
* **`UserSegmentTransitions`:** Log history for user tier upgrades/downgrades.

---

## 📌 Proje Özeti (Türkçe)

**Bu proje ulaşım ve araç çağırma (Uber/Martı TAG benzeri) operasyonlarını yönetmek üzere tasarlanmış kapsamlı bir ilişkisel veritabanı ve **C# Windows Forms Yönetici Paneli** entegrasyonuna sahip kapsamlı bir mühendislik sistemidir. Endüstri mühendisliği ve veri mimarisi ilkeleri doğrultusunda geliştirilen bu proje; dinamik fiyatlandırma, sürücü komisyon kademelendirmesi, bölge bazlı bildirim eşleştirmesi ve kampanya yönetim süreçlerini kapsar.

### 🚀 C# Yönetici Paneli ve Sistem Özellikleri
* **Gelişmiş Yönetici Arayüzü:** Açılış ekranı (Splash Screen), rol seçimi ve şifreli güvenli admin girişi.
* **Yolcu ve Sürücü Segmentasyonu:** DataGridView ile bağlanan veritabanı üzerinden segmente göre (Bronze, Silver, Gold, VIP) anlık listeleme ve toplam kişi sayısı sayaçları.
* **Yüksek Risk Grubu Tespiti:** Puanı 3.0’ın altında olan sürücüleri tek tıkla listeleyen risk yönetim butonu.
* **Kampanya ve Teşvik Paneli:** Aktif kampanya ve teşviklerin anlık sayısal takibi.
* **İş Zekası ve Grafik Analizleri:**
  * Şehirlere göre toplam sefer sayıları grafiği.
  * Yolcu cinsiyet dağılımı analizi.
  * En yüksek ciro sağlayan ilk 5 sürücü sıralaması.
  * Gün içindeki saatlik talep yoğunluk grafiği.
  * Platform toplam cirosu ve kat edilen toplam mesafe göstergeleri.
* **Canlı Veritabanı Konsolu:** Uygulama içinden doğrudan SQL sorguları çalıştırmaya olanak tanıyan entegre konsol arayüzü.

---


## 🛠️ Kullanılan Teknolojiler
* **Database:** SQL Server (Relational Database - RDBMS)
* **Application / UI:** C# (.NET Framework / Windows Forms)
* **Analytics:** Chart Controls & DataGridView Integration
