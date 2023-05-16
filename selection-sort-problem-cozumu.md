## [22,27,16,2,18,6] Dizisi Üzerinde Selection Sort Problemleri
### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. 22 kendisi hariç tüm değerler ile karşılaştırılır ve neticede 2 ile yer değiştirir. **Dizinin son hali: [2,27,16,22,18,6]**
2. 27 kendisinden sonra ki ve kendi hariç değerler ile karşılaştırılır ve neticede 6 ile yer değiştirir. **Dizinin son hali: [2,6,16,22,18,27]**
3. 16 kendisinden sonra ki ve kendi hariç değerler ile karşılaştırılır ve neticede yer değiştirmez.
4. 22 kendisinden sonra ki ve kendi hariç değerler ile karşılaştırılır ve neticede 18 ile yer değiştirir. **Dizinin son hali: [2,6,16,18,22,27]**
5. **Dizi sıralanmış** vaziyete erişmiştir.

### Big-O gösterimini yazınız.
![big-o gosterimi](https://github.com/muhendisonur/Temel-Algoritmalar/assets/113312815/4725d52b-790a-400d-b9a2-b6519e8337aa)

### Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
18 değeri dizinin ortasında bulunduğu için "Avarage case" kapsamına dahildir.

## [7,3,5,8,2,9,4,15,6] Dizisinin Selection Sort'a Göre İlk 4 Adımını Yazınız
1. 7 değeri kendisinden sonra ki tüm değerler ile karşılaştırılır ve neticede 2 ile yer değiştirir. **Dizinin son hali: [2,3,5,8,7,9,4,15,6]**
2. 3 değeri kendisinden sonra ki tüm değerler ile karşılaştırılır ve neticede yer değişikliği olmaz.
3. 5 değeri kendisinden sonra ki tüm değerler ile karşılaştırılır ve neticede 4 ile yer değiştirilir. **Dizinin son hali: [2,3,4,8,7,9,5,15,6]**
4. 8 değeri kendisinden sonra ki tüm değerler ile karşılaştırılır ve neticede 7 ile yer değiştirilir. **Dizinin son hali: [2,3,4,7,8,9,5,15,6]**
