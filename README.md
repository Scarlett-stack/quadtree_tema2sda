# quadtree_tema2sda
implmentare arbore quad pt imagini ppm p6
1. Construire arbore cuaternar
![image](https://user-images.githubusercontent.com/87925542/235298246-7f1e50a4-d12c-49e1-9dbb-c8848260742f.png)
2. Compresia imaginii in fisier binar
3. Decompresia imaginii construirea unui nou arbore si scrierea imaginii
Pentru rulare 
1. make
2. ./quadtree -c1 <factor> <fis in> <fis out>
  ./quadtree -c2 <factor> <fis in> <fis out>
  ./quadtree -d <fis in> <fis out>
Pt valgrind:
  1. make
  2. valgrind -v ./quadtree +Arg 
  setezi ce flaguri vrei.
