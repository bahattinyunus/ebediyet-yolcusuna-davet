# 🤝 Şahs-ı Manevî Katkı Rehberi (Contributing Guide)

> *"Bu dijital medrese tek bir kişinin değil, kalbinde iman kurtarma derdi taşıyan bütün ebediyet yolcularının ortak sadaka-i cariyesidir."*

**Ebediyet Yolcusuna Davet** deposuna katkıda bulunmak istediğin için Allah razı olsun! Burada açılan her anlamlı Issue ve gönderilen her özenli Pull Request, şüphe fırtınasında yol arayan bir kardeşimizin elinden tutmaya vesile olabilir.

---

## 🧭 Katkı İlkelerimiz (Medrese Edebi)

Katkı hazırlarken şu dört temel düstura sadık kalmanı rica ediyoruz:

1. **İhlas ve Müsbet Hareket:** Metinlerde polemik, siyasi tartışma, kişi/cemaat hedef gösterme veya sert ötekileştirici üslup kesinlikle yer almamalıdır. Muhatabımız "düşman" değil, yangından kurtarılmayı bekleyen "hasta kardeşimizdir".
2. **Kaynak Sadakati ve Ehli Sünnet Çizgisi:** Yapılan alıntılarda Kur'an ayetlerinin sure/ayet numaraları ve Risale-i Nur Külliyatı'ndaki ilgili eser/bölüm adları (*ör. 23. Lem'a, 10. Söz Dokuzuncu Hakikat*) doğru ve teyitli şekilde belirtilmelidir.
3. **Bilişsel ve Çağdaş Köprü Kurma:** Klasik hakikatlerin özünü sulandırmadan, günümüz insanının ve gençliğinin zihin dünyasına (modern bilim, psikoloji, sistem düşüncesi analojileriyle) berrak köprüler kurulmalıdır.
4. **Temiz Formatlama ve UTF-8:** Tüm dosyalar **UTF-8** kodlamasıyla kaydedilmeli, GitHub Flavored Markdown standartlarına uygun başlıklar, tablolar ve `mermaid` şemaları kullanılmalıdır.

---

## 🛠️ Nasıl Katkıda Bulunabilirsin?

* **Yeni Alt Ders Ekleme:** Mevcut `00`–`07` modüllerinden birinin altına henüz işlenmemiş bir Risalenin (*ör. 19. Mektup Mucizat-ı Ahmediye, 25. Söz Mucizat-ı Kur'aniye, 32. Söz, Münâcât Risalesi*) analiz dersini ekleyebilirsin.
* **Zihin Haritaları (`mermaid`):** Karmaşık kelâmî argümanları tek bakışta anlaşılır kılan akış şemaları ve kavram haritaları üretebilirsin.
* **Sözlük ve Reçete Genişletme:** [Kavramsal Sözlük](./sozluk/README.md) veya [Okuma Planları](./okuma-planlari/README.md) tablolarına yeni kavramlar ve okuma rotaları önerebilirsin.
* **Çok Dilli Tercüme:** Derslerin İngilizce, Arapça, Almanca veya diğer dillerdeki özenli tercümeleri için katkı sunabilirsin.
* **Yazım ve Bağlantı Düzeltmeleri:** Gözden kaçan imla hatalarını veya kırık linkleri düzeltebilirsin.

---

## 📋 Yeni Ders Şablonu

Bir modüle yeni ders eklerken aşağıdaki iskeleti takip etmen bütünlüğü koruyacaktır:

```markdown
# 📌 Ders XX: [Ders Başlığı]

> *"[Kaynak Risaleden Vurucu Serlevha Alıntısı]"*  
> **— [Kaynak Risale Adı]**

---

## 1. Problem Tanımı: [Asrın Sorusu veya İhtiyacı]
...

## 2. Hakikat Analizi ve Aklî Burhanlar
...

## 📝 Ders Özeti ve Eylem Adımları
1. [Günlük Pratik Tefekkür Uygulaması]
2. **Kaynak Okuma:** ...

---

⬅️ **[Önceki Ders](./...)** | ➡️ **[Sonraki Ders](./...)**
```

---

## 🚀 Pull Request Adımları

1. Depoyu **Fork** et ve kendi çalışma dalını oluştur (`git checkout -b ders/mucizat-i-kuraniye`).
2. Değişikliklerini temiz ve anlamlı bir mesajla kaydet (`git commit -m "feat(02): 25. Söz Kur'an mucizeleri alt dersi eklendi"`).
3. Dalını kendi fork'una gönder (`git push origin ders/mucizat-i-kuraniye`) ve **Pull Request** aç.

*Gayret bizden, tevfik ve kabul ancak Allah'tandır!*

---

⬅️ **[Ana Sayfaya Dön](./README.md)**
