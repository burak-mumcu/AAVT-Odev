Morris-Pratt algoritması, bir dize (string) içinde bir alt dizenin (substring) eşleşmesini bulmak için kullanılan bir algoritmadır. Bu algoritma, zaman karmaşıklığı açısından KMP (Knuth-Morris-Pratt) algoritması ile benzerlik gösterir, ancak daha az bellek kullanır.

Morris-Pratt algoritması, bir önek fonksiyonu (prefix function) kullanır. Bu fonksiyon, bir dize içindeki her konumda, bu konumun sonuna kadar olan alt dizelerin en uzun öneklerinin uzunluklarını tutar. Önek fonksiyonu, alt dizeyi aramak için kullanılır ve arama işleminde tüm metni tekrar tekrar incelemeyi önler.

Algoritmanın adım adım çalışması şu şekildedir:

Önek fonksiyonunu hesaplayın.
Ana dizeyi ve alt dizeyi karşılaştırmaya başlayın.
Eğer bir karakter eşleşmiyorsa, önek fonksiyonunu kullanarak alt dizenin nereye kadar eşleştiğini bulun ve ana dizede bu kadar geri atlayın.
Eşleşen alt dize bulunana kadar 2. adıma devam edin.
Önek fonksiyonunun hesaplanması, anahtar kısım Morris-Pratt algoritmasında yatar. Önek fonksiyonu hesaplaması, alt dizeyi tarif etmek için kullanılır. Hesaplamak için, bir önceki indekste önek uzunluğunu kullanarak çalışır ve eşleşme bulunamadığında, önek uzunluğunu güncellemek için önek fonksiyonunu kullanır.

Morris-Pratt algoritması, KMP algoritması kadar hızlı olmasa da, daha az bellek tüketir. Bu algoritma, uzun metinler üzerinde çalışırken, bellek tüketimi önemli bir faktör olabileceğinden, tercih edilebilir bir seçenektir.

Kod örnekleri ve uygulamaları için, Morris-Pratt algoritmasını uygulayan açık kaynak kodlu kütüphaneler mevcuttur