# Binary-Search-Tree-Projesi

[Patika.dev](https://www.patika.dev/tr)

Verilen Dizinin Binary Search Tree Algoritmasına Göre Aşamaları Yazılan Projedir.

## Soru - 1

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Verilen dizinin Binary-Search-Tree algoritmasına göre ilk aşaması bu diziden bir root(kök) elemanının seçilmesidir.

Bu algoritmaya göre seçilen ilk eleman **7** olacaktır.

Root elemanı seçildikten sonra sırasıyla gelen elemanlar root(kök)den büyükse root'un sağ altına değilse sol alt tarafına yazılacaktır.

Buna göre 

                                        1.Aşama(Kök Elemanın Belirlenmesi)
                                                    7

                                                 2. Aşama
                                                    7
                                                5

                                                 3. Aşama
                                                    7
                                                5
                                            1

                                                 4. Aşama
                                                    7
                                                5       8
                                            1

                                                 5. Aşama
                                                    7
                                                5       8
                                            1
                                                3               -- 3, (7 ve 5 değerlerinden küçük 1 den büyüktür)


                                                6. Aşama
                                                    7
                                                5       8
                                                    6           -- 6, 5'den büyük olduğu için 5'in sağına yazılmıştır.
                                            1
                                                3


                                                7. Aşama
                                                    7
                                                5       8
                                                    6           
                                            1
                                                3
                                        0

                                                8. Aşama
                                                    7
                                                5       8
                                                    6       9          
                                            1
                                                3
                                        0

                                                9. Aşama
                                                    7
                                                5       8
                                                    6       9          
                                            1
                                                3
                                        0           4

                                                10. Aşama
                                                    7
                                                5       8
                                                    6       9          
                                            1
                                                3
                                              2                
                                        0           4