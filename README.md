# Manga ve Çizgi Roman Çevirici

Bu proje, yapay zeka kullanarak farklı dillerdeki mangaları veya çizgi romanları herhangi bir dile çevirir.

# ÖZELLİKLER


* OCR

Resimlerdeki metinleri çıkarmak için OCR kullanılmaktadır. Bu projede EasyOCR kütüphanesi tercih ettim. 

* Çevri 

Çevri için transformırs kütüphanesi ile farklı dil modellerini çevri için kullanıyorum.


# Gereksinimler

easyocr==1.7.1

transformers==4.41.1

opencv-python==4.9.0.80

tqdm==4.66.2

textwrap3==0.9.2 


# İnput:

file:///home/koesan/%C4%B0ndirilenler/manga_cizgi_roman_ceviri-main/manga/2.jpg

# Output:

![1](https://github.com/koesan/manga_cizgi_roman_ceviri/raw/main/resimler/4.jpg)
