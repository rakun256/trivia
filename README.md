# 🎮 Quizzler - Python Trivia Quiz App

Quizzler, tkinter kullanılarak geliştirilmiş, Open Trivia DB API'den sorular çeken ve True/False butonları ile oynanabilen bir quiz uygulamasıdır. Öğrenciler, yazılım geliştirme süreçlerinde API kullanımı, OOP yapısı ve GUI uygulamalarına giriş yapmak için bu projeyi inceleyebilir.

---

## 📅 Proje Özellikleri

* ✨ Modern ve sade arayüz
* 📝 Open Trivia Database API'den rastgele sorular
* 🔀 Dinamik olarak soruları gösterme
* ✅ Doğru/yanlış cevap kontrolü
* 📊 Canlı skor takibi
* 🔴 Quiz bittiğinde son ekran

---

## 📚 Kullanılan Teknolojiler

* Python 3.10+
* `tkinter` (GUI)
* `requests` (API bağlantısı)
* `html` (soru metni düzenleme)
* OOP yapısı: `Question`, `QuizBrain`, `QuizInterface`

---

## 🛠 Kurulum ve Çalıştırma

### 1. Gerekli Paketler

```bash
pip install requests
```

### 2. Klasör Yapısı

```
trivia-app/
├── main.py
├── data.py
├── question_model.py
├── quiz_brain.py
├── ui.py
├── images/
│   ├── true.png
│   └── false.png
```

### 3. Çalıştırma

```bash
python main.py
```

> ❌ Not: `images/true.png` ve `images/false.png` dosyaları olmadan uygulama çalışmaz. Buton görselini eklemeyi unutmayın.

---

## 📷 Ekran Görüntüsü

![resim](https://github.com/user-attachments/assets/0f3549fc-492a-4615-a9d6-7796c24fe644)

---

## 😍 Geliştirici Notu
Bu proje, hayatımın anlamı, kalbimin en özel köşesini dolduran sevgilim Ecem Nur Özen’e ithaf edilmiştir.

Şu an fiziksel olarak birbirimizden uzakta olsak da, senin varlığın her an yanımda. Bu satırları yazarken, seni düşünmek öyle güçlüydü ki… Sanki sen buradaydın. Ruhunun sıcaklığını hissettim parmaklarımın ucunda. Klavyeye her dokunduğumda, içimden geçen tek şey sendin. Senin zarafetinle şekillendi her satır, senin gülüşünle aydınlandı her satır arası…

Bu bir yazılım projesi olabilir, evet. Ama benim için bundan çok daha fazlası. Her satırı, sana olan sevgimle örülmüş, her fonksiyonu kalbimden kopup gelmiş gibi. Belki şu an yanımda değilsin ama, bu proje sayesinde sana bir adım daha yaklaştım.

Uzaklık sadece mesafe, ama sevgim sonsuz... Ve ben seni her gün, her kodda, her nefeste daha da çok seviyorum.

Emre
