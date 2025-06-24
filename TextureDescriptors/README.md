# TextureDescriptors

Bu proje, doku tanımlayıcılarının (texture descriptors) hesaplanması ve görselleştirilmesi için hazırlanmıştır. Özellikle Gri Seviye Eş-Olasılık Matrisi (GLCM) gibi yöntemler kullanılarak görüntülerin doku analizleri yapılabilir.

## İçerik
- `GLCM.ipynb`: GLCM (Gray Level Co-occurrence Matrix) tabanlı doku analizi için Jupyter Notebook dosyası.
- `Red_legged_Kittiwake.jpeg` ve `Red_legged_KittiwakeF.jpeg`: Doku analizi için örnek görüntüler.

## Kullanım
1. Gerekli Python kütüphanelerini yükleyin:
    ```bash
    pip install numpy matplotlib scikit-image
    ```
2. `GLCM.ipynb` dosyasını Jupyter Notebook veya Google Colab üzerinde açın.
3. Notebook içerisindeki adımları takip ederek doku analizi işlemlerini gerçekleştirin.

## Açıklama
- **GLCM (Gray Level Co-occurrence Matrix):** Görüntüdeki piksellerin gri seviyelerinin uzamsal ilişkilerini analiz ederek doku özelliklerini çıkarır.
- Proje, temel olarak doku analizi ve görselleştirme üzerine odaklanmıştır.

## Katkı
Katkıda bulunmak isterseniz, lütfen bir pull request oluşturun veya issue açın.

## Lisans
Bu proje MIT lisansı ile lisanslanmıştır. 