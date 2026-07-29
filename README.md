# CRM-Database-Application
A desktop-based Customer Relationship Management (CRM) application built with C# and SQL Server.


#  Mobility & Ride-Hailing Database Management System
A comprehensive, relational database architecture designed for a ride-hailing and mobility service (similar to Uber/Bolt), featuring dynamic user segmentation, location-based matching, multi-tiered incentives, and automated commission logic.

---

## 📌 Project Overview (English)

** This project is an end-to-end database platform developed to manage complex mobility operations. Built upon Industrial Engineering and Data Architecture principles, the system handles dynamic pricing/discounts, multi-tiered driver commissions, geolocation-based driver-trip matching, and comprehensive feedback management.

### 🚀 Key Features & Business Logic
* **Dynamic Passenger Segmentation:** Classifies riders into Bronze, Silver, Gold, and VIP tiers based on trip volume and ratings, unlocking automated discounts (e.g., 3% per trip for VIPs).
* **Driver Performance & Commission Tiers:** Segments drivers into Bronze, Silver, and Gold tiers based on completed trips and performance ratings. Higher tiers benefit from lower platform commission fees.
* **Geofenced Service Matching (`Districts` & `DriverServiceAreas`):** Matches ride requests with drivers based on preferred operational districts (e.g., Izmir Bornova, Bayrakli) to optimize notification delivery.
* **Comprehensive Trip Architecture (`Trips`):** Integrates passenger, driver, vehicle, and origin-destination district IDs for granular trip tracking.
* **Financial & Rating Systems (`Payments` & `Ratings`):** Handles multi-channel payments, trip issue logs, and mutual rating/review systems between drivers and passengers.
* **Promotions & Incentive Engines:** Manages targeted passenger campaigns and driver incentive awards (`Campaigns`, `Incentives`), supporting segment-specific targeting via `TargetSegmentID`.
* **Flexible Support Tickets (`SupportRequests`):** Supports both trip-specific and general system complaints with optional relation parameters.
* **Audit Trail (`UserSegmentTransitions`):** Tracks historical segment changes and progression for all users over time.

---

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

**Bu proje ulaşım ve araç çağırma (Uber/Martı TAG benzeri) operasyonlarını yönetmek üzere tasarlanmış kapsamlı bir ilişkisel veritabanı sistemidir. Endüstri mühendisliği ve veri mimarisi ilkeleri doğrultusunda geliştirilen bu proje; dinamik fiyatlandırma, sürücü komisyon kademelendirmesi, bölge bazlı bildirim eşleştirmesi ve kampanya yönetim süreçlerini kapsar.

### 🚀 Öne Çıkan Sistem Özellikleri
* **Dinamik Yolcu Segmentasyonu:** Yolcuları sürüş sayısı ve puanına göre Bronze, Silver, Gold ve VIP olarak ayırır; segmente özel otomatik indirim tanımlar.
* **Sürücü Performansı ve Komisyon Modeli:** Sürücüleri sürüş ve puan kriterlerine göre kademelendirir. Segment yükseldikçe platformun sürücüden aldığı komisyon oranı düşer.
* **Bölge Bazlı Eşleştirme (`Districts` & `DriverServiceAreas`):** Sürücülerin hizmet vermeyi kabul ettiği ilçeleri (Örn: İzmir Bornova, Bayraklı) eşleştirerek sürücülere doğru bölge bildirimlerinin gitmesini sağlar.
* **Sürüş Yönetimi (`Trips`):** Yolcu, sürücü, araç, başlangıç ve bitiş ilçe verilerini bağlayan merkezi sürüş mimarisi.
* **Ödeme, Puanlama ve Destek Mimarisi:** Karşılıklı puan/yorum mekanizması (`Ratings`), ödeme detayları (`Payments`) ve yolculuktan bağımsız da oluşturulabilen esnek destek talebi (`SupportRequests`) yapısı.
* **Segment Geçiş Geçmişi (`UserSegmentTransitions`):** Yolcu ve sürücülerin zaman içindeki statü değişimlerini izleyen denetim izi.

---

## 🛠️ Kullanılan Teknolojiler
* **Database:** SQL Server / Relational Database (RDBMS)
* **Application / UI:** C# Windows Forms / .NET
