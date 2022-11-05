
# [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

  Dizinin ilk elemanını root olarak alıp sonraki her bir elemanı büyük ise sağ tarafa, küçük ise sol tarafa ekleyerek adım adım binary search tree oluşturuyoruz. 



```
              7
```

```
              7
             / 
            5
```

```
              7
             / 
            5   
           / 
          1   
```

```
              7
             / \
            5   8
           / 
          1   
```           
   
```   
              7
             / \
            5   8
           / 
          1   
           \
            3
```

```
              7
             / \
            5   8
           / \
          1   6
           \
            3
```

```            
              7
             / \
            5   8
           / \
          1   6
         / \
        0   3
```

```        
                7
             /     \
            5       8
           / \       \
          1   6       9
         / \
        0   3
 ```           
 
 ```       
                7
             /     \
            5       8
           / \       \
          1   6       9
         / \
        0   3
             \
              4
 ```       
 
 ```       
                7
             /     \
            5       8
           / \       \
          1   6       9
         / \
        0   3
           / \
          2   4
 ```       
        
        
        
        
        
        
        
        
        
        
