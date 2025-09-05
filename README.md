# Pusula Projesi - Zeynep Çiçen - cicenzeynep1@gmail.com

Bu repo, **sağlık verileri** üzerinde yapılan veri analizi ve ön işleme çalışmalarını içermektedir. Çalışmalar Python dili ve Google Colab Notebook kullanılarak hazırlanmıştır.  

## İçerik

- [`pusula_EDA.ipynb`](./pusula_EDA.ipynb)  
  - Veri kümesinin keşifsel analizi yapılmıştır.  
  - Eksik veriler, tekrar eden kayıtlar ve veri dağılımları incelenmiştir.  
  - Görselleştirmeler ile verilerdeki kalıplar ortaya çıkarılmıştır.  

- [`DPP.ipynb`](./DPP.ipynb)  
  - Veri temizleme ve ön işleme adımları uygulanmıştır.  
  - Eksik değerler **SimpleImputer** ve **KNNImputer** yöntemleriyle doldurulmuştur.  
  - Kategorik değişkenler encode edilmiştir.  
  - Sayısal değişkenler normalleştirilmiş/standardize edilmiştir.  

## Kullanılan Teknolojiler

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Nasıl Çalıştırılır?

1. Repoyu klonla:
   ```bash
   git clone https://github.com/zeynepcicen/Pusula_Zeynep_Cicen.git
