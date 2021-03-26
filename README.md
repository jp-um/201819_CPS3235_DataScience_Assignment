# 201718 CPS3235 DataScience Assignment (Datasets)

The datasets are split into volumes of (at most) 99MB to get past a github limitation that no file should be larger than 100MB.  It is (relatively) straightforward to assemble these back to the original files, i.e.

```bash
cat task2_KingBase2017-pgn.zip_part0 task2_KingBase2017-pgn.zip_part1 task2_KingBase2017-pgn.zip_part2 task2_KingBase2017-pgn.zip_part3 task2_KingBase2017-pgn.zip_part4 > task2_KingBase2017-pgn.zip
unzip task2_KingBase2017-pgn.zip
```

Note that the order of the files in the `cat` command above is important.  These datasets are stored here for longevity.  Please refer to the original URL's for more updated versions.


The file was originally split with:

```bash
split -a1 -d -b99MB KingBase2017-pgn.zip KingBase2017-pgn.zip_part
```

The dataset for task 3 was harvested by an anacron script I wrote (available on request).

The original datasets were downloaded from:
- [Chess Dataset (Task 2)](http://www.kingbase-chess.net/)

