# Some codes for NCIplot on Linux

## An example for the software installed on @Pauli

1. On user@Pauli, go to folder `nciplot-3.0`:

> **cd nciplot-3.0**

2. Go to folder `test-cases` and list subfolders in this folder

> **cd test-cases**

> **ls**

![image](https://user-images.githubusercontent.com/69685019/165224134-04286a8b-e700-4491-ba7f-b90dd33ec6cc.png)

3. Go to an available subfolder, copy `Sample-file.nci` and `Sample-file.wfn` to edit it then

![image](https://user-images.githubusercontent.com/69685019/165229835-deac90a0-5eac-4529-b5f6-9382f98286a3.png)

> **cp Sample-file.nci New-file.nci** <br>
> **cp Sample-file.wfn New-file.wfn**

* Rewrite name of .wfn after copying by view `test.nci`

![image](https://user-images.githubusercontent.com/69685019/165256043-2d159ab1-b8c2-47df-b13d-26aa38033a4e.png)


3. [Mix step] Back to folder `nciplot-3.0` , access folder `scr` and use nciplot program to run file `Sample-file.nci`

* Note: Folder tree: nciplot-3.0/test-cases/(subfolder)/

> **../../src/nciplot Sample-file.nci**

![image](https://user-images.githubusercontent.com/69685019/165254269-7e49b2dd-f0be-428c-8988-b7ff38665dd7.png)

