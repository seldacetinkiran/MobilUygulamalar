## Görünüm Yerleştirme Yöntemlereri ##

wrap_content: Bir Component'in içeriğinin tamamı görünecek kadar olan bir  boyutlandırma seçeneğidir. 

match_parent: Cihazın ekranının tamamını kaplayacak şekilde olan bir boyutlandırma seçeneğidir.


![image](https://user-images.githubusercontent.com/69754028/210307345-34c2252e-10c5-4baa-a04b-d4a97ede6e52.png)

(Kaynak: Mesleki ve Teknik Anadolu Lisesi Bilişim Teknolojileri Alanı mobil Uygulamalar ders materyali)

Genişlik ve yükseklik değerlerini verirken wrap_content ve Match_parent yerine sayısal olarak değer de verebiliriz.

Ölçü Birimleri

px (Pixels):  Ekrandaki gerçek piksellere karşılık gelir.
in (Inches):   Ekrandaki inç olarak karşılığıdır.
mm (Millimeters):  Ekrandaki mm olarak karşılığıdır.
pt (Points): Ekranın fiziksel boyutuna bağlı olarak 1/72 inç oranındadır.
dp (Density-independent Pixels): Ekranın fiziksel yoğunluğunu temel alan soyut bir birim. Bu birimler 160 dpi ekrana göredir, bu nedenle 160 dpi ekranda bir dp, bir pikseldir. Dp-piksel oranı, ekran yoğunluğu ile değişecektir, ancak doğrudan orantılı olması gerekmez

sp (Scaleable-independent Pixels):Bu, dp birimi gibidir, ancak kullanıcının yazı tipi boyutu tercihine göre de ölçeklenir. Yazı tipi boyutlarını belirtirken bu birimi kullanmanız önerilir, böylece hem ekran yoğunluğuna hem de kullanıcının tercihine göre ayarlanacaktır.
