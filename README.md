# ApiProjeKampi

**ASP.NET Core Web API** ve **Entity Framework Core** ile geliştirilmiş, bir restoran web sitesinin arka ucunu oluşturan REST API projesi. Eğitim kampı kapsamında, ders ders ilerlenerek geliştirilmektedir.

> 🚧 Durum: Geliştirme devam ediyor

## Teknolojiler

- ASP.NET Core Web API (.NET 6)
- Entity Framework Core (Code First, Migrations) · SQL Server
- Swagger / OpenAPI

## Varlıklar

`Category` · `Product` · `Chef` · `Service` · `Feature` · `Reservation` · `Testimonial` · `Image` · `Message` · `Contact`

## Endpoint'ler

| Controller | İşlemler |
|---|---|
| `CategoriesController` | Listeleme, ekleme, silme, güncelleme, tekil getirme |
| `ChefsController` | Listeleme, ekleme, silme, güncelleme, tekil getirme |

## Çalıştırma

```bash
cd ApiProjeKampi.WebApi
dotnet ef database update
dotnet run
```

Uygulama açıldığında Swagger arayüzü `/swagger` adresinden incelenebilir.
