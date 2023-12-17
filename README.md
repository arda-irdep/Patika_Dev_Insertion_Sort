# Patika_Dev_Insertion_Sort
Patika.dev Data Structures and Algorithms course Insertion Sort assignment

Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Solution:

    Data set: [22,27,16,2,18,6]

    Sorting Algorithm: Insertion Sort

    1) [22, 27, 16, 2, 18, 6] -> After first pass, we compare 27 with 22. Since 27 > 22, no swapping needed. The sorted part is still [22]. We move the pointer to the next unsorted element 16.

    2) [22, 16, 27, 2, 18, 6] -> Now we compare 27 with 16. Since 27 > 16, no swapping needed. The sorted part becomes [22, 16]. Move the pointer to the next unsorted element 2.

    3) [2, 16, 27, 22, 18, 6] -> Compare 27 with 2. Swap them since 2 < 27. New sorted part is [2, 16], and move the pointer to the next unsorted element 18.

    4) [2, 16, 18, 27, 22, 6] -> No need to swap because 18 < 27. Sorted part grows to [2, 16, 18]. Move the pointer to the last unsorted element 6.

    5) [2, 6, 16, 18, 27, 22] -> Compare 27 with 6. Swap them since 6 < 27. New sorted part is [2, 6, 16, 18]. Move the pointer back to start from the beginning again.

    6) [2, 6, 16, 18, 22, 27] -> Finally, compare 27 with 22. Don't need to swap. Finished going through all the elements.

    So the sorted dataset is now [2, 6, 16, 18, 22, 27].

    Big O: O(n^2)

    Time Complexity:

    Average case: The number we are looking for is in the middle of the array. (18)

    0) [7,3,5,8,2,9,4,15,6]
    1) [2,3,5,8,7,9,4,15,6]
    2) [2,3,4,8,7,9,5,15,6]
    3) [2,3,4,5,7,9,8,15,6]
    4) [2,3,4,5,7,8,9,15,6]
