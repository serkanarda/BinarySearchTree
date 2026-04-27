# BinarySearchTree
 Binary Search Tree Projesi

Dizimiz: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Binary Search Tree (BST) Aşamaları:

Adım 1: Dizinin ilk elemanı olan 7 root (kök) düğümdür.
Adım 2: Sıradaki sayı 5. Kökten (7) küçük olduğu için 7'nin soluna eklenir.
Adım 3: Sıradaki sayı 1. 7'den küçük (sola in), 5'ten küçük (sola in). 5'in soluna eklenir.
Adım 4: Sıradaki sayı 8. 7'den büyük olduğu için 7'nin sağına eklenir.
Adım 5: Sıradaki sayı 3. 7'den küçük (sola in), 5'ten küçük (sola in), 1'den büyük (sağa git). 1'in sağına eklenir.Adım 6: Sıradaki sayı 6. 7'den küçük (sola in), 5'ten büyük (sağa git). 5'in sağına eklenir.
Adım 7: Sıradaki sayı 0. 7'den küçük, 5'ten küçük, 1'den küçük. 1'in soluna eklenir.
Adım 8: Sıradaki sayı 9. 7'den büyük (sağa in), 8'den büyük (sağa git). 8'in sağına eklenir.
Adım 9: Sıradaki sayı 4. 7'den küçük, 5'ten küçük, 1'den büyük, 3'ten büyük. 3'ün sağına eklenir.
Adım 10: Sıradaki sayı 2. 7'den küçük, 5'ten küçük, 1'den büyük, 3'ten küçük. 3'ün soluna eklenir.
Tüm bu yerleştirmeler bittikten sonra ağacın haritası (şeması) şu şekilde görünür:

      	  7
        /   \
       5     8
      / \     \
     1   6     9
    / \
   0   3
      / \
     2   4

---------------------------------------


