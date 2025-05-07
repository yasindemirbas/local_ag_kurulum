# Local Ağ Kurulum

## Sanal Anahtarları Oluşturma (WAN, LAN)

Hyper-V üzerinden sağdan **Sanal Anahtar Yöneticisi** bölümüne giriyoruz.

<h4>WAN:</h4>

**Yeni sanal ağ anahtarı** diyoruz, ve **Dış** seçip  **Sanal Anahtar Oluştur** diyoruz.

- Ad: (Herhangi bir ad olabilir)
- Bağlantı türü
  - Dış ağı
    - (Kendi ethernet bağlantızı seçin)
    - "Yönetim işletim sisteminin bu ağ bağlaştırıcısının paylaşmasına izin ver": Eğer WAN IP ataması olmaz ise bunu kapatın.

<h4>LAN:</h4>

**Yeni sanal ağ anahtarı** diyoruz, ve **Özel** seçip  **Sanal Anahtar Oluştur** diyoruz.

- Ad: (Herhangi bir ad olabilir)

## PfSense Kurulumu

PfSense, Linux çekirdeğini kullanan açık kaynaklı bir güvenlik duvarı işi görür. Port yönlendirme, vs. İşler içindir.

<a href="https://www.pfsense.org/">PfSense İndir</a>

PfSense, ilk açılım

[Resim1]

Klavye dilini şeçtikten sonra *Auto (ZFS)* seçiyoruz.

[Resim3]

[Resim2]

Bundan sonra 3 adım varsyılan ayarlar ile.

[Resim3]
[Resim4]
[Resim5]

Space'e basarak disk'i seçiyoruz.

[Resim6]


Kurulumdan sonra yeniden başlatıyoruz.
Kurulumdan sonra varsaylan giriş bilgileri:

Kullanıcı: admin
Şifre: pfsense

Aynı şey web arayüzü üzerinden'de geçerli.
