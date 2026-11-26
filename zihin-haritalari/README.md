# 🗺️ Görsel Hakikat ve Burhan Atlası (`zihin-haritalari/`)

> *"Temsil, uzak hakikatleri yakınlaştıran bir dürbündür; şema ise dağınık burhanları tek bakışta zihne mühürleyen bir haritadır."*

Bu atlas, Risale-i Nur Külliyatı'ndaki temel iman, ontoloji, psikoloji ve içtimaiyat hakikatlerini **7 bütünsel zihin haritası** halinde görselleştirir. Ders müzakerelerinde, sunumlarda ve kişisel tefekkürde hızlı başvuru haritası olarak kullanabilirsin.

---

## Harita 1: Külliyat-ı Nur Bütünsel Mimari Haritası

Hangi ana eserin insan ruhunun hangi temel ihtiyacına cevap verdiğini gösteren kuşbakışı harita:

```mermaid
flowchart TD
    K["📚 RİSALE-İ NUR KÜLLİYATI<br>(Kur'an'ın Manevi Tefsiri)"] --> S["💎 SÖZLER<br>Aklî ve Kalbî İman Burhanları<br>(Tevhid, Haşir, Kader, Ene, Namaz)"]
    K --> M["✉️ MEKTUBAT<br>İçtimaiyat, Uhuvvet ve Nübüvvet<br>(19. Mektup Mucizat, 22. Mektup Uhuvvet)"]
    K --> L["✨ LEM'ALAR<br>Ruhsal İlaçlar ve İhlas Mimarisi<br>(İhlas, Tabiat, Hastalar, İhtiyarlar, İsm-i A'zam)"]
    K --> SU["☀️ ŞUALAR<br>Küllî Tefekkür ve Müdafaanameler<br>(7. Şua Âyetü'l-Kübra, Münâcât, 15. Şua)"]
    K --> LA["🤝 LAHİKALAR<br>Hizmet Metodolojisi ve Şahs-ı Manevî<br>(Barla, Kastamonu, Emirdağ)"]
    K --> IL["🔬 İŞÂRÂTÜ'L-İ'CÂZ & MESNEVÎ<br>Belâgat, Nazım İ'câzı ve Enfüsî Dersler"]
```

---

## Harita 2: İman Erkânlarının Birbirini İspat Zinciri (`Telâzüm-ü Erkân`)

İmanın altı şartı birbirinden kopuk maddeler değildir; bir halka ispatlandığında diğer tüm halkaları mantıksal zorunlulukla netice verir:

```mermaid
flowchart LR
    T["1. ALLAH'A İMAN<br>(Sonsuz İlim, Kudret, Hikmet ve Adalet)"] -->|"Hikmetli Sanatkâr mahlukatını rehbersiz bırakmaz"| N["2. PEYGAMBERLERE İMAN<br>(Risalet ve Rehberlik)"]
    N -->|"Elçi elinde Sultanın Fermanıyla gelir"| K["3. KİTAPLARA İMAN<br>(Vahiy ve Kur'an)"]
    T -->|"Mülkünü şuursuz bırakmaz, elçilerle doldurur"| ML["4. MELEKLERE İMAN<br>(Gayb Âlemi Sâkinleri)"]
    T -->|"Sonsuz Adalet ve Rahmet hesap gününü ister"| A["5. AHİRETE İMAN<br>(Haşir ve Ebedî Beka)"]
    T -->|"Sonsuz İlim her şeyi ölçüyle kaydeder"| KD["6. KADERE İMAN<br>(İlahi Program ve Cüz'î İrade)"]
    K & N -->|"Vahyin binlerce ihbar ve delili"| A
```

---

## Harita 3: Mânâ-yı İsmî vs. Mânâ-yı Harfî Bilişsel İşlem Hattı

Duyularımızla algıladığımız aynı dış dünya verisinin zihinde iki zıt yoruma dönüşme süreci:

```mermaid
flowchart TD
    V["🍎 Duyu Verisi: Bir Elma / Bir Çiçek / Bir Yıldız"] --> F{"Bilişsel Filtre Seçimi"}
    F -->|"Mânâ-yı İsmî (Gaflet Filtresi)"| MI1["Yalnız maddeyi, kimyayı ve fiziksel formu görür"]
    MI1 --> MI2["Sebeplere ve tesadüfe mal eder: 'Ne güzel olmuş!'"]
    MI2 --> MI3["Sonuç: Geçicilik hüznü, anlamsızlık ve manevi körlük"]

    F -->|"Mânâ-yı Harfî (Nuranî Filtre)"| MH1["Sanatın içindeki İlim, İrade ve Şefkati okur"]
    MH1 --> MH2["Sanatkâr'a bağlanır: 'Ne güzel yaratılmış, kimin ikramı?'"]
    MH2 --> MH3["Tecelli Eden İsimleri Tanır (Rezzak, Musavvir, Rahîm)"]
    MH3 --> MH4["Sonuç: Marifetullah, Muhabbetullah ve Şükür Lezzeti"]
```

---

## Harita 4: İnsanın Manevi Anatomisi (`Lâtifeler ve Kuvveler Haritası`)

Risale-i Nur'da insan sadece "akıl ve beden"den ibaret görülmez; ebediyete uzanan zengin bir lâtifeler topluluğudur:

```mermaid
flowchart TD
    INS["👤 İNSAN-I KÂMİL ADAYI<br>(Ahsen-i Takvim)"] --> R["🕊️ RUH: Emir âleminden gelen ölümsüz, şuurlu öz"]
    INS --> KL["❤️ KALP: İmanın, muhabbetin ve tasdikin merkezi (Âyine-i Samed)"]
    INS --> AK["🧠 AKIL: Hakikati tartan muhakeme ve tefekkür aleti"]
    INS --> VC["🧭 VİCDAN: Fıtrat pusulası (Acz ve fakr ile Yaratıcı'yı hisseder)"]
    INS --> HY["🎬 HAYAL: Görüntü ekranı (Tahayyül sorumluluk doğurmaz)"]
    INS --> KP["⚡ ÜÇ KUVVE (Sınırlandırılmamış Güçler)"]
    KP --> K1["Kuvve-i Şeheviye -> İtidal noktası: İFFET"]
    KP --> K2["Kuvve-i Gadabiye -> İtidal noktası: ŞECAAT (Cesaret)"]
    KP --> K3["Kuvve-i Akliye -> İtidal noktası: HİKMET"]
```

---

## Harita 5: Şüphe, Vesvese ve İstifham Tanı Ağacı (`Manevi Triyaj`)

Zihne gelen her rahatsız edici düşünce aynı kategoriye girmez; yanlış teşhis yanlış tedavi doğurur:

```mermaid
flowchart TD
    S["Zihne Gelen Soru / Sıkıntı"] --> Q1{"Kalbin bundan üzülüyor ve tiksiniyor mu?"}
    Q1 -->|"Evet, istemediğim halde hücum ediyor"| V["🦠 VESVESE (21. Söz)"]
    V --> V1["Çözüm: Tartışma, büyütme, ehemmiyet verme! Hayal ≠ Tasdik"]
    Q1 -->|"Hayır, gerçekten mantığını anlamak istiyorum"| Q2{"Konusu Nedir?"}
    Q2 -->|"Doğa / Evrim / Yaratıcı"| T1["🧪 23. Lem'a (Tabiat) & 33. Söz"]
    Q2 -->|"Ölüm / Yokluk / Ahiret"| T2["🌱 10. Söz (Haşir) & 29. Söz"]
    Q2 -->|"Kader / Özgür İrade / Kötülük"| T3["⚖️ 26. Söz (Kader) & 12. Mektup"]
    Q2 -->|"Neden Peygamber ve Din var? (Deizm)"| T4["🌹 19. Söz & 25. Söz"]
```

---

## Harita 6: Gençlikte Zaman ve Lezzet Ekonomisi (13. Söz & Gençlik Rehberi)

```mermaid
flowchart LR
    G["⏳ Gençlik Sermayesi (Sınırlı Süre)"] --> Y1["❌ Gayrimeşru Heves Yolu"]
    G --> Y2["✅ Helal Daire ve İffet Yolu"]
    Y1 --> Z1["1 Saatlik Zehirli Bal"] --> Z2["Vicdan Azabı + Ruhsal Çöküntü + Ahiret Mesuliyeti"]
    Y2 --> N1["Temiz Huzur ve Özsaygı"] --> N2["İbadet Sevabı + Ebedî Cennet Gençliği"]
```

---

## Harita 7: İhlas, Uhuvvet ve Şahs-ı Manevî Geri Besleme Döngüsü

```mermaid
flowchart TD
    I["🎯 1. İHLAS: Yalnız Rıza-yı İlahî"] --> E["🪞 2. ENANİYETİN ERİMESİ: Fena fi'l-İhvan"]
    E --> U["🤝 3. UHUVVET: Kardeşini Tenkit Etmemek ve Şefkat"]
    U --> T["🧱 4. TESANÜD: 1 + 1 + 1 = 111 Sırrı"]
    T --> SM["🛡️ 5. ŞAHS-I MANEVÎ: Asrın Fırtınasına Direnen Kolektif Ruh"]
    SM -->|"Şevk ve Kuvvet Vererek Besler"| I
```

---

⬅️ **[AI Mütalaa Araçlarına Dön](../ai-mutalaa-araclari/README.md)** | ➡️ **[Ana Sayfaya Dön](../README.md)**
