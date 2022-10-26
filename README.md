# Proje1 - Insertion Sort

[22,27,16,2,18,6] -> insertion sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
   
      - [22,27,16,2,18,6] (n)
   
      - [2,22,27,16,18,6] (n-1)
   
      - [2,6,22,27,16,18] (n-2)
   
      - [2,6,16,22,27,18] (n-3)
   
      - [2,6,16,18,22,27] (1)
   
2. Big-O gösterimini yazınız.
   
      - Big O -> (n.(n+1))/2 = ((n^2)+n)/2
   
      - Big O -> O(n^2)
      
3. Time complexity.

      - Average Case: [2,6,16,18,22,27] -> 16 veya 18 sayısı
      
      - Worst Case  : [2,6,16,18,22,27] -> 27 sayısı
      
      - Best Case   : [2,6,16,18,22,27] -> 2 sayısı
      
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
     
      - [2,6,16,>18<,22,27] --> 18 sayısı dizinin ortasında olduğu için 'Average Case' kapsamına girer.
      
      
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
      
       - [2,7,3,5,8,9,4,15,6]
      
       - [2,3,7,5,8,9,4,15,6]
      
       - [2,3,4,7,5,8,9,15,6]
      
       - [2,3,4,5,7,8,9,15,6]

www.patika.dev
        
   
   
   
   
