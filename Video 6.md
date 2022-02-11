# Rangkuman Video #6 GIT BRANCH & MERGE

## Membuat Branch
- masuk ke folder repo dan branch yang ingin dibuat branchnya
- buat branch : $ git branch <nama_branch>
  ![image](https://user-images.githubusercontent.com/95738230/153651506-4a143e1f-8c34-459b-8547-ff92b020057b.png)

## Commit di Branch baru
- checkout ke branch yang diinginkan : $ git checkout <nama_branch>
  ![image](https://user-images.githubusercontent.com/95738230/153654158-dd89b0d8-3767-4bb9-9b0f-f3d420abe1f2.png)
- staging semua perubahan yang dilakukan : $ git add .
 ![image](https://user-images.githubusercontent.com/95738230/153655184-e882cc09-25e4-4020-a9df-7aeddacc6e7f.png)
- commit semua perubahan : $ git commit -m ""
  ![image](https://user-images.githubusercontent.com/95738230/153653920-cd558218-611d-438a-a59a-a7fc36ce58fa.png)

## Merge
Ada 2 tipe merge yaitu :

### Fast Forward Merge
ketika branch yang ingin dimerge mempunyai direct path ke branch tujuan merge
- checkout ke branch yang menjadi tujuan merge
  ![image](https://user-images.githubusercontent.com/95738230/153656170-1a48f1ea-be65-48e3-9ba5-f57a53973997.png)
- merge branch yang diinginkan : $ git merge <nama_branch>
  ![image](https://user-images.githubusercontent.com/95738230/153656649-21deb5c9-1d3a-41af-8c7a-0942b83174ae.png)

### Three-way Merge
ketika branch yang dinginkan tidak mempunyai direct path ke branch tujuangit 
- checkout ke branch yang menjadi tujuan merge
  ![image](https://user-images.githubusercontent.com/95738230/153658895-23276eae-5bf1-4750-973b-6778f46e19c7.png)
- merge branch yang diinginkan : $ git merge <nama_branch>
  
