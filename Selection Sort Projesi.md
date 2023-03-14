# VERİ YAPILARI VE ALGORİTMALAR

## PROJE 1

* [22,27,16,2,18,6] 
Yukarıda verilen dizinin insertion sort türüne göre aşamalarını yazınız.
    
1.adım: [2,27,16,22,18,6]

Dizideki bütün elemanlar incelenir ve en küçük eleman 2 olarak belirlenir. Bulunan elemanın en başta yer alan 22 ile yerleri değiştirilir.

2.adım: [2,6,16,22,18,27] 

Dizideki ilk eleman atlanarak diğer elemanlar incelenir ve ikinci en küçük eleman 6 olarak belirlenir. Bulunan elemanın en başta ikinci sırada yer alan 27 ile yerleri değiştirilir.

3.adım: [2,6,16,22,18,27] 

Dizideki ilk iki eleman atlanarak diğer elemanlar incelenir ve üçüncü en küçük eleman 16 olarak belirlenir. Bulunan eleman en başta üçüncü sırada yer aldığı için yer değiştirme yapılmaz.

4.adım: [2,6,16,18,22,27]

Dizideki ilk üç eleman atlanarak diğer elemanlar incelenir ve dördüncü en küçük eleman 18 olarak belirlenir. Bulunan elemanın en başta dördüncü sırada yer alan 22 ile yerleri değiştirilir.

5.adım: [2,6,16,22,18,27] 

Dizideki ilk dört eleman atlanarak diğer elemanlar incelenir ve beşinci en küçük eleman 18 olarak belirlenir. Bulunan eleman en başta beşinci sırada yer aldığı için yer değiştirme yapılmaz.

6.adım: [2,6,16,22,18,27] 

Dizideki ilk beş eleman atlanarak diğer elemanlar incelenir ve altıncı en küçük eleman 27 olarak belirlenir. Bulunan eleman en baştan altıncı sırada yer aldığı için yer değiştirme yapılmaz.
	
* Yukarıda verilen dizinin Big-O gösterimini yazınız.
    
1.adımda n, 2.adımda n-1, 3.adımda n-2, 4.adımda n-3, 5.adımda n-4 ve 6.adımda n-5 tane eleman incelenmiştir. Bu da bize 1’den n’e kadar olan sayıların toplamı (n(n+1)/2=(n^2+n)/2)  kadar iş yaptığımızı gösterir. Big o notation gösterimi ise dominant factor n^2 olduğu için O(n^2) olur.

* Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

(Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.)
    
18 sayısı sıraladığımız listede ortada olduğu için Average case kapsamına girer.

* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
    
1.adım: [7,3,5,8,2,9,4,15,6]

Dizide yer alan bütün elemanlar incelenir ve en küçük eleman 2 olarak belirlenir. Bulunan elemanın en başta yer alan 7 ile yerleri değiştirilir.

2.adım: [2,3,5,8,7,9,4,15,6]

Dizide ilk eleman atlanarak diğer elemanlar incelenir ve ikinci en küçük eleman 3 olarak belirlenir. Bulunan eleman baştan ikinci sırada yer aldığı için yer değiştirme yapılmaz.

3.adım: [2,3,4,8,7,9,5,15,6]

Dizideki ilk iki eleman atlanarak diğer elemanlar incelenir ve üçüncü en küçük eleman 4 olarak belirlenir.  Bulunan elemanın en başta üçüncü sırada yer alan 5 ile yerleri değiştirilir.

4.adım: [2,3,4,5,7,9,8,15,6]

Dizideki ilk üç eleman atlanarak diğer elemanlar incelenir ve dördüncü en küçük eleman 5 olarak belirlenir.  Bulunan elemanın en başta dördüncü sırada yer alan 8 ile yerleri değiştirilir.

`https://app.patika.dev/yarenozel`
