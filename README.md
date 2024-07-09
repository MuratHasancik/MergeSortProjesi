# Merge Sort Projesi
Patika.dev merge sort projesi.

[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

# Dizinin merge sort aşamaları:
![Image](https://ibb.co/rMYXXjn)

# Big-O gösterimi:
Step 1 -> n
Step 2 -> n/2
Step 3 -> n/4
....
Step (n-1) -> (n-1)/2^(n-2)

sum = n + n/2 + ... = n(1 + 1/2 + ...) = nlogn
O(nlogn)

