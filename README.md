# CLTV_PREDICTION
Customer Life Time Value Prediction


![image](https://github.com/furkansukan/CLTV/assets/115731123/302eaf5e-177f-4ccc-a249-2ee93154c449)


Müşteri Ömrü Değeri (Customer Lifetime Value - CLTV), bir müşterinin belirli bir süre içinde bir şirket için ne kadar değer yaratacağını tahmin etmek için kullanılan bir yöntemdir.

CLTV yöntemi iki ana bölümden oluşur:

BG/NGD (Beta Geometrik/Negatif Binom Dağılımları) Alt Modeli: Koşullu beklenen işlem sayısının hesaplanması,
Gamma Gamma Alt Modeli: Koşullu beklenen ortalama karın hesaplanması.
CLTV modelinde BetaGeoFitter kullanılır.

Öngörü fonksiyonları haftalık olarak zamanlanırken, BetaGeoFitter fonksiyonunun zaman değişkeni aylık olarak hesaplanır.

Online Retail II Veri Kümesi Bilgileri: (https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

Veri kümesi, 01/12/2009 ile 09/12/2011 tarihleri arasında gerçekleşen çevrimiçi perakende olmayan işlemleri içerir. Şirket genellikle eşsiz her türlü özel hediye eşyası satmaktadır. Şirketin birçok müşterisi toptancılardır.
