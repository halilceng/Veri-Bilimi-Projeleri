# 📊 Veri Analizi ve Görselleştirme Projeleri

Bu depo (repository), Python kullanılarak gerçekleştirilen **Veri Manipülasyonu** ve **Veri Görselleştirme** çalışmalarını içermektedir. Projelerde, gerçek dünya veri setleri üzerinde Pandas ile analizler yapılmış, Matplotlib ve Seaborn kütüphaneleri ile görselleştirmeler oluşturulmuştur.

## 📂 İçerik

Bu depoda iki ana proje bulunmaktadır:

### 1. Ülke Verileri Analizi (Filtreleme & Sıralama)
* **Dosya:** `Veri_filtreleme_sıralama_projesi.ipynb`
* **Veri Seti:** `country.csv` (Dünya ülkelerine ait nüfus, yüzölçümü, GSYİH, okuryazarlık gibi demografik veriler).
* **Yapılan İşlemler:**
    * Veri temizleme (virgüllü sayıların düzeltilmesi, boşlukların silinmesi).
    * Pandas ile veri filtreleme (Nüfusu 10 milyondan fazla olan ülkeler vb.).
    * Sıralama işlemleri (Kişi başına düşen GSYİH'ye göre sıralama).
    * En yüksek nüfus yoğunluğuna sahip ülkelerin tespiti.

### 2. Startup Kârlılık Analizi (Veri Görselleştirme)
* **Dosya:** `Veri_Görsellestirme_odevi.ipynb`
* **Veri Seti:** `50_Startups.csv` (Şirketlerin Ar-Ge, Yönetim, Pazarlama harcamaları ve Kâr verileri).
* **Kullanılan Görselleştirme Teknikleri:**
    * **Scatter Plot:** Ar-Ge harcamaları ile Kâr arasındaki ilişkinin incelenmesi.
    * **Bar Chart:** Eyaletlere göre ortalama kâr dağılımının karşılaştırılması.
    * **Boxplot (Kutu Grafiği):** Farklı harcama türlerinin dağılımının ve aykırı değerlerin analizi.

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

Projeler **Python 3** kullanılarak geliştirilmiştir. Aşağıdaki kütüphanelerden yararlanılmıştır:

* **[Pandas](https://pandas.pydata.org/):** Veri okuma, temizleme, filtreleme ve manipülasyon.
* **[NumPy](https://numpy.org/):** Sayısal hesaplamalar.
* **[Matplotlib](https://matplotlib.org/):** Temel grafik çizimleri.
* **[Seaborn](https://seaborn.pydata.org/):** İstatistiksel ve estetik veri görselleştirme.

## 🚀 Nasıl Çalıştırılır?

Bu projeleri kendi bilgisayarınızda çalıştırmak için:

1.  Bu depoyu klonlayın:
    ```bash
    git clone [https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git](https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git)
    ```
2.  Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Jupyter Notebook'u başlatın ve `.ipynb` uzantılı dosyaları açın.

---
*Bu çalışma, veri bilimi alanındaki yetkinliklerimi geliştirmek amacıyla hazırlanmıştır.*
