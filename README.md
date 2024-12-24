# Telefon Rehberi Uygulaması README

## Proje Açıklaması
Bu proje, kullanıcıların telefon rehberini yönetebileceği basit bir Python uygulamasıdır. Kullanıcılar bu uygulama ile rehberlerine kişi ekleyebilir, kişi silebilir, kişi arayabilir ve tüm rehberlerini listeleyebilirler.

## Özellikler
- **Kişi Ekleme**: Kullanıcılar, telefon rehberine yeni bir kişi ekleyebilir. İsim ve numara bilgisi girilir.
- **Kişi Silme**: Kullanıcılar, rehberden mevcut bir kişiyi silebilir. Eğer kişi bulunamazsa, hata mesajı gösterilir.
- **Kişi Arama**: Kullanıcılar, rehberdeki bir kişiyi arayabilir. Kişi bulunduğunda numara görüntülenir.
- **Tüm Kişileri Listeleme**: Kullanıcılar, rehberdeki tüm kişileri ve numaralarını listeleyebilir.
- **Çıkış**: Uygulamadan çıkış yapılabilir.

## Kullanım
1. Uygulamayı çalıştırdığınızda bir ana menü ile karşılaşırsınız.
2. Menüyü kullanarak aşağıdaki işlemleri yapabilirsiniz:
    - **Kişi Ekle**: Yeni bir kişi eklemek için `1` tuşuna basın.
    - **Kişi Sil**: Rehberden kişi silmek için `2` tuşuna basın.
    - **Kişi Ara**: Bir kişiyi aramak için `3` tuşuna basın.
    - **Tüm Kişileri Listele**: Rehberdeki tüm kişileri görmek için `4` tuşuna basın.
    - **Çıkış**: Uygulamadan çıkmak için `5` tuşuna basın.

## Kod Açıklaması
- `telefon_rehberi` sözlüğü, kişilerin isimlerini anahtar (key) ve telefon numaralarını değer (value) olarak saklar.
- `kisi_ekle(isim, numara)` fonksiyonu, verilen ismi ve numarayı telefon rehberine ekler.
- `kisi_sil(isim)` fonksiyonu, rehberden verilen isimdeki kişiyi siler.
- `kisi_ara(isim)` fonksiyonu, rehberdeki kişiyi arar ve varsa numarasını gösterir.
- `tum_kisileri_listele()` fonksiyonu, rehberdeki tüm kişileri ve numaralarını listeler.

## Gereksinimler
- Python 3.x

## Çalıştırma
Uygulamayı çalıştırmak için Python yüklü bir ortamda bu dosyayı çalıştırabilirsiniz. Python dosyasını terminal veya komut satırında çalıştırarak uygulamayı başlatabilirsiniz.

```bash
python telefon_rehberi.py
```

Uygulama, kullanıcıdan seçimler alarak işlemleri gerçekleştirecektir.

## Katkı Sağlamak
Projeye katkı sağlamak isterseniz, pull request (PR) oluşturabilirsiniz. Herhangi bir sorunuz veya öneriniz varsa, lütfen issue (sorun) açarak bizimle iletişime geçin.

## Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
