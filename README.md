# algorithmic-trading-strategy-with-python

Staretejim 5 indikatör ile alım satım sinyali oluşturup çoğunluğun oyuna göre alım satım emri vermek. Bu beş indikatöre temel ve teknik analizler sonrasında karar verdim.

#Kullandığım İndikatörler

1.	RSI (Relative Strength Index)

2.  CCI (Commodity Channel Index)
  
3.	Bollinger Bantları

4.	SMA (Simple Moving Average)
   
5.	Hacim


#Kullandığım Ürün ve Platform Seçimi 

Platform olarak, geniş bir kullanıcı kitlesine sahip olan  Binance kripto para borsasını tercih ettim. Seçtiğim ürün AVAX/TRY.Daha sonra alım satım yapabilmek ve veri çekebilmek için Binance hesabı oluşturarak API KEY ve SECRET KEY aldım.

Test aşamasında, gerçek piyasa koşullarında stratejimin performansını değerlendirebilmek adına backtesting yöntemini kullanmayı tercih ettim. Ancak, Binance platformunda bu testi gerçekleştiremediğim için TradingView çevrimiçi platformunu tercih ettim. (TradingView, gerçek zamanlı ve tarihsel fiyat verileri üzerinde stratejileri test etmek ve optimize etmek için popüler bir araçtır.)


#Pythonda Kullandığım Kütüphaneler

Binance -Client : Bu kütüphaneyi kullanarak binance borsasına bağlanılır.

Pandas : Binance'den alınan finansal verileri düzenlemek ve analiz etmek için kullanılır.

Talib (Technical Analysis Library):  Finansal analizde yaygın olarak kullanılan bir teknik analiz aracıdır. Bu kütüphane, çeşitli teknik analiz göstergelerini ve matematiksel hesaplamaları içerir. Projede talib kütüphanesi, teknik analiz indikatörlerini hesaplamak için kullanılmaktadır.

