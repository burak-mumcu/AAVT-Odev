Bron-Kerbosch algoritması, bir grafın tüm maksimum bağımsız küçük kümelerini (MBC) bulmak için kullanılan bir geri izleme algoritmasıdır.

Maksimum bağımsız küçük kümeler, bir graf içinde birbirine bağlı olmayan en büyük düğüm kümeleridir. Bu kümelerin bulunması, çeşitli uygulamalarda önemli bir rol oynar, örneğin çizge boyama, sosyal ağ analizi, kimyasal bileşiklerin yapısal analizi gibi.

Bron-Kerbosch algoritması, tüm düğümleri kapsayan bir alt kümeyle başlar ve grafın tüm düğümleri bu alt kümeye eklenene kadar işlemi yineler. Bu yinelenme sırasında, her adımda, alt kümeye eklenmeyen bir düğüm seçilir ve bu düğüme komşu olan diğer düğümlerle birlikte bir aday kümesi oluşturulur. Aday kümesi, bu düğümlerin alt kümeyle çakışmayan tüm maksimum bağımsız küçük kümelerini içerir.

Daha sonra, aday kümesi üzerinde bir geri izleme işlemi gerçekleştirilir ve aday kümesinin her elemanı alt kümeye eklenir ve işlem yinelenir. İşlem, alt kümenin maksimum bağımsız küçük küme sayısı değişmeyene kadar yinelenir.

Bron-Kerbosch algoritması, zaman karmaşıklığı ve bellek kullanımı açısından diğer algoritmalardan daha iyi performans gösterir ve birçok uygulama alanında kullanılır.