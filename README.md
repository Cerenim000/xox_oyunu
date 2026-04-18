Python ile Tic-Tac-Toe (XOX) Oyunu
Bu proje, Python programlama dili kullanılarak terminal (komut satırı) üzerinden oynanabilen basit bir Tic-Tac-Toe (XOX) oyunudur.

Oyunun Özellikleri
İki Kişilik Oynanış: Oyuncular sırayla 'X' ve 'O' işaretlerini yerleştirir.
Dinamik Tahta: Her hamleden sonra oyun tahtası güncellenerek ekrana yazdırılır.
Kazanma Kontrolü: Yatay, dikey ve çapraz olmak üzere tüm kazanma kombinasyonları otomatik olarak kontrol edilir.
Hata Yönetimi: Dolu bir hücreye hamle yapılmaya çalışıldığında kullanıcıyı uyarır.

Nasıl Çalıştırılır?
Bilgisayarınızda Python yüklü olduğundan emin olun.
Dosyayı indirin veya bu depoyu klonlayın.
Terminal üzerinden şu komutu çalıştırın:
python oyun_dosyanizin_adi.py

Nasıl Oynanır?
Oyun başladığında sizden önce yukarıdan aşağıya (satır), sonra soldan sağa (sütun) koordinatlarını girmeniz istenir.
Koordinatlar 1, 2 veya 3 olmalıdır.
Oyundan çıkmak isterseniz koordinat kısmına q yazmanız yeterlidir.

Kod Yapısı Hakkında Teknik Detaylar
Tahta Yönetimi: Liste içinde listeler (nested lists) kullanılarak 3x3'lük bir matris oluşturulmuştur.
Kazanma Algoritması: kazanma_ölçütleri adlı bir liste içinde tüm koordinat kombinasyonları tutulur ve her hamlede oyuncunun koordinat listesiyle karşılaştırılır.
Görsel Düzen: expandtabs() ve center() metodları ile terminalde daha okunaklı bir arayüz sağlanmıştır.
