# E-Commerce Web Application — Frontend

Bu proje, modern ve ölçeklenebilir bir **e-ticaret web uygulamasının Angular tabanlı frontend** katmanıdır. Kullanıcıların ürünleri görüntüleyebildiği, sepete ekleyebildiği ve sipariş oluşturabildiği; yöneticilerin ise ürün ve kategori yönetimi yapabildiği **tam özellikli bir e-ticaret sistemi** sunar.

**Backend Repository:** `ECommerceSiteApi` (ASP.NET Core REST API)

---

## Features

### User Side
- Kullanıcı kayıt & giriş işlemleri
- Ürün listeleme ve kategori bazlı filtreleme
- Ürün detay sayfası
- Sepet yönetimi
- Sipariş oluşturma

### Admin Panel
- Ürün ekleme / silme / güncelleme
- Kategori yönetimi
- Siparişleri görüntüleme

### Core System
- Angular Guards ile yetkilendirme
- HTTP Interceptors ile token yönetimi
- Modüler mimari yapı
- RESTful API entegrasyonu
- Responsive tasarım

---

## Tech Stack
- Angular 17
- TypeScript
- RxJS
- Angular Router
- RESTful API integration
- HTML5 / CSS3

---

## Project Structure

```text
src/app
├── category-list
├── product-list
├── main-layout
├── menu
├── modules
├── services
├── models
├── guards
├── interceptors
├── app-routing.module.ts
├── app.component.ts
└── app.module.ts
```

---

## Getting Started

### Prerequisites
- Node.js (LTS)
- Angular CLI

### Installation
npm install


### Environment Configuration
`src/environments/environment.ts`
export const environment = {
apiUrl: 'https://localhost:5001/api
'
};


### Run (Development)
Application runs at:
http://localhost:4200


### Build
ng build
Build çıktıları `dist/` klasörüne oluşturulur.

---

## API Entegrasyonu

Uygulama, ASP.NET Core backend ile RESTful servisler üzerinden haberleşir.  
Tüm ürün, kategori, kullanıcı ve sipariş işlemleri API uç noktaları üzerinden gerçekleştirilir.  
Yetkilendirme işlemleri route guard’lar ve HTTP interceptor’lar ile yönetilir.
