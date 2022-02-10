
### Gereksinimler

1. [Python 3.7](https://www.python.org/downloads/release/python-370/)
2. [Microsoft Visual C++ build tools](http://go.microsoft.com/fwlink/?LinkId=691126&fixForIE=.exe.) (Sadece Windows için)

------------------------------------------
### Kurulum

* Adım 1: Dosyaların bağlantısı verilen bölümden indirin[buradan](https://drive.google.com/file/d/1C1Rd00ZLMQrK_qEBf9PYLckIixclCYAK/view?usp=sharing) ve Adaptive-Traffic-Signal-Timer/Code/YOLO/darkflow/bin konumuna taşıyınız.

* Adım 2: İndirilen dosyaları kurunuz.
```sh
      # Terminalde, Adaptive-Traffic-Signal-Timer/Code/YOLO/darkflow bölümüne gidiniz.
      $ cd Adaptive-Traffic-Signal-Timer/Code/YOLO/darkflow
      $ pip install -r gereksinimler.txt
      $ python setup.py build_ext --inplace
```

* Adım 3: Kodu Çalıştırın
```sh
      # Araç algılama sistemini çalıştırmak için
      $ python vehicle_detection.py
      
      # Simülasyon programını çalıştırmak için
      $ python simulation.py
```

