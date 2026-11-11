# 🚀 Git ve GitHub Temel Rehberi (Tutorial)

Bu depo, Git sürüm kontrol sistemi ve GitHub platformunun temel prensiplerini, yaygın komutlarını ve pratik iş akışını belgelemek amacıyla hazırlanmıştır.

**Hazırlayan:** Abdülkadir Aydıngöç  
**GitHub:** [@kadir3106](https://github.com/kadir3106)

---

## 📌 İçindekiler
1. [Git Nedir?](#-git-nedir)
2. [Temel Git Kavramları](#-temel-git-kavramları)
3. [Sık Kullanılan Git Komutları](#-sık-kullanılan-git-komutları)
4. [Branch (Dal) ve Pull Request Akışı](#-branch-dal-ve-pull-request-akışı)
5. [Bu Depoda Yapılan Uygulamalar](#-bu-depoda-yapılan-uygulamalar)

---

## 💡 Git Nedir?
**Git**, yazılım projelerinde yapılan değişiklikleri adım adım takip eden, geçmişe dönmeyi sağlayan dağıtık bir **sürüm kontrol sistemidir** (VCS).

**GitHub** ise Git ile takip edilen projelerin bulutta depolanmasını, ekip arkadaşlarımızla birlikte çalışabilmemizi ve açık kaynak projeleri paylaşabilmemizi sağlayan bir platformdur.

---

## 🧱 Temel Git Kavramları
* **Repository (Depo/Repo):** Projenin tüm dosyalarını ve geçmişini saklayan ana klasör.
* **Commit:** Yapılan değişikliklerin anlık görüntüsünü (snapshot) kaydeden işlem.
* **Branch (Dal):** Ana kod yapısını bozmadan bağımsız özellikler geliştirmek için açılan yan yol.
* **Remote (Uzak Sunucu):** Kodların tutulduğu bulut sunucusu (örneğin GitHub).
* **Pull Request (PR):** Bir dalda tamamlanan çalışmanın ana dala (main) birleştirilmesi için açılan inceleme isteği.

---

## 🛠 Sık Kullanılan Git Komutları

| Komut | Açıklama |
| :--- | :--- |
| git init | Bulunulan dizinde yeni bir Git deposu başlatır. |
| git clone <url> | Uzak sunucudaki bir depoyu bilgisayara kopyalar. |
| git status | Hangi dosyaların değiştiğini ve takip durumunu gösterir. |
| git add . | Tüm değişiklikleri commit öncesi hazırlık alanına (stage) alır. |
| git commit -m "mesaj" | Hazırlanan değişiklikleri açıklayıcı bir mesajla kaydeder. |
| git push | Yereldeki commit'leri GitHub'a (remote) gönderir. |
| git pull | Uzak depodaki güncellemeleri yerel depoya çeker. |
| git checkout -b <dal-adi> | Yeni bir branch oluşturur ve o dala geçer. |
| git merge <dal-adi> | Belirtilen daldaki değişiklikleri bulunulan dalla birleştirir. |

---

## 🌿 Branch (Dal) ve Pull Request Akışı
Ekip çalışmalarında ve en iyi pratiklerde doğrudan main dalına kod gönderilmez:
1. git checkout -b feature/yeni-ozellik ile yeni bir dal oluşturulur.
2. Kodlar yazılır, dd ve commit edilir.
3. git push -u origin feature/yeni-ozellik ile GitHub'a dal push edilir.
4. GitHub arayüzünden veya CLI üzerinden **Pull Request (PR)** açılır.
5. İnceleme sonrası PR **Merge** edilerek main dalına aktarılır.

---

## 🎯 Bu Depoda Yapılan Uygulamalar
- [x] Yerel Git deposu başlatıldı (git init)
- [x] Kullanıcı adı ve e-posta konfigürasyonu yapıldı (git config)
- [x] İlk commit oluşturuldu
- [x] GitHub üzerinde uzak depo oluşturuldu ve push edildi
- [x] eature/git-cheatsheet dalı açılarak yeni içerik eklendi
- [x] Pull Request oluşturuldu ve başarıyla birleştirildi (merged)
