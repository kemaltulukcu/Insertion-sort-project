# Proje 1
## [22,27,16,2,18,6] -> Insertion Sort

*Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
### [2,27,16,22,18,6]
### [2,6,16,22,18,27]
### [2,6,16,18,22,27]

*Big-O gösterimini yazınız.
### [22,27,16,2,18,6] -- (n)
### [2,27,16,22,18,6] -- (n-1)
### [2,6,16,22,18,27] -- (n-2)
### [2,6,16,18,22,27] -- (1)
### n+(n-1)+(n-2)+1=n(n+1)/2=(n^2)*n/2 ise, Domine eden fonksiyon n^2 olduğu için Big-O(n^2) olur.

*Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
### [2,6,16,18,22,27] sıralamasında 18 sayısı ortada olması sebebi ile Average case kapsamına girer.

*[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
### [2,3,5,8,7,9,4,15,6] -- 1. adım
### [2,3,4,8,7,9,5,15,6] -- 2. adım
### [2,3,4,5,7,9,8,15,6] -- 3. adım
### [2,3,4,5,6,9,8,15,7] -- 4. adım
