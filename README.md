# Patika.Dev-Proje1-InsertionSortProjesi
Projede bizden istenilenler aşağıda belirtilmiştir.

a) [22,27,16,2,18,6] -> Insertion Sort

a.1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

a.2) Big-O gösterimini yazınız.

a.3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

a.4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

b) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# a.1) Insertion Sort Aşamaları

Aşama 1: Bize verilen dizide en küçük değeri buluruz. Bu dizide en küçük değer 2 dır. 2 değerini dizinin en solundaki değer(22) ile yer değiştiririz. 

[22,27,16,2,18,6]-->[2,27,16,22,18,6] 

Aşama 2: Aşama 1 de elde ettiğimiz yeni dizi üzerinde ilk indexten sonraki değerlere bakarız. Ardından en küçük değeri(6) bulup ikinci index(27) ile yerlerini değiştiririz.

[2,27,16,22,18,6]-->[2,6,16,22,18,27]

Aşama 3: Aşama 2 de elde ettiğimiz yeni dizi üzerinde ikinci indexten sonraki değerlere bakarız. Ardından en küçük değeri(16) bulup üçüncü index(16) ile yerlerini değiştiririz. Bu aşamada en küçük değerimiz halihazırda üçüncü indextedir. Bu yüzden dizide herhangi bir değişiklik yapılmaz.

[2,6,16,22,18,27]

Aşama 4: Aşama 3 de elde ettiğimiz yeni dizi üzerinde üçüncü indexten sonraki değerlere bakarız. Ardından en küçük değeri(18) bulup dördüncü index(22) ile yerlerini değiştiririz.

[2,6,16,22,18,27]-->[2,6,16,18,22,27]

Aşama 5: Aşama 4 de elde ettiğimiz yeni dizi üzerinde dördüncü indexten sonraki değerlere bakarız. Ardından en küçük değeri(22) bulup beşinci index(22) ile yerlerini değiştiririz. Bu aşamada en küçük değerimiz halihazırda beşinci indextedir. Bu yüzden dizide herhangi bir değişiklik yapılmaz.

[2,6,16,18,22,27]

Sonuç olarak sıralanmış dizimiz [2,6,16,18,22,27] bu şekildedir.

# a.2) Insertion Sort Big-O Gösterimi
Bu sıralama yönteminde elimizde n kadar sayı bulunsun. İlk aşamada n kadar sayı kontrol edilip en küçüğü ilk index ile yer değiştirilir. Ardından ilk index harici kalan sayılar (n-1) kontrol edilip en küçüğü ikinci index ile yer değiştirilir. Bu işlem son sayıya kadar devam eder. n+(n-1)+(n-2)+(n-3).....+1 burdaki işlem 1 den n e kadar olan sayıların toplamını belirtir. Matematikten bildiğimiz üzere 1 den n'e kadar olan sayıların toplamı [n*(n+1)/2] şeklinde bulunur. 

Bunu açarsak (n²+n)/2 elde ederiz. Big-O gösteriminde domine fonksiyon alınır. Burada domine fonksiyon n² dir.

BEST Case -----> o(n)

AVERAGE Case --> o(n²)

WORST Case ----> o(n²)

# a.3) Time Complexity

Average Case: Average case: Aradığımız sayının ortada olması ---> [22,27,16,2,18,6] 








