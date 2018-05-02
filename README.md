# binary-search
binary search tanımlaması

İkili Arama (Binary Search)
-Parçala ve fethet yöntemiyle çalışır.
-Big O'su O(logn)'dir.
-Dizi sıralı olmalıdır.

->Çalışma Mantığı
-Dizinin indis bakımından ortanca elemanı bulunur.
-Eğer aranan eleman, ortanca elemana eşitse aramayı sonlandır.
-Eğer eşit değilse ve ortanca elemandan büyükse ortadaki elemanın sağ tarafına(büyük olanına) bak.
O kısmı da ikiye böl ve aynı şekilde karşılaştır.
-Eğer eşit değilse ve ortanca elemandan küçükse ortadaki elamanın sol tarafına(küçük olanına) bak.
O kısmı da ikiye böl ve aynı şekilde karşılaştır.
-Eğer aramadaki bakılan aralık 1 veya daha küçükse aranan eleman bulunamamıştır.

-> İkili Arama Algoritmasının Mantığı : Diziyi ortadan ikiye bölerek aramayı kolaylaştırmaktır.
