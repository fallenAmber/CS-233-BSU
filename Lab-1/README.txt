2.

** cd or cd.. :

cd or Change Directory changes the current working directory, while cd.. takes us back to the previous directory.

** ls:

This command lists all the files in the current directory except the hidden files.

** pwd :

Alos known as 'print working directory'. Gives us the path to the working directory.

** cp and mv :

cp copies the files but it keeps the original files as they are. On the other hand, mv moves is used for moving or renaming the files, but it deletes the original files.

** rm :

rm is used for removing files and directories.

** To determine which version of Python I am running, I have to open the command prompt and and simply type python.
** To run a python program, I have to open the command prompt, navigate to the directory where the program file is located. Then I have to type python before the file name with extention and hit enter.

3.

In [2]: cd D:/
D:\
In [4]: ls

 Volume in drive D is Software
 Volume Serial Number is A8AF-978A

 Directory of D:\

In [9]: pwd
Out[9]: 'D:\\'

**


In [1]: cd C:\\Users\\Tanzid\\30 days of ML
C:\Users\Tanzid\30 days of ML

In [2]: ls
 Volume in drive C has no label.
 Volume Serial Number is 725A-A421

 Directory of C:\Users\Tanzid\30 days of ML

01/23/2022  01:24 PM    <DIR>          .
01/23/2022  01:24 PM    <DIR>          ..
01/23/2022  01:24 PM    <DIR>          .ipynb_checkpoints
01/23/2022  01:24 PM                72 addition.ipynb
09/10/2021  12:28 PM            14,819 Categorical Variables.ipynb
09/03/2021  10:38 PM            10,531 chaii - Hindi and Tamil Question Answering.ipynb
08/19/2021  02:49 AM            41,938 day 8-9.ipynb
08/18/2021  11:08 AM         2,091,239 melb_data.csv
09/10/2021  03:50 AM            21,417 Missing Values.ipynb
09/15/2021  12:08 PM    <DIR>          NLP
09/03/2021  10:22 PM           140,558 test.csv
09/03/2021  10:22 PM        31,660,461 train.csv
08/09/2021  11:53 AM            10,024 Untitled.ipynb
08/19/2021  02:38 AM             1,534 Untitled1.ipynb
01/23/2022  12:34 PM             1,012 Untitled2.ipynb
              11 File(s)     33,993,605 bytes
               4 Dir(s)   8,869,650,432 bytes free

In [4]: %run addition.ipynb


