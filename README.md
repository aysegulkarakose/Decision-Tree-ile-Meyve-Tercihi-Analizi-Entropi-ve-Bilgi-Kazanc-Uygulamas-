Karar Ağacı ile Meyve Tercihi Analizi

Bu projede, basit bir veri seti kullanılarak decision tree algoritması ile meyve tercihleri sınıflandırılmıştır. Python ve scikit-learn kütüphanesi kullanılarak hem model eğitimi hem de el ile entropi ve bilgi kazancı (information gain) hesaplamaları yapılmıştır.

Proje Özeti

- El ile oluşturulmuş bir veri seti (`Meyve`, `Renk`, `Büyüklük`, `Tercih`)
- Entropi ve bilgi kazancı fonksiyonları (manuel hesaplama)
- `DecisionTreeClassifier` ile karar ağacı oluşturma
- Görsel karar ağacı çizimi (`graphviz` ve `plot_tree`)
- El ile karar verme fonksiyonu (`manual_karar_agaci`)
- Seaborn ile detaylı görselleştirme
- Model doğruluk oranı hesaplama

Dosya İçeriği

- `meyve_secim.csv` – Örnek veri seti (otomatik olarak script tarafından oluşturulur)
- `karar_agaci.py` – Tüm Python kodları
- `decision_tree.pdf/png` – Oluşturulan karar ağacının görsel çıktısı (graphviz ile)

Kullanılan Kütüphaneler

```python
pandas
numpy
scikit-learn
matplotlib
seaborn
graphviz
