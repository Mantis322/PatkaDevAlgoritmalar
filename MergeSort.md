# Marge Sort
[16,21,11,8,12,22] -> Merge Sort

                [16,21,11,8,12,22] 
         [16,21,11]              [8,12,22] 
       [16] [21,11]              [8]   [2,22]
     [16]  [21]  [11]         [8]    [12]   [22]
      [16] [11,21]            [8]    [12,22]
    [11,16,21]                  [8,12,22]
            [8,11,12,16,21,22]  
            
* Merge sort'un Big o gösterimi: O(nlogn). Liste 6 elemanlı olduğundan O(6log6) olacaktır.
