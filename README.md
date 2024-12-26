📌 Uygulama Hakkında
Travel Companion App, tatil planlamanızı kolaylaştırmak için tasarlanmış bir konsol uygulamasıdır. Kullanıcılar, Bodrum, Marmaris veya Çeşme gibi popüler tatil destinasyonlarından birini seçebilir, ulaşım tercihlerini belirleyebilir ve toplam tatil maliyetlerini hesaplayabilir. Uygulama, kullanıcı dostu bir deneyim sunar ve birden fazla tatil planı yapmanıza olanak tanır.

🚀 Nasıl Çalışır?
Başlangıç:

Uygulama çalıştırıldığında kullanıcıyı bir tatil planı yapmaya davet eder.
Lokasyon Seçimi:

Kullanıcı, Bodrum, Marmaris veya Çeşme seçeneklerinden birini seçer.
Seçilen lokasyona göre tatil önerileri ve kişi başı tatil maliyeti belirlenir.
Kişi Sayısı:

Kullanıcı, tatil planını kaç kişi için yapmak istediğini belirtir.
Ulaşım Tercihi:

Kara yolu (kişi başı 1500 TL) veya hava yolu (kişi başı 4000 TL) seçeneklerinden biri seçilir.
Toplam Maliyet Hesaplama:

Lokasyon maliyeti ve ulaşım tercihi dikkate alınarak toplam tatil maliyeti hesaplanır ve ekrana yazdırılır.
Devam Seçeneği:

Kullanıcı, başka bir tatil planı yapmak isteyip istemediğini belirtebilir.
"Hayır" seçeneği ile uygulama sonlanır.
🛠️ Kullanılan Teknolojiler
C#: Uygulamanın temel programlama dili.
.NET Core: Konsol uygulaması geliştirme altyapısı.
📋 Özellikler
Esnek Tatil Planlama: Birden fazla tatil planı oluşturabilme.
Kullanıcı Dostu: Hatalı girişlerde kullanıcıyı yönlendiren mesajlar.
Hızlı Hesaplama: Tatil maliyetini anında hesaplama.
Dinamik İçerik: Seçilen lokasyona göre özel öneriler.
💻 Nasıl Çalıştırılır?
Proje Dosyalarını İndirin:

bash
Kodu kopyala
git clone https://github.com/ahmetucar1/TravelCompanionApp.git
cd TravelCompanionApp
Uygulamayı Derleyin ve Çalıştırın:

Visual Studio veya bir IDE kullanarak projeyi açın.
Program.cs dosyasını çalıştırın.
Terminalden Çalıştırma (Opsiyonel):

bash
Kodu kopyala
dotnet run
📝 Kullanım Örneği
Örnek Senaryo:
Lokasyon Seçimi:

markdown
Kodu kopyala
Lütfen bir yer seçin: Bodrum, Marmaris, Çeşme
> Bodrum
Kişi Sayısı:

css
Kodu kopyala
Kaç kişi için tatil planı istiyorsunuz?
> 3
Ulaşım Tercihi:

yaml
Kodu kopyala
Nasıl gitmek istersiniz:
1 - Kara yolu: Kişi başı 1500 TL
2 - Hava yolu: Kişi başı 4000 TL
> 1
Sonuç:

yaml
Kodu kopyala
Seçtiğiniz lokasyon: Bodrum
Kişi sayısı: 3
Toplam tatil maliyeti: 16500 TL
🛠️ Geliştirici Notları
Yeni destinasyonlar eklemek için switch bloğuna yeni bir case ekleyebilirsiniz.
Ulaşım seçeneklerini artırmak veya maliyetleri değiştirmek için ilgili kod bloklarını düzenleyebilirsiniz.
🤝 Katkıda Bulunun
Projeye katkıda bulunmak için lütfen bir pull request gönderin veya önerilerinizi issue olarak paylaşın.

