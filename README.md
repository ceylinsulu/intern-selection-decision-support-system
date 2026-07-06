# intern-selection-decision-support-system
Bu proje, stajyer adaylarının değerlendirilmesi süreçlerini optimize etmek amacıyla geliştirilmiş makine öğrenmesi modellerinin (XGBoost, Karar Ağacı, Lojistik Regresyon) sonuçlarını görselleştiren interaktif bir web gösterge panelidir (dashboard).

## 📊 Proje Özeti
* **Veri Hacmi:** 10.000 başvurucu kaydı
* **Özellikler (Features):** Toplam 505 özellik (5 yapısal özellik + 500 TF-IDF özniteliği)
* **Veri Dağılımı:** %80 Eğitim / %20 Test (Stratified Split)

## ⚙️ Özellikler
* **Model Karşılaştırması:** Lojistik Regresyon, Karar Ağacı ve XGBoost modellerinin Doğruluk (Accuracy), AUC-ROC, F1 Skoru ve Çapraz Doğrulama (Cross-Validation) metriklerinin analizi.
* **İnteraktif Grafikler:** `Chart.js` kütüphanesi kullanılarak oluşturulan dinamik ROC Eğrisi ve Karmaşıklık Matrisi (Confusion Matrix) grafikleri.
* **Başvurucu Senaryoları:** Farklı aday profilleri (Güçlü eşleşme, Kısmi eşleşme, Zayıf eşleşme) üzerinden modelin olasılık tahminlerinin ve karar mekanizmasının incelenmesi.

## 🚀 Teknolojiler
* HTML5, CSS3
* Vanilla JavaScript
* Chart.js (Veri Görselleştirme)
* Google Fonts (Outfit, DM Mono, DM Serif Display)

* 🚀 Projeyi Canlı İncele: https://ceylinsulu.github.io/intern-selection-decision-support-system/



