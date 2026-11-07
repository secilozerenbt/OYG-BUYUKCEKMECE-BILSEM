# OYG-BUYUKCEKMECE-BILSEM

**Büyükçekmece Bilim ve Sanat Merkezi · OYG Python Atölyesi**

## Ödev 01 · For döngüsü ile toplama

**Öğretmen: Seçil Özeren**

Bu ödevde `for` döngüsüyle sayıları dolaşacak, bir değişkende toplam tutacak ve `%` operatörüyle bölme işleminden kalan bulacaksınız.

## Ödeve katılma

İlk kez katılıyorsanız [öğretmen şablonunu açınız](https://github.com/secilozerenbt/OYG-BUYUKCEKMECE-BILSEM). Kendi deponuzu daha önce oluşturduysanız aşağıdaki genel yönergeye geçebilirsiniz.

1. Öğretmen şablonunun üstündeki **Use this template → Create a new repository** seçeneğine tıklayınız.
2. **Owner** alanında kendi hesabınızı seçiniz. Deponuza `python-for-dongusu-odevim` adını veriniz ve görünürlüğünü **Private** olarak ayarlayınız.
3. **Create repository from template** düğmesine tıklayınız. Böylece ödev dosyaları kendi deponuza kopyalanır.
4. Kendi deponuzda **Settings** bölümündeki erişim ayarlarından öğretmeninizi ortak çalışan olarak davet ediniz. GitHub kullanıcı adı **`secilozerenbt`** olan öğretmen hesabını seçiniz.
5. Kendi deponuzun bağlantısını öğretmeninize sınıfta kullanılan iletişim kanalından iletiniz. Bu bağlantı, katılım ve teslim takibi için kullanılacaktır.

İndirme, çalıştırma ve yükleme adımları için [Öğrenci Rehberi](OGRENCI_REHBERI.md) dosyasını okuyunuz.

## Genel yönerge

Aşağıdaki her madde için **Python dilinde, `for` döngüsü kullanarak ayrı bir program yazınız.** Tüm sorularda **1 ve 100 sayıları aralığa dâhildir.** Sonuçları açıklayıcı bir mesajla ekrana yazdırınız.

### 1. 1’den 100’e kadar olan sayıların toplamı

`for` döngüsüyle 1’den 100’e kadar olan bütün tam sayıları dolaşarak toplamlarını hesaplayınız.

İlk çözüm dosyası: [soru1_sayilarin_toplami.py](ilk-cozum/soru1_sayilarin_toplami.py)

### 2. 1’den 100’e kadar olan çift sayıların toplamı

`for` döngüsünü 2’den başlayıp ikişer artacak şekilde düzenleyerek çift sayıların toplamını hesaplayınız.

İlk çözüm dosyası: [soru2_cift_sayilarin_toplami.py](ilk-cozum/soru2_cift_sayilarin_toplami.py)

### 3. 1’den 100’e kadar olan tek sayıların toplamı

`for` döngüsünü 1’den başlayıp ikişer artacak şekilde düzenleyerek tek sayıların toplamını hesaplayınız.

İlk çözüm dosyası: [soru3_tek_sayilarin_toplami.py](ilk-cozum/soru3_tek_sayilarin_toplami.py)

### 4. 1’den 100’e kadar olan sayıların 3’e bölümünden kalanların toplamı

`for` döngüsüyle her sayının 3’e bölümünden kalanı bulunuz ve bu kalanları toplayınız. Kalanı bulmak için **`%` operatörünü** kullanınız. Bu soruda `for` döngüsüne ek olarak **`if` koşulunu da kullanabilirsiniz.**

İlk çözüm dosyası: [soru4_kalanlarin_toplami.py](ilk-cozum/soru4_kalanlarin_toplami.py)

**Hatırlatma:** Toplamı tutacak değişkeni döngü başlamadan önce sıfır olarak tanımlayınız. Döngü içinde bu değişkeni güncelleyiniz ve toplamı döngü bittikten sonra ekrana yazdırınız.

## Tekrar çalışması

Her soruyu çözüp programınızın doğru çalıştığını kontrol ettikten sonra, **o sorunun kodunu kopyala-yapıştır yapmadan 5 kez yeniden yazınız.** Mümkün olduğunca önceki çözümünüze bakmadan yazmayı deneyiniz. Her tekrarda programı çalıştırarak sonucunu kontrol ediniz ve yazdığınız satırların ne işe yaradığını açıklayabilmeye çalışınız.

| Aşama | Çalışılacak klasör | Dosya sayısı |
| --- | --- | --- |
| İlk çözümler | [ilk-cozum](ilk-cozum) | 4 |
| 1. tekrar | [tekrarlar/tekrar-1](tekrarlar/tekrar-1) | 4 |
| 2. tekrar | [tekrarlar/tekrar-2](tekrarlar/tekrar-2) | 4 |
| 3. tekrar | [tekrarlar/tekrar-3](tekrarlar/tekrar-3) | 4 |
| 4. tekrar | [tekrarlar/tekrar-4](tekrarlar/tekrar-4) | 4 |
| 5. tekrar | [tekrarlar/tekrar-5](tekrarlar/tekrar-5) | 4 |

İlk çözümler ve tekrarlarla birlikte **toplam 24 Python dosyası** tamamlayacaksınız. Tekrar, programın sonucunu ekrana beş kez yazdırmak anlamına gelmez; kodu ayrı dosyalara yeniden yazmanız beklenir.

## Sonucunuzu kontrol etme

- Önce programınızı 1–10 gibi daha küçük bir aralıkta deneyiniz ve sonucu elle hesapladığınız değerle karşılaştırınız.
- Kontrolden sonra aralığı yeniden 1–100 olacak şekilde düzenleyiniz.
- `range()` içinde bitiş değerinin aralığa dâhil olmadığını hatırlayınız.
- Son soruda sayıları değil, her sayının 3’e bölümünden kalan değerleri topladığınızı kontrol ediniz.

## Teslim

1. Çalışmalarınızı kendi deponuza, klasör düzenini koruyarak yükleyiniz.
2. [TESLIM.md](TESLIM.md) dosyasındaki kontrol listesini tamamlayınız.
3. Öğretmeninize erişim daveti gönderdiğinizden emin olunuz. Özel depolar, davet kabul edilmeden öğretmeniniz tarafından görüntülenemez.
4. Kendi depo bağlantınızı öğretmeninize iletip ödevinizi tamamladığınızı bildiriniz.

Teslim edilecekler: **24 adet `.py` dosyası ve doldurulmuş `TESLIM.md`.**
