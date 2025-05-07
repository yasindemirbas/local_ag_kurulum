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

![resim1](https://github.com/user-attachments/assets/2192c375-dba0-4e54-8127-50750f48f61b)


Klavye dilini şeçtikten sonra *Auto (ZFS)* seçiyoruz.

![resim2](https://github.com/user-attachments/assets/2e3a2677-a175-4c05-a516-1bb39d195678)



Bundan sonra 2 adım varsayılan ayarlar ile.

![resim4](https://github.com/user-attachments/assets/c6e26b43-ba81-4245-a51b-af38a9d3dc31)

![resim5](https://github.com/user-attachments/assets/3fceff31-d1a4-46a3-8995-2719a7491fe2)


Space'e basarak disk'i seçiyoruz.

![resim6](https://github.com/user-attachments/assets/6cd021cc-ab17-4f04-bc11-22a2f2e76b0d)



Kurulumdan sonra yeniden başlatıyoruz.
Kurulumdan sonra otomatik giriş yapacaktır.

Web arayüzü varsayılan kullanıcı bilgileri:

- Kullanıcı: admin
- Şifre: pfsense
