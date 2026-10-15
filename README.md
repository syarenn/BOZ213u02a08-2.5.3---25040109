# BOZ213u02a08-25040109
# Python Yorum Satırları 

## 1. Proje ne yapıyor?

Bu çalışma, Nesne Tabanlı Programlama dersi kapsamında tüm öğrencilere verilen bir Python laboratuvar uygulamasıdır.

Laboratuvarın amacı, Python'da yorum satırlarının doğru kullanımını öğrenmek, gereksiz veya hatalı açıklamaları belirlemek ve mevcut kodu PEP 8 yazım ilkelerine uygun şekilde düzenlemektir.

Örnek program, belirlenen saat değerini saniyeye dönüştürmektedir

## 2. Proje neden faydalıdır?

Bu proje, Python'da temiz ve okunabilir kod yazma becerisinin geliştirilmesine yardımcı olur.

Özellikle aşağıdaki konuların öğrenilmesini sağlar:

- Yorum satırlarının doğru kullanılması.
- Gereksiz açıklamaların kaldırılması.
- Hatalı yorumların tespit edilmesi.
- Anlamlı değişken isimlerinin kullanılması.
- PEP 8 kod yazım ilkelerinin uygulanması.

### PEP 8 ile İlişkisi

PEP 8, Python kodlarının daha okunabilir ve tutarlı yazılmasını amaçlayan bir stil rehberidir.

Bu projede PEP 8'in özellikle **Comments** ve **Naming Conventions** bölümleri dikkate alınmıştır.

Orijinal kodda `a = 2` olarak tanımlanmasına rağmen son yorum satırında 3 saatlik hesaplamadan bahsedilmiştir.

Bu tutarsızlık giderilmiş ve kodla çelişen yorum satırı kaldırılmıştır.

Ayrıca programın iki gün önce yazıldığına ilişkin gereksiz açıklama çıkarılmıştır.

`a` değişkeni `hours`, `seconds` değişkeni ise `seconds_per_hour` olarak yeniden adlandırılmıştır.

Böylece kod daha anlaşılır hâle getirilmiştir.

## 3. Kullanıcılar projeyi nasıl çalıştırabilir?

### Kullanılan Teknolojiler
- Python 3
- Python IDLE

### Programın Çalıştırılması

1. Python 3 bilgisayara yüklenir.
2. Python IDLE açılır.
3. `main.py` dosyası açılır.
4. F5 tuşuna basılarak program çalıştırılır.
5. Hesaplanan saniye değeri ekranda görüntülenir.

### Programın Çalışma Mantığı

Programda saat değeri 2 olarak belirlenmiştir.

Bir saat 3600 saniye olduğundan:

**2 × 3600 = 7200 saniye**

### Beklenen Çıktı

```text
Hours: 2
Seconds in Hours: 7200
```

### Öğrenilen Python Kavramları
- Değişkenler
- Yorum satırları (`#`)
- Çarpma operatörü (`*`)
- `print()` fonksiyonu
- Anlamlı değişken isimlendirme
- PEP 8 kod yazım kuralları

## 4. Kullanıcılar nereden yardım alabilir?

Proje hakkında soru, öneri veya hata bildirimleri için GitHub Issues bölümü kullanılabilir.

Python programlama dili ve PEP 8 standartları hakkında ayrıntılı bilgi için Python'un resmî dokümantasyonu incelenebilir.

## 5.Projeyi kim geliştirir ve sürdürür?

Bu laboratuvar çalışması, Nesne Tabanlı Programlama dersi kapsamında tüm öğrencilere verilen ortak bir uygulamadır.

Çalışmada kullanılan başlangıç kodu ders materyali olarak sunulmuştur. Kod üzerinde gerekli düzenlemeler yapılarak gereksiz ve hatalı yorum satırları kaldırılmış, değişken isimleri PEP 8 ilkeleri doğrultusunda iyileştirilmiştir.

Düzenlenen kodun GitHub ortamına aktarılması ve belgelendirilmesi bireysel olarak gerçekleştirilmiştir.
## Kaynakça

Van Rossum, G., Warsaw, B. ve Coghlan, A. (2001). *PEP 8 – Style Guide for Python Code*. Python Enhancement Proposals.

https://peps.python.org/pep-0008/

GitHub Docs. *About READMEs*.

https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

## Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Ayrıntılı bilgi için `LICENSE` dosyasına bakılabilir.
