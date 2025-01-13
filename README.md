# Baraj Doluluk Tahmini

Bu proje, İstanbul barajlarının günlük doluluk oranlarını tahmin etmek için geliştirilmiştir. Tahminler, geçmiş veriler ve ETSFormer algoritması kullanılarak gerçekleştirilir. Proje, veri analizi, makine öğrenimi ve zaman serisi tahmini konularında bir çalışma örneği sunmaktadır.

## İçindekiler
- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Veri Seti](#veri-seti)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Özellikler
- **ETSFormer algoritması** kullanılarak zaman serisi tahmini yapılır.
- Ortalama rüzgar hızı, çiy noktası, deniz basıncı, nem, sıcaklık, su tüketimi gibi çeşitli çevresel faktörler analiz edilir.
- 13 yıllık veri seti ile model eğitimi gerçekleştirilir.
- Proje çıktıları, baraj doluluk oranlarını tahmin ederek karar verme süreçlerine katkı sağlar.

## Kullanılan Teknolojiler
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- PyTorch
- ETSFormer

## Veri Seti
Veri seti, İstanbul'a ait 13 yıllık çevresel ve baraj doluluk oranı verilerinden oluşmaktadır. Veri sütunları şunlardır:
- Tarih
- Sıcaklık
- Hissedilen Sıcaklık
- Çiy Noktası
- Nem
- Yağış
- Rüzgar Hızı
- Deniz Basıncı
- Bulut Örtüsü
- Gün Işığı Süresi
- Baraj Doluluk Yüzdesi

## Kurulum
Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. **Depoyu Klonlayın:**
   ```bash
   git clone https://github.com/hakan8755/barajDolulukTahmin.git
   cd barajDolulukTahmin
   ```

2. **Gerekli Kütüphaneleri Yükleyin:**
   Gerekli bağımlılıkları yüklemek için aşağıdaki komutu çalıştırın:
   ```bash
   pip install -r requirements.txt
   ```

3. **Veri Setini Hazırlayın:**
   Veri setini `data/` dizinine yerleştirin.

4. **Modeli Çalıştırın:**
   Eğitim ve tahmin işlemlerini başlatmak için:
   ```bash
   python train_and_predict.py
   ```

## Kullanım
Proje, baraj doluluk oranlarını tahmin etmek için aşağıdaki adımları izler:
1. Verilerin ön işlenmesi.
2. Transformer algoritmalarıyla ile model eğitimi.
3. Tahmin sonuçlarının görselleştirilmesi.

Sonuçlar `results/` dizininde saklanacaktır.

## Katkıda Bulunma
Katkıda bulunmak için şu adımları takip edebilirsiniz:
1. Bu depoyu fork'layın.
2. Yeni bir özellik dalı oluşturun (`git checkout -b yeni-ozellik`).
3. Değişikliklerinizi yapın ve commit edin (`git commit -m 'Yeni bir özellik eklendi'`).
4. Dalınızı ana depoya push edin (`git push origin yeni-ozellik`).
5. Bir **Pull Request** oluşturun.



---

Herhangi bir sorunuz veya öneriniz varsa [hakan8755](https://github.com/hakan8755) ile iletişime geçebilirsiniz.
