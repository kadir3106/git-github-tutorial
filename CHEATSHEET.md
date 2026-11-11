# 📖 Hızlı Git Komutları (Cheatsheet)

### 1. Durum ve Geçmiş
- git status : Değişen dosyaları listeler.
- git log --oneline : Geçmiş commit'leri tek satırda özetler.
- git diff : Yapılan satır bazlı değişiklikleri gösterir.

### 2. Dal (Branch) Yönetimi
- git branch : Mevcut dalları listeler.
- git checkout -b <isim> : Yeni dala geçer.
- git merge <isim> : Başka bir dalı bulunulan dala birleştirir.

### 3. Geri Alma (Undo)
- git restore <dosya> : Kaydedilmemiş değişiklikleri geri alır.
- git reset HEAD~1 : Son commit'i geri alır (dosyaları silmeden).
