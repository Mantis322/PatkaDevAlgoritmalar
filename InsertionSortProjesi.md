# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort


* Array içerisinde bulunan ilk elemanın en küçük eleman ile yer değiştirmesi gerekir.

```
[22,27,16,2,18,6] -----> [2,27,16,22,18,6]
```

* Array içerisinde bulunan ikinci elemanın ikinci küçük eleman ile yer değiştirmesi gerekir. (1. elemanın en küçük olduğunu bildiğimiz için işleme dahil etmiyoruz.)
```
[2,27,16,22,18,6] -----> [2,6,16,22,18,27]
```

* Array içerisinde bulunan üçüncü elemanın üçüncü en küçük eleman ile yer değiştirmesi gerekir. (3. küçük sayı olması gerektiği yerde olduğu için ellemiyoruz.)
```
[2,6,16,22,18,27] -----> [2,6,16,22,18,27]
```

* Array içerisinde bulunan dördüncü elemanın dördüncü en küçük eleman ile yer değiştirmesi gerekir.
```
[2,6,16,22,18,27] -----> [2,6,16,18,22,27]
```

* Sıralama istenildiği gibi olmuştur.
```
[2,6,16,18,22,27]
```

* Big O Notation :  O(n2). Liste 6 elemanlı olduğundan O(62)=36 olacaktır.

* Dizi sıralandıktan sonra 18 sayısı ortada olacağından Average Case kapsamındadır.

## İkici Örnek

[7,3,5,8,2,9,4,15,6] -> Insertion Sort

| Adım Sayısı| Girdi| Çıktı|
| :--- | :---: | ---: |
| 1 | [***7***,3,5,8,***2***,9,4,15,6] | [***2***,3,5,8,***7***,9,4,15,6] |
| 2 | [2,3,5,8,7,9,4,15,6| [2,3,5,8,7,9,4,15,6] |
| 3 | [2,3,***5***,8,7,9,***4***,15,6| [2,3,***4***,8,7,9,***5***,15,6] |
| 4 | [2,3,4,***8***,7,9,***5***,15,6| [2,3,4,***5***,7,9,***8***,15,6] |
