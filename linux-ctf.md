

### ls
```
lab@29d4cf5af0ab:~$ ls
base64.txt  flag  hex.txt
直接執行 ls 帶任何參數的話，會列出目前目錄中的檔案與目錄列表。
```
```
cat flag
把檔案串連接後傳到基本輸出
```
### ls -l
```
-l 參數可以顯示檔案與目錄的詳細資訊
lab@29d4cf5af0ab:~$ ls -l
total 12
-rw-rw-r-- 1 root root 46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root 35 Nov 15  2017 flag
-rw-rw-r-- 1 root root 68 Nov 20  2017 hex.txt
```
### ls -Al
```

lab@29d4cf5af0ab:~$ ls -Al
total 28
-rw-r--r-- 1 lab  lab   220 Apr 26 14:48 .bash_logout
-rw-r--r-- 1 root root 3771 Apr 26 14:48 .bashrc
-rw-rw-r-- 1 root root   34 Nov 19  2017 .hidden
-rw-r--r-- 1 lab  lab   655 Apr 26 14:48 .profile
-rw-rw-r-- 1 root root   46 Nov 20  2017 base64.txt
-rw-rw-r-- 1 root root   35 Nov 15  2017 flag
-rw-rw-r-- 1 root root   68 Nov 20  2017 hex.txt


```
### ls -al
```
`參數『-al』則表示列出所有的檔案
## 指令參數的學習
```
ls -h
ls --h
ls -help
ls --help
```
```
到google 搜尋linux ls
-a --all列出所有的檔案，包含以「.」開頭的隱藏檔
-A --almost-all列出所有的檔案，隱藏檔，但不包括「.」與「..」兩個目錄
-C --list entries by colums按行列列舉資料
--color --to distinguish file types藉顏色辨認檔案特性，正常檔案（黑色）；可執行檔（綠色）；連鎖（淺藍色）；目錄（藍色），
-d --directory列出目錄本身，而不列出目錄內的檔案
-F --clasify分類「*」代表可執行檔；「/」代表目錄；「=」代表socket檔「|」代表FIFO檔
-h --human-readable檔案大小單位，以容易閱讀的方式顯示
-i --inode索引節點
-l --use a long listing format以長格式表示，包含檔案屬性。
-r --reverse英文字母由大向小排序
-R --recursive遞迴地列出目錄樹下的所有內容
-s --size檔案大小
-S --sort by file size依佔用空間大小掛序
-t --time依照檔案的修改時間排序
