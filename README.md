![splash](https://github.com/user-attachments/assets/edd0adf0-d1b9-425c-b5fb-6641aecc38ca)



<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/149723?tab=description">Nexus</a> |
  <a href="https://github.com/candrmz/Nergal-Mod-List-TR/blob/main/README.md">Yükleme</a> |
  <a href="https://github.com/candrmz/Nergal-Mod-List-TR/blob/main/D%C3%B6k%C3%BCmanlar/Ayarlar">Ayarlar</a> |


 - [Giriş](#Giriş)
   - [Sistem Gereksinimleri](#Sistem-Gereksinimleri)
  - [Yükleme](#Yükleme)
    - [Yüklemeden Önce](#Yüklemeden-Önce)
      - [Sanal Bellek ve Hata Önleme](#Sanal-Bellek-ve-Hata-Önleme)
      - [Gölgelendirici Önbellek Boyutu (Sadece NVIDIA Kartları için)](#Gölgelendirici-Önbellek-Boyutu-Sadece-NVIDIA-Kartları-İçin)
    - [Wabbajack Kurulum](#wabbajack-Kurulum)
      - [Wabbajack'in Kurulumu](#Wabbajack'in-Kurulumu)
      - [Nergal'i İndirme ve Yükleme](#Nergal'i-İndirme-ve-Yükleme)
      - [Sorunlu Dosyalar](#Sorunlu-Dosyalar)
  - [Kurulum Sonrası](#Kurulum-Sonrası)
    - [Klavye Tuşları](#Klavye-Tuşları)
    - [Oyuna Başlamak](#Oyuna-Başlamak)
  - [İletişim](#İletişim)
  - [Teşekkürler](#Teşekkürler)

## Giriş

Nergal, Skyrim Anniversary Edition için türkçe, görselliğe ve dövüş sistemine önem veren bir mod listesidir. Ordinator vb oynanış modları ve bir çok silah, zırh, canavar, büyü modları içerisine dahil edilmiştir.

Listedeki tüm modları merak ediyorsanız, mod listesini buradan görebilirsin [Buradan]().

---

### Sistem Gereksinimleri

**DİKKAT:**
- HDD veya harici SSD kullanmamanızı tavsiye ederim.
- Steamdan AE versiyonunu almalı ya da SE versiyonu varsa AE sürüm güncellemesini satın almalısınız.
- Sadece Windowns 10 veya 11 desteklenmekte.
- en az 8gb vram'e sahip bir ekran kartına sahip olmalısınız, yoksa oyun içinde takılmalara denk gelebilirsiniz ve oyununuz çökebilir.

| Sistem Kategorisi | Minimum (1080p) | 
|     :---:    |      :---:    |
| **İŞLEMCİ**   | R5 5600x / i5 13400f |
| **EKRAN KARTI**    |  RTX 3060 / RX 6700-XT  | 
| **Ram**    | 16 GB / 32GB DDR4/5 | 
| **DEPOLAMA**    | SATA/NVME SSD | 
| **OS**    | Windows 10/11 | 

İndirme: ~135 GB  
Kurulum: ~215  GB  
**TOPLAM:** ~ 350 GB  

## Yükleme

**⚠ DİKKAT ⚠:**
- **Listeyi yüklemeden önce Skyrim Anniversary Edition son sürümünü kurmanız gerekiyor.**

### Yüklemeden Önce

#### Sanal Bellek ve Hata Önleme

büyük Skyrim mod listeleri önemli miktarda bellek gerektirir ve belleğin tükenmesi **çökmelere ve diğer potansiyel sorunlara neden olur**.

Nergal'in boyutu ve liste için işlenmesi gereken dosya sayısı nedeniyle bu adım isteğe bağlı **DEĞİLDİR**. **Ne kadar RAM veya VRAM'iniz olursa olsun lütfen bu adımı uygulayın.**


 1. **Win Tuşu + R** Basın
 2. *sysdm.cpl ,3* yazın ve **ENTER**a tıklayın
 3. *Performans* kısmındaki "Ayarlar..." kutusuna tıklayın
 4.  Üst kısımdaki *Gelişmiş* sekmesine tıklayın
 5. *Sanal Bellek* altında "Değiştir..." kutusunu tıklayın.
 6. İşaretliyse *Otomatik olarak yönet* seçeneğinin işaretini kaldırın
 7. İdeal olarak en hızlı sürücünüz olan disk sürücünüzü seçin.

      > Bu HDD veya harici SSD **olamaz** 

 8. **Özel boyut:** düğmesini tıklayın
 9. **Başlangıç ​​Boyutu (MB)** seçeneğinin yanındaki kutuya '40960' yazın
 10. **En Büyük Boyut (MB)** seçeneğinin yanındaki kutuya '40960' yazın
 11. *Ayarla* butonuna tıklayın
 12. *Tamam* tıklayın
 13. *Uygula* tıklayın
 14. *Tamam* tıklayın
 15. Sanal bellek etkili olması için bilgisayarınızı yeniden başlatın.

---

#### Gölgelendirici Önbellek Boyutu (Sadece NVIDIA Kartları için)

NVIDIA GeForce Grafik Kartınız varsa lütfen aşağıdakileri yapın:

 1. **NVIDIA Kontrol Panelini** açın
 2. **3D Ayarlarının Yönetilmesi** bölümünü açın. Sol yukarıdan 2. seçenek
 3. Genel ayarlar kısmından **Gölgelendirici Önbellek Boyutu** ayarını görene kadar aşağı kaydırın 
 4. Gölgelendirici Önbellek Boyutu ayarının sol tarafına çift tıklayın ve **10 GB** seçin
 5. Sağ alt köşeden **Uygula** butonuna tıklayın
 6. Uygulamadan çıkabilirsiniz.
 ![](https://github.com/user-attachments/assets/c9235651-ca0a-4e9d-b3be-41a1c0709225)

---

### Wabbajack Kurulum

#### Wabbajack'in Kurulumu

Yüklemeden önce ki adımları tamamladıysanız wabbajack kurulum adımlarını takip edin

1. `Wabbajack` isminde boş bir klasör oluşturun, örneğin `C:\Wabbajack` gibi olabilir. **Program files klasörü, kullanıcı korumaları klasörler (Masaüstü, Dosyalar, İndirilenler, vb.), ya da skyrim steam klasörüne kurmayın**.
   > 'Wabbajack' klasörünün bir SSD'de olması gerekmez, ancak kurulumu daha hızlı hale getirir. Yerden tasarruf etmek adına HDD'de bir 'Wabbajack' klasörü oluşturabilirsiniz.

2. [Son wabbajack sürümünü](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) indirin ve 1. adımda oluşturduğunuz klasöre wabbajack.exe dosyasını kopyalayın. Wabbajack'in eski sürümlerini **kullanmayın**.

3. Programı kurmak için Wabbajack klasörünüzün içinde bulunan 'Wabbajack.exe' dosyasına çift tıklayın.

---

#### Nergal'i İndirme ve Yükleme

Nergal'i indirip yüklemek internet bağlantınıza, PC özelliklerine ve Nexus Premium'a sahip olup olmadığınıza bağlı olarak biraz zaman alabilir.

Nergal'i yüklemek için aşağıdaki adımları takip edin:

1. [Son Nergal Sürümünü](https://drive.google.com/file/d/11kMWDWNBWsFEuDfpwqTdqEyuyOCNmqt2/view?usp=sharing) indirip wabbajack klasörüne atın

2.  "Modlist Installation Location" kısmını "C:\Nergal" gibi bir klasöre ayarlayın
   > **Program files klasörü, kullanıcı korumaları klasörler (Masaüstü, Dosyalar, İndirilenler, vb.), ya da skyrim steam klasörüne kurmayın**.

3. 'Modlist Installation Location' ayarladıktan sonra 'Resource Download Location' satırı otomatik olarak doldurulmalıdır.
   > 'Resource Download Location' Listenin kurulum konumuyla aynı sürücüde olması gerekmez. Yerden tasarruf etmek amacıyla bu konumu HDD'deki bir klasöre ayarlayabilirsiniz.

4. Kurulumu başlatmak için oynat okuna basın.
   
5.Kurulum başarılı olursa [Kurulum Sonrası](#kurulum-sonrası) bölümüne geçin. Kurulum başarısız olursa, [Sorunlu Dosyalar](#sorunlu-dosyalar) bölümüne ve aşağıdaki ipuçlarına bakın veya destek için [İletişim](#iletişim) bölümünü kontrol edin.

---

#### Sorunlu Dosyalar

Wabbajack bazen Nexus dışındaki sitelerde barındırılan modları indirirken sorun yaşayabilir. Bu nedenle, size kolaylık sağlamak için birçok sorunlu dosya aşağıda listelenmiştir.

Bu dosyaları **manuel olarak indirmeniz** ve bunları [Nergal'i İndirme ve Yükleme](#Nergal-İndirme-ve-Yükleme) bölümünde oluşturulan 'Resource Download Location'na yerleştirmeniz gerekecektir.

  - [ENB BINARIES](https://drive.google.com/file/d/18rIOtzSG94-ElYZU5-f2t8BQkvoTKc9H/view?usp=sharing)
---

## Kurulum Sonrası

  Eğer 8gb vram kullanıyorsanız vramr adlı programı çalıştırmanızda fayda var. 
  
### Klavye Tuşları
Tuşlar eski sürüm için ayarlanmıştı eski sürümü kullanıyorsanız bu tuşları kullanın yeni tuş sistemi yükleyeceğim.
![keyboard-layout (2)](https://github.com/user-attachments/assets/31101971-0c91-4b46-9b93-0f6d5d8b7c96)

### Oyuna başlamak

Kurulum klasörüne gidin ve 'ModOrganizer.exe' adlı yürütülebilir dosyayı bulun ve başlatın.

 1. MO2'nin sağ üst köşesindeki 'Nergal' yazısının yanındaki 'Çalıştır' yazan düğmeye tıklayın.
      > Listenin çok büyük olması nedeniyle oyunun ilk açılışında yüklenmesi 5-10 dakika sürebilir. Lütfen sabırlı olun ve MO2 de kilidi kaldır butonuna basmayın.
 2. Oyun yüklendikten sonra yeni bir oyuna başlayın. hikayeyi geç seçeneğini seçin ve mağaranın çıkışında başlayın.
 3. Karakter yaratma işiniz bitince mağaradan çıkarak oyuna başlayabilirsiniz. (Bazı karakter presetleri yükledim yukarıdan hazır karakterlerle başlayabilirsiniz.)

## İletişim

Tüm Yazılanları yapmanıza rağmen hata ile karşılaşırsanız [Kitetki](https://discord.gg/9rDGJ585fz) discord sunucusuna gelip beni etiketleyerek soru sorabilirsiniz.

**Oyun içerisinde herhangi bir hata ile karşılaşırsanız konsolu açıp hatanın sebep olduğu şeye tıklayarak ss alıp gönderin. Aksi takdirde sorunu bulup düzeltmek çok zor.**

## Teşekkürler

- Axel'e Dövüş animasyonları ve listede bazı hataların çözümünde bulunduğu için teşekkür ederim
- Kitetki'ye wabbajack sorunlarıyla ilgili yardımda bulunduğu için teşekkür ederim
- Proton'a SSEedit ile ilgili yardımcı olduğu için teşekkür ederim
- ve Mod önerisinde bulunan, listeyi test eden arkadaşlara da teşekkür ederim
  
