# KitapDizini

**KitapDizini**, kullanıcıların sahip oldukları kitapları yönetebileceği ve kitaplarda hoşlarına giden alıntıları paylaşabileceği bir platformdur. Bu API, kitap koleksiyonunuzu dijital ortamda düzenlemenize ve etkileyici sözleri saklayarak okuma deneyiminizi zenginleştirmenize olanak tanır.

## Özellikler

- **Kitap Yönetimi**: Kitaplarınızı ekleyin, düzenleyin ve silin.
- **Alıntı Paylaşımı**: Kitaplarda hoşunuza giden sözleri ekleyin ve paylaşın.
- **Veri Formatları**: API, XML ve JSON formatlarını destekler.
- **Kullanıcı Bazlı Veri**: Her kullanıcı kendi kitaplarını ve alıntılarını yönetir.

## Teknolojiler

- **RestEasy**: RESTful servisler için kullanılacak.
- **JPA (Java Persistence API)**: Veritabanı işlemleri için ORM.
- **JAXB ve Jackson2**: XML ve JSON veri dönüşümleri için.
- **PostgreSQL**: Veritabanı olarak kullanılacak.

## Kurulum

### Gereksinimler

- Java 8 veya üzeri
- Maven
- PostgreSQL veritabanı

### Adımlar

1. **Projeyi Klonlayın**:
   ```bash
   git clone https://github.com/cbasanbuga/KitapDizini.git
   cd KitapDizini
