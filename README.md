# binary_search_tree

Q1-) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1.adım:

root 7 olarak belirlendi buna göre binary search tree adım adım aşağıdaki şekilde oluşturulmuştur.

                     7
                    /   
                   5	   
2.adım:

                      7
                    /   
                   5	   
                  /	  
                1	
3.adım:

                    7
                  /   \
                 5	   8
                /	  
               1	    
4.adım:

                    7
                  /   \
                 5	   8
                /	  
               1	     
                \
                 3
5.adım:

                    7
                   /  \
                 5	   8
                / \  
               1   6     
                \
                 3
6.adım: 

                    7
                   /  \
                 5	   8
                / \  
               1   6     
              / \
             0   3
7.adım:


                    7
                   /  \
                 5	   8
                / \     \
               1   6     9 
              / \
             0   3
8.adım:


                    7
                   /  \
                 5	   8
                / \     \
               1   6     9 
              / \
             0   3
	              \
                   4
                  
9.adım:

                    7
                   /  \
                 5	   8
                / \     \
               1   6     9 
              / \
             0   3
                / \
               2   4
