Genel Bakış:
Bu Java programı basit bir konsol tabanlı Mayın Tarlası oyununu uygular. Oyun, gizli mayınlarla dolu bir mayın tarlası oluşturur ve oyuncunun amacı, bir mayına çarpmadan tüm güvenli hücreleri ortaya çıkarmaktır. Oyuncu, bir hücrenin içeriğini ortaya çıkarmak için satır ve sütun koordinatları girer ve oyun, seçilen hücreye komşu mayın sayısı hakkında geri bildirim sağlar.


Oyun Kuralları:

Satır ve sütun koordinatlarını girerek bir hücrenin içeriğini ortaya çıkarın.
Oyun tahtası, açılmamış hücreler için "-" gösterecektir.
Mayınlar "*" ile temsil edilir.
Sayılar, bir hücreyi çevreleyen mayın sayısını gösterir.
Oyun, tüm güvenli hücreler ortaya çıkarıldığında veya bir mayına çarpıldığında sona erer.


Kod Yapısı:
MineSweeper Sınıfı Özellikleri:

rowNumber, colNumber: Oyun tahtasındaki satır ve sütun sayısı.
mineNumber: Mayın tarlasındaki mayın sayısı.
answerBoard: Mayın konumlarını saklayan tahta (oyuncudan gizli).
board: Oyuncunun gördüğü oyun tahtası.


Yapıcı Metot:
Belirtilen satır ve sütun sayısıyla oyunu başlatır.

Metotlar:
fillArr(): Oyun tahtasını "-" karakterleriyle doldurur.
placeMines(): Mayınları mayın tarlasına rastgele yerleştirir.
showBoard(): Oyuncunun oyun tahtasını görüntüler.
showAnswerBoard(): Mayın konumlarını görüntüler (hata ayıklama amaçlı).
findMines(): Seçilen hücrenin çevresindeki mayın sayısını belirler.
run(): Oyun mantığını yürüten ana metot.


Oyunu Oynamak:
Oyunu çalıştırdıktan sonra mayın tarlasının başlangıç durumunu göreceksiniz.
Satır ve sütun koordinatları girerek hücreleri ortaya çıkarın.
Oyun, yakındaki mayın sayısı hakkında geri bildirim sağlayacaktır.
Oyunu kazanmak için tüm güvenli hücreleri ortaya çıkarın.
Bir mayına rastlarsanız, oyun sona erer ve kaybedersiniz.

Notlar:
Oyun, mayınları tahtaya rastgele yerleştirmek için basit bir algoritma kullanır.
Geçerli satır ve sütun koordinatları sağlamak için giriş doğrulaması uygulanmıştır.
Oyun, tüm güvenli hücreler ortaya çıkarıldığında veya bir mayına çarpıldığında sona erer.
Mayın Tarlasının tadını çıkarın! Herhangi bir sorunla karşılaşırsanız veya önerileriniz varsa, lütfen iletişime geçmekten çekinmeyin.
