# Insertion Sort Projesi 

### [22,27,16,2,18,6] -> Insertion Sort
1.  Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
>İlk adım olarak en küçük elemanı bul ve listenin başındaki değer ile yer değiştir.
[2, 27, 16, 22, 18, 6] -> en küçük eleman 2

>Geriye kalan kısımda en küçük elemanı bul ve listenin 2. elemanı ile yer değiştir.
[2, 6, 16, 22, 18, 27] -> ikinci en küçük eleman 6

>[2, 6, 16, 22, 18, 27] -> üçüncü en küçük eleman zaten olması gereken yerde, olduğun gibi kal.

>[2, 6, 16, 18, 22, 27] -> 4. en küçük elemanı yerine koymak adına 18 ve 22 yer değiştiriyor.

>22 ve 27 sayıları zaten olması gereken yerdeler. O yüzden diğer aşamada yer değişimi olmuyor. Listemizin son hali şu şekilde:
>>***[2, 6, 16, 18, 22, 27]***
2. Big-O gösterimini yazınız.
>>***O(n^2)*** (average case - worst case)
>>***O(n)*** (best case)
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
>*Average Case* -> Sayının ortada olması  -> [6,16,18,22]
>*Best Case* -> Sayının en başta olması -> [2]
>*Worst Case* -> Sayının en sonda olması -> [27]
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
> Dizi sıralandıktan sonra 18 sayısı dizinin orta kısmında bulunuyor. Bu nedenle 18 sayısının aranması **average case** kapsamına girer.

-----------------------------------------------------------
### **[7,3,5,8,2,9,4,15,6**] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. Adım:
>[2, 3, 5, 8, 7, 9, 4, 15, 6] -> 2 ve 7 yer değiştirdiler.
2. Adım:
>[2, 3, 5, 8, 7, 9, 4, 15, 6] -> 2. en küçük sayı olan '3' zaten ikinci sıradaydı. O yüzden herhangi bir yer değiştirme olmadı.
3. Adım:
>[2, 3, 4, 8, 7, 9, 5, 15, 6] -> 3. en küçük sayı olan 4 ile 3. sıradaki 5 yer değiştirdiler.
4. Adım:
>[2, 3, 4, 5, 7, 9, 8, 15, 6] -> 4. en küçük sayı olan 5 ile 4. sıradaki 8 yer değiştirdiler.
5. Adım:
>[2, 3, 4, 5, 6, 9, 8, 15, 7] -> 6 ile 7 yer değiştirdiler.
