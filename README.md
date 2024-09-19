# K-Means-LinearRegression

**K-Means:**

**K-means Algoritmasının Temel Özellikleri:**
**Hızlı ve Etkili:** K-means genellikle hızlı çalışan bir algoritmadır ve büyük veri kümelerinde bile kullanılabilir.
**Kullanımı Basit:** Küme sayısının (k) kullanıcı tarafından önceden belirlenmesi gerekse de uygulaması kolay bir algoritmadır.
**Simetrik Kümeler:** K-means, simetrik ve küresel şekilli kümeler üzerinde iyi çalışır. Ancak, kümelerin şekli karmaşıksa veya boyutları çok farklıysa, algoritmanın performansı düşebilir.

**K-means'in Zayıf Yönleri:**
**Küme sayısının önceden belirlenmesi gerekmesi:** K değeri uygun seçilmezse, sonuçlar hatalı olabilir.
**Başlangıç merkezlerinin rastgele seçilmesi:** K-means başlangıç merkezlerine duyarlıdır. Farklı başlangıç noktaları farklı sonuçlar üretebilir.
**Karmaşık yapıdaki veriler için uygun olmayabilir:** K-means, kümelerin dairesel ya da küresel bir yapıda olduğu varsayımına dayanır. Karmaşık yapılı veri kümelerinde bu algoritma iyi sonuç vermeyebilir.

K-means, özellikle büyük veri kümelerinde hızlı sonuçlar üreten ve uygulaması kolay bir algoritmadır, ancak doğru sonuçlar elde edebilmek için başlangıç noktalarının seçimine ve k sayısının belirlenmesine dikkat etmek gerekir.

![image](https://github.com/user-attachments/assets/5e129f6f-1dfc-45c9-b7a6-0ed188136838)

Bu projede K-Means algoritmasını kullandım. Yukarıdaki çıktıda verilerin PCA ile 2 boyutlu hale getirilip görselleştirme işlem gerçekleştirilmiştir. Renkli görünümlerle birlikte her bir kümenin nasıl ayrıldığını görebiliyoruz.

**LinearRegression:**
**Linear Regression Özellikleri:**
**Basitlik:** Doğrusal regresyon, genellikle veri bilimi ve makine öğrenmesine girişte kullanılan en basit modeldir.
**Yorumlanabilirlik:** Her bağımsız değişkenin, bağımlı değişken üzerindeki etkisini (katsayılarla) doğrudan görmemizi sağlar.
**Genel Kullanım:** İstatistiksel analizlerde ve veri bilimi uygulamalarında oldukça yaygın bir yöntemdir.

**Linear Regression'in Zayıf Yönleri:**
**Doğrusal Varsayım:** Yalnızca bağımsız ve bağımlı değişkenler arasında doğrusal bir ilişki varsa iyi çalışır. Eğer ilişki doğrusal değilse, sonuçlar yanıltıcı olabilir.
**Hata Terimlerinin Normal Dağılımı:** Hata terimlerinin (residuals) normal dağılıma sahip olması ve varyanslarının sabit olması beklenir.
**Aykırı Değerler:** Aykırı değerler (outliers) doğrusal regresyonu kolayca bozabilir.

Doğrusal regresyon, basit yapısı ve kolay uygulanabilirliği ile pek çok farklı alanda kullanılan güçlü bir modelleme tekniğidir. Ancak verinin doğrusal olup olmadığını anlamak ve modeli dikkatlice değerlendirmek önemlidir.

![image](https://github.com/user-attachments/assets/73e744b6-c7ff-416b-ac93-8a138ae0b952)

Bu projede ise LinearRegression algoritması kullandım. Yukarıdaki çıktıda tahminleri ve gerek değerlerin ikili sınıflara dönüştürüldükten sonra  bu iki sınıfın karışıklık matrisini oluşturup görselleştirilmiştir. Bu matris modelin doğruluğunu ve tahminlerin performansını daha iyi anlamamızı sağlamaktadır.



