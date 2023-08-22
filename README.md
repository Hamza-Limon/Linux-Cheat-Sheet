# Temel Linux komutları

# Dosya ve Dizin İşlemleri:

ls: Mevcut dizindeki dosyaları ve dizinleri listele.

-l: Detaylı liste görüntüleme.

-a: Gizli dosyaları da listeleme.

pwd: Şu anki dizini göster.

cd [Dizin]: Dizini değiştir.

touch [Dosya Adı]: Yeni bir dosya oluştur.

mkdir [Dizin Adı]: Yeni bir dizin oluştur.

cp [Kaynak] [Hedef]: Dosya veya dizini kopyala.

mv [Eski] [Yeni]: Dosya veya dizini taşı veya adını değiştir.

rm [Dosya]: Dosya silme.

-r: Dizin ve içeriğini silme.

# Kullanıcı ve İzinler:

whoami: Mevcut kullanıcıyı göster.

sudo [Komut]: Yönetici haklarıyla komut çalıştırma.

useradd [Kullanıcı Adı]: Yeni bir kullanıcı oluştur.

passwd [Kullanıcı Adı]: Kullanıcı şifresini değiştir.

chown [Kullanıcı]:[Grup] [Dosya/Dizin]: Dosya veya dizinin sahibini ve grubunu değiştir.

chmod [İzinler] [Dosya]: Dosya izinlerini değiştir.

Örnek: chmod 755 dosya.txt

# Ağ İşlemleri:

ifconfig: Ağ arayüzlerini görüntüle.

ping [Hedef]: Hedefe ping gönder.

netstat -tuln: Açık portları ve bağlantıları listele.

nslookup [Alan Adı]: DNS sorgusu yap.

# Arşivleme ve Sıkıştırma:

tar -czvf [Dosya.tar.gz] [Dosyalar]: Dosyaları sıkıştırılmış bir arşiv oluştur.

tar -xzvf [Dosya.tar.gz]: Arşivi aç.

# Süreçler:

ps aux: Tüm çalışan süreçleri listele.

top: Sistem kaynaklarını canlı olarak izle.

kill [PID]: Belirtilen süreci sonlandır.

# Veri Akışları:

cat [Dosya]: Dosyanın içeriğini göster.

grep [Arama] [Dosya]: Belirli bir metni içeren satırları bulma.

head [Dosya]: Dosyanın başındaki satırları göster.

tail [Dosya]: Dosyanın sonundaki satırları göster.
