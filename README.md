# lab1_BASH
tail -n 40 file1.txt>file2.txt

head -n 10 file2.txt>file3.txt

grep koko file2.txt>fileSave.txt&&sed -i 's/koko/kyky/g' fileSave.txt

head -n 3 fileSave.txt>>file3.txt

sort file3.txt|uniq -c&&sort -u file3.txt -o file3.txt!

[bashScreen](https://user-images.githubusercontent.com/52314995/158367801-be14ede8-b3ad-49d8-905a-7becc99fd572.png)
