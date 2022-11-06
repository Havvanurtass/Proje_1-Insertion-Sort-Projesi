# Proje_1-Insertion-Sort-Projesi  www.patika.dev

[22,27,16,2,18,6] -> Insertion Sort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.adım: [22,27,16,2,18,6]
    Başlangıçta, dizinin ilk iki elemanı karşılaştırılır.22,27 den küçük olduğu için yerleri değişmez dizi aynı kalır.

2.adım: [16,22,27,2,18,6]
    16 ve 27 sayısını karşılaştırır 16 27 den küçük olduğu için 16 ve 27 yer değiştirir.
daha sonra 22 ile 16 karşıltırılır 16 22 den küçük olduğu için 16 ve 22 yer değiştirir.

3.adım: [2,16,22,27,18,6]
    2 ile 27 karşılatırılır 2 küçük olduğu için 27 ile yer değiştirilir,2 sayısı 16 ve 22 sayılarıyla da karşılaştırılıp diğer iki sayıdan da küçük olduğu için dizinin en başına geçer.

4.adım: [2,16,18,22,27,6]
    27 ile 18 sayısı karşılaştırılır 18,27 den küçük olduğu için yer değiştirirler , daha sonra 18 sayısı 22 ile karşılaştırılıdığında 22 sayısınıdan küçük olduğu için 16 ile 22 yer değiştirir.

5.adım: [2,6,16,18,22,27]
    27 ile 6 sayısı karşılaştırılır 6,27 den küçük olduğu için 27 ie yer değiştirilir,daha sonra 22 sayısı ile karşılaştırılır 6 küçük olduğu için 22 ile yer değiştirilir 18,6 karşılaştırılır 6 18 den küçük olduğu için 18 ile de yer değiştirir son olarak 16 ile karşılatırılır 6,16 dan küçük olduğu için 16 ile yer değiştirir.
Son olarak dizi tamamen sıralanır.

2)Big-O gösterimini yazınız.

Dizideki elemanları sıraladığı için iki tane iç içe döngüye sahiptir.Bu da n*n sürede gerçekleşir big-o notasyonu O(n^2) 'dir.

3)Time Complexity: 
Average case: Aradığımız sayının ortada olması,O(n^2)
Worst case: Aradığımız sayının sonda olması, O(n^2)
    En kötü durumda veya ortalama durumda bir diziyi sıralamak için geçen süre, dizideki eleman sayısının karesiyle orantılıdır.
Best case: Aradığımız sayının dizinin en başında olması.O(n) 
     Diziyi sıralamak için geçen süre, dizideki elemanların sayısıyla orantılıdır.Dizi zaten sıralıyken iç döngü işlemi önemsiz olduğundan, bu durumda yalnızca bir yineleme vardır.


4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    18 sayısı dizinin ortalarında olduğu için average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.adım: [3,7,5,8,2,9,4,15,6]
    7 ile 3 sayısı karşılatırılır 3 küçük pluduğu için 7 ile yer değiştirir,
2.adım: [3,5,7,8,2,9,4,15,6]
    7 ile 5 karşılaştırılır 5,7 den küçük olduğu için 7 ile 5 yer değiştirir.
3.adım: [3,5,7,8,2,9,4,15,6]
    7 ile 8 karşılaştırılır 7,8 den küçük olduğu için hiç bir değişim olmaz.
4.adım:[2,3,5,7,8,9,4,15,6]
    8 ile 2 karşılaştırılır 2 8 den küçük olduğu için 2 ile 8 yer değiştirir,2 sayısı7,5 ve 3 ile karşılaştırılır 2 hepsinden küçük olduğu için dizinin en başına geçer. 
    

