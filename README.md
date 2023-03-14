Algoritma, bir problemin çözümü için tasarladığımız adımlar bütünüdür.
`Time complexity` oluşturulan bir algoritmayı çalıştırmak için gereken zamanı yani algoritma çalışırken gerçekleşecek işlem sayısını ifade eder. 
`Big O Notation` ise bu zamanı yani algoritmanın performansını hesaplamak için kullanılır.

Algoritmalar iki grupta incelenir:
* Sorting Algoritmalar
* Searching Algoritmalar

# Sorting Algoritmalar
Sorting algoritmalar elimizde bulunan sayı dizisini, belirlediğimiz bir sıralama ölçütüne göre sıralamamıza denir.
Sıralanmış bir veride eleman aramak daha kolay ve hızlı gerçekleşir.

Sorting algoritmalar üç grupta incelenir:
* Selection Sort
* Merge Sort
* Quick Sort

### Selection Sort
Selection sort algoritması elimizdeki sayı dizisini kendi arasında sıralarken ilk önce dizide bulunan ilk eleman ile dizideki diğer elemanları kıyaslar. İncelenen elemandan 
daha küçük bir eleman buldukça yer değiştirerek bütün elemanları inceler. Böylelikle ilk eleman için dizideki en küçük sayıyı bulmuş olur. Bu işlemleri dizideki bütün 
elemanlar bitene kadar sayı dizisinde bulunan bütün elemanlara uygular.

### Merge Sort
Merge sort algoritması elimizdeki sayı dizisini parçalara ayırarak daha küçük sayı dizilerini kendi aralarında sıralayarak birleştirir. Algoritma ilk önce sayı dizisini 
tek eleman kalıncaya kadar ikiye ayırır. Daha sonra dizi parçalarını ayırdığı parçaları kendi aralarında sıralayıp birleştirir. Bu işlemleri sayı dizisi tekrar bir bütün 
haline gelene kadar devam ettirir.

# Searching Algoritmalar
Searching algoritmalar elimizde bulunan sayı dizisinden belirtilen özellikte bir veriyi bulup getirmemize denir.

Searching algoritmalar üç grupta incelenir:
* Linear Search
* Binary Search
* Binary Search Tree

### Binary Search Tree
Binary search tree algoritması ilk önce elimizdeki sayı dizisinin ilk elemanını referans alacak şekilde sayı dizisindeki diğer elemanları referans eleman ile 
karşılaştırır. Karşılaştırılan eleman referans alınan elemandan büyükse sağ tarafa, küçükse sol tarafa olacak şekilde bir dal çizilerek eleman o dala yazılır.
Sırasıyla her eleman ağaca yazılan elemanlar ile karşılaştırılarak bir sayı ağacı oluşturulur.

`.md` uzantılı dosyalarda bu algoritmaların örneklerine ulaşılabilir.

