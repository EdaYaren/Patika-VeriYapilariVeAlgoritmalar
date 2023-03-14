# VERİ YAPILARI VE ALGORİTMALAR

## PROJE 2

* [16,21,11,8,12,22]  Yandaki dizinin merge sort türüne göre aşamalarını yazınız.

1.adım: [16,21,11] … [8,12,22]

Dizi iki parçaya ayırılır.

2.adım: [16] , [21,11] … [8] , [12,22]

Diziler tekrar iki parçaya ayrılır.

3.adım: [16] , [21] , [11] … [8] , [12] , [22]

Tek eleman kalıncaya kadar diziler parçalanır.

4.adım: [16] , [11,21] … [8] , [12,22]

En sondan başlanarak diziler sıralı bir şekilde birleştirilir.

5.adım: [11,16,21] … [8,12,22]

6.adım: [8,11,12,16,21,22]

* Yukarıda verilen dizinin Big-O gösterimini yazınız.

Her adımda oluşan diziler ikiye bölündüğü için her adımda n elemana karşı logn kadar işlem yaparız. Böylelikle big o notation gösterimi O(nlogn) olur.

[https://app.patika.dev/yarenozel](https://app.patika.dev/yarenozel)
