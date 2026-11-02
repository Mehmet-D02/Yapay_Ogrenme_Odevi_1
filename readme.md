# Veri Analizi Projesi

Bu proje, `Advertising.csv`, `tips.csv` ve `OnlineRetail2.csv` veri setlerini kullanarak yapay öğrenme dersi için ödev analizlerini içerir.

## Kurulum

1.  Bu projeyi klonlayın veya indirin.
2.  Proje ana dizininde bir sanal ortam oluşturun:
    ```bash
    python3 -m venv venv
    ```
3.  Sanal ortamı aktif edin:
    * Windows: `.\venv\Scripts\activate`
    * macOS/Linux: `source venv/bin/activate`
4.  Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

## Kullanım

Gerekli tüm CSV dosyaları `data/` klasöründe yer alıyor.

Analizi çalıştırmak için (sanal ortam aktifken):

```bash
python3 analiz.py