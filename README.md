# Some codes for NCIplot on Linux

## An example for the software installed on @Pauli

1. On user@Pauli, go to folder `nciplot-3.0`:

> **cd nciplot-3.0**

2. Go to folder `test-cases` and list subfolders in this folder (you should create your subfolder and put .wfn files into here)

> **cd test-cases**

> **ls**

Example:

![image](https://user-images.githubusercontent.com/69685019/165224134-04286a8b-e700-4491-ba7f-b90dd33ec6cc.png)

3. For create a new nci file, go to your subfolder in this folder `test-cases`, copy `Sample-file.nci` to edit it then

Copy code:

> **cp Sample-file.nci New-file.nci** 

 Example: 

Go to subfolder `XCHZ-nH2O` and list files in this folder

![image](https://user-images.githubusercontent.com/69685019/165229835-deac90a0-5eac-4529-b5f6-9382f98286a3.png)

Example: 

cp bro-2h2o.nci test.nci

* Rewrite name of code line "Sample-file.wfn" into "New-file.wfn" after copying by view `test.nci` and then save it

![image](https://user-images.githubusercontent.com/69685019/165256043-2d159ab1-b8c2-47df-b13d-26aa38033a4e.png)

3. Back to initial folder `nciplot-3.0`, access folder `scr` and use nciplot program to run file `Sample-file.nci`

* Note: Folder tree that you had accessed: nciplot-3.0/test-cases/(subfolder)/

> **../../src/nciplot Sample-file.nci**

![image](https://user-images.githubusercontent.com/69685019/165256748-48336d6c-8eef-4514-87bc-7b79ef57b62a.png)

Done!

Now, you get `Sample-file-grad.cube` and `Sample-file-dens.cube` and `Sample-file.vmd` and `Sample-file.dat` to plot with VMD and Gnuplot programs. 

