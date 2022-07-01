# Proje 3
- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

  Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. 
  
  Cevap :
  
  Root 7 olarak belirleriz.
  
  Adım 1 ) 5 sayısı 7den küçük olduğu için 7'nin soluna eklenir
  
  Adım 2 ) 1 sayısı 7den küçük olduğu için sola bakıyoruz.Solumuzda 5 sayısı var.5den de küçük olduğu için 5 sayısının soluna eklenir

  Adım 3 ) 8 sayısı 7den büyük olduğu için sağa eklenir

  Adım 4 ) 3 sayısı 7den küçük olduğu için sola bakıyoruz.Solumuzda 5 sayısı var.5den küçük olduğu için tekrar sola bakıyoruz.Solumuzda 1 var.1den büyük olduğu için 1in sağına eklenir

  Adım 5 ) 6 sayısı 7den küçük olduğu için solumuza bakıyoruz.Solumuzda 5 sayısı var.5den büyük olduğu için 5in sağına eklenir.

  Adım 6 ) 0 sayısı 7,5,1'den küçük olduğu için 1in soluna eklenir.

  Adım 7 ) 9 sayısı 7den büyük olduğu için sağa bakıyoruz.Sağımızda 8 sayısı var sekizden büyük olduğu için 8in sağına eklenir

  Adım 8 ) 4 sayısı 7den küçük olduğu için sola bakıyoruz.Solumuzda 5 sayısı var.5den de küçük olduğu için tekrar sola bakıyoruz.Solumuzda 1 var.1den büyük olduğu için sağımıza bakıyoruz.Sağımızda 3 var.3den de büyük olduğu için 3ün sağına eklenir

  Adım 9 ) 2 sayısı 7den küçük olduğu için sola bakıyoruz.5den de küçük olduğu için 1 sayısına bakıyoruz.1den büyük olduğu için 1in sağına bakıyoruz.1in sağında 3 var.3den küçük olduğu için 3ün soluna eklenir

                         7
                        / \	
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3
                      / \  
                     2   4