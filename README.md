Proje Raporu: Adam Asmaca Oyunu
Proje Amacı
Bu proje, C programlama dilini kullanarak klasik "Adam Asmaca" oyununu bir bilgisayar ortamında uygulamayı amaçlamaktadır. Oyuncuların gizli bir kelimeyi, belirli bir sayıdaki yanlış tahmin hakkı içinde doğru bir şekilde tahmin etmeye çalışmasını simüle eder. Proje, kullanıcı etkileşimini, döngüleri, dizileri, koşulları ve string işleme yöntemlerini içeren temel programlama becerilerini geliştirmek için tasarlanmıştır.
Genel İşleyiş
1.	Gizli Kelime: Program, tahmin edilmesi gereken kelimeyi (PROGRAM) sabit bir string olarak saklar.
2.	Kullanıcı Girdisi: Kullanıcı bir harf tahmini yapar.
3.	Doğru/Yanlış Tahmin Kontrolü:
o	Eğer tahmin edilen harf gizli kelimede bulunuyorsa, ilgili konumlarda gösterilir.
o	Eğer harf gizli kelimede yoksa, kullanıcının kalan deneme hakkı bir azaltılır.
4.	Oyun Sonucu:
o	Oyuncu gizli kelimeyi tahmin ederse, kazandığı bildirilir.
o	Yanlış tahmin hakları biterse, oyun sona erer ve kaybedildiği belirtilir.

Kullanılan Fonksiyonlar
1.	displayProgress()
o	Bu fonksiyon, gizli kelimenin mevcut durumunu ekrana yazdırır. Henüz tahmin edilmemiş harfler _ sembolüyle gösterilir.
o	Örnek Çıktı:
makefile
Kodu kopyala
Kelime: _ _ _ _ _ _ _
2.	checkWin()
o	Bu fonksiyon, oyuncunun tüm harfleri doğru tahmin edip etmediğini kontrol eder.
o	Kullanıcı tarafından tahmin edilen kelime (guessed) ile gizli kelime (word) karşılaştırılır. Eğer eşitse, oyun kazanılmıştır.
Oyun Akışı Örneği
1.	Başlangıç Mesajı
Adam Asmaca Oyununa Hoşgeldiniz!
Kelime: _ _ _ _ _ _ _
Bir harf tahmin edin: 

2.	Doğru Tahmin
Doğru tahmin ettiniz!
Kelime: P _ O _ _ _ _
3.	Yanlış Tahmin

Yanlış tahmin! Kalan deneme hakkı: 5
Kelime: _ _ _ _ _ _ _
4.	Sonuç
o	Kazanma:
o	Tebrikler! Kelimeyi doğru tahmin ettiniz: PROGRAM
o	Kaybetme:
Üzgünüm, kaybettiniz! Kelime: PROGRAM

Geliştirme Önerileri
1.	Kelime Havuzu
o	Gizli kelimenin rastgele seçilmesi için bir kelime havuzu oluşturulabilir.
2.	Grafiksel Arayüz
o	ASCII sanatını kullanarak adam asmaca şekli eklenebilir.
3.	Skor Tablosu
o	Kullanıcıya doğru tahminler ve kalan haklarına göre puan sistemi eklenebilir.
Sonuç
Bu proje, basit bir Adam Asmaca oyununun temel işlevselliğini başarıyla uygulamıştır. Harf tahmini, kalan hak kontrolü ve oyun sonu mesajları gibi özelliklerle temel bir oyun yapısı oluşturulmuştur. Proje, hem eğlenceli bir oyun geliştirme süreci hem de programlama becerilerini pekiştirmek için etkili bir araçtır.

