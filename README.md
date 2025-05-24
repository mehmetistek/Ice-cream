# Kütüphaneler 

-json-server
-bootstrap
-axios@^0.27.2
-@testing-library/user-event@14.0

# Selector - Seçiciler

-Test içerisinde JSX elementlerini çağırmaya yarayan methodlardır.
-screen nesnesi aracılığıyla kullanılır.
-https://testing-library.com/docs/queries/about/

# HTML Element Rolleri 
-her HTML elementinin kendini temsil eden bir rolü vardır.Bu rol ismi
bazen etiket ismi ile aynı (button'ın rolü button)bazen de farklı(h1'in rolü heading) olabilir.

-https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles

# Matchers - Kontrolcüler
-expect komutu ile birlikte kullanılan ve bir element veya değişken üzerindeki
beklentimizi kontol eden methodlardır. 
örn: (rengi kırmızıdır | checkbox tiklidir | buton aktiftir | yazı içeriği şudur | dizinin uzunluğu 5'tir)

-Değişkenler için kullanılan Matcher'lar:
-https://jestjs.io/docs/using-matchers

-HTML elementi için kullanılan matcher'lar:
-- https://github.com/testing-library/jest-dom

# Test Geliştirme Süreci

## TDD (Test Driven Development)
 - Önce testler yazılır sonra işlevler / bileşenler kodlanır.
 - red to green
 -Artısı, testler bir yük olarak gelmez.Test yazmak geliştirme sürecinin bir parçası oluyor.Testleri yazarken dinamik yapının bir algoritmasını oluşturduğumuz için işlevi daha hızlı kodluyoruz.

## BDD (Behaviour Driven Development)

-Önce işlev/bileşen kodlanır sonra testleri yazılır.

# FireEvent

-rtl içerisinde geçen olay tetiklemek için kullandığımız metod.
-gerçek kullanıcıdan uzak tepkiler verdiği için yerini UserEvent'e bıraktı.

-Tetiklenen olaylar gerçek bir insanın tepkisinden çok daha hızlı bir şekilde aniden gerçekleştiği için testlerde tutarsızlıklara ve beklenmedik sonuçlara sebep olabiliyor.

# UserEvent
-fireEvent'in modern/ gelişmiş versiyonu
-tetikledğimiz olaylar fireEvent gibi doğrudan tetiklenmesi yerine gerçek bir kullanıcıyı simule ederek belirli bir gecikmenin ardından tetiklenir.
- kullanılması için userEvent kütüphanesi kurulmalıdır
-asyn çalıştığı için async await ile kullanılır.

# Mock

-Unit testlerde "mock" kullanımı, bir fonksiyonun veya nesnenin belirli
bir kısmını izole ederek test etmeye yarar.Özellikle dış bağımlılıkları olan 
fonksiyonları test etmek için kullanılır.Bu sayede gerçek sistem bileşenlerine bağımlı olmadan sadece test edilmek istenen kodun doğru çalışıp çalışmadığı kontrol edilir.

-DışaBağımlılıkları izole ederiz.

-Fonksiyonlar çağrıldı mı kontrolü yapmamızı sağlar.

-Fonksiyonlara gönderilen parametreleri kontrol edilebilir.

# 100% Test Coverage# Ice-cream

Screen Gif
![Image](https://github.com/user-attachments/assets/e1031cc4-0bcf-415e-91b6-fa448ee75310)
