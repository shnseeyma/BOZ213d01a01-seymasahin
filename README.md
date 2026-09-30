# surey-bul
Yolculuk Süresi Hesaplama AracıBu Python projesi, girilen mesafe ve hız değerlerini temel fizik formülüyle ($Zaman = Mesafe / Hız$) işleyerek hedefe ne kadar sürede varılacağını saniye, dakika ve saniye cinsinden hesaplar.ÖzelliklerBelirtilen mesafeyi ve hızı değişken olarak alır.Matematiksel formülü doğrudan uygulayarak toplam saniyeyi bulur.Toplam saniyeyi anlaşılır bir şekilde dakika ve saniye formatına dönüştürür.Sade ve kolay anlaşılır Python kodu sunar.KullanımProjeyi çalıştırmak için bilgisayarınızda Python yüklü olması yeterlidir. Aşağıdaki kodu bir Python dosyasında (hesaplama.py) çalıştırabilirsiniz:# Değerleri tanımlayalım
mesafe = 2000
hiz = 10

# Formülü uygulayalım: Zaman = Mesafe / Hız
zaman_saniye = mesafe / hiz

# Süreyi dakika ve saniyeye bölelim
dakika = int(zaman_saniye // 60)
saniye = int(zaman_saniye % 60)

# Sonucu ekrana yazdıralım
print("Toplam Saniye:", zaman_saniye)
print("Süre:", dakika, "dakika", saniye, "saniye")
GereksinimlerPython 3.x
