Patika Profil Linki 
https://app.patika.dev/mervekskn


# Merge_sort_case

[16, 21, 11, 8, 12, 22] dizisinin Merge Sort'a göre adımları;

Öncelikle diziyi tek eleman kalıncaya kadar ikili parçalara ayrılır.

[16, 21, 11] --- [8, 12, 22]

[16] --- [21, 11] --- [8] --- [12, 22]

[16] --- [21] +++ [11] --- [8] --- [12] +++ [22]

Birleştirme işlemine sayısal değeri küçük olan elemanla başlanır;

[16] --- [11, 21] --- [8] --- [12, 22]

[11, 16, 21] --- [8, 12, 22]

[8, 11, 12, 16, 21, 22]

Big O gösterimi;

O(nlogn)
