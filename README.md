# E-Ticaret A/B Testi Analizi 📊

Bu depo, bir e-ticaret platformunda yeni bir arayüz/özelliğin kullanıcı dönüşüm oranlarına etkisini değerlendirmek amacıyla geliştirilmiş uçtan uca bir A/B testi analizini içermektedir.

## 🚀 Proje Hakkında
* **Amaç:** Kontrol grubu ile yeni özellik sunulan test grubu arasındaki dönüşüm oranlarının istatistiksel olarak anlamlı bir fark yaratıp yaratmadığını test etmek.
* **Kullanılan Araçlar:** Python, Pandas, NumPy, SciPy, Statsmodels.
* **Yöntem:** Hipotez Testi, İki Oranlı Z-Testi (Two-Proportion Z-Test).

## 📈 Temel Bulgular ve Sonuçlar
* **Kontrol Grubu Dönüşüm Oranı:** %11.45
* **Test Grubu Dönüşüm Oranı:** %14.09
* **P-Value (P-Değeri):** ~0.0000 (0.05 anlamlılık seviyesinin altında)
* **İş Kararı / Çıkarım:** H0 hipotezi reddedilmiştir. Test grubu lehine istatistiksel olarak anlamlı bir artış gözlemlenmiştir; yeni tasarımın tüm kullanıcı tabanına yaygınlaştırılması önerilir.

## 📂 Depo Yapısı
* `ab_testing_analysis.ipynb`: Veri simülasyonunu, keşifsel veri analizini ve istatistiksel testleri içeren detaylı Jupyter Notebook dosyası.
