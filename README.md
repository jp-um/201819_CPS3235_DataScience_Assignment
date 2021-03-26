# 201617 CPS3235 DataScience Assignment (Datasets)

The datasets are split into volumes of (at most) 99MB to get past a github limitation that no file should be larger than 100MB.  It is (relatively) straightforward to assemble these back to the original files, i.e.

```bash
cat task1_dblp.xml.gz_part0 task1_dblp.xml.gz_part1 task1_dblp.xml.gz_part2 task1_dblp.xml.gz_part3 > task1_dblp.xml.gz
gunzip task1_dblp.xml.gz
```

Note that the order in the `cat` command above is important.  Similarly for the task2 split dataset.  These datasets are stored here for longevity.  Please refer to the original URL's for more updated versions.

The original datasets were downloaded from:
- [dblp Dataset (Task 1)](http://dblp.uni-trier.de/xml/)
- [Chess Dataset (Task 2)](http://www.kingbase-chess.net/)

