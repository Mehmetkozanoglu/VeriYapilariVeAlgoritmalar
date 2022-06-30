# Proje 1
[22,27,16,2,18,6] -> Insertion Short

 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.


Cevap 1 )
1.[2,27,16,22,18,6] = ilk sayı olan 22 ile en küçük sayı olan 2'nin yerini değiştirdik. 
2.[2,6,16,22,18,27] = ikinci sayı olan 27 ile 2den sonraki en büyük sayı olan 6'nın yerini değiştirdik.
3.[2,6,16,22,18,27] = Üçüncü sayı olan 16 6'dan sonraki en küçük sayı olduğu için dokunmadık.
4.[2,6,16,18,22,27] = Dördüncü sayı olan 22 ile 16dan sonraki en küçük sayı olan 18in yerini değiştirdik.
5.[2,6,16,18,22,27] = Beşinci sayı olan 22 18dan sonraki en kücük sayı oldugu için dokunmadık.
6.[2,6,16,18,22,27] = Son olarak son sayıdaki 27 en büyük olduğu için dokunmadık ve bitirdik.


2.Big-O gösterimini yazınız.


Cevap 2 )
n.(n-1).(n-2) ... +1 =(n.(n+1)) / 2'den O(n²) = O(6²)


3.Time Complexity:

Cevap 3 ) Average case:  0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2
          Worst case : n^2 
          Best case  : n 

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Cevap 4 ) Veri setinin ortasında olduğu için average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]

[Ödev Linki](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje)

[Patika.Dev Profile](https://app.patika.dev/mehmetkozanoglu)
