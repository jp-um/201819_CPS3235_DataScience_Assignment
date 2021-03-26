# 2018/2019 CPS3235 Data Science Assignment (Datasets)

**Dataset for different years may be found in tags in this repository**

GitHub repo for the CPS3235 assignment (2018/2019).  Contains datasets for posterity.

The datasets are split into volumes of (at most) 99MB to get past a github limitation that no file should be larger than 100MB.  It is (relatively) straightforward to assemble these back to the original files, i.e.

```bash
cat 20181216_dblp.xml.gz_part0 20181216_dblp.xml.gz_part1 20181216_dblp.xml.gz_part2 20181216_dblp.xml.gz_part3 20181216_dblp.xml.gz_part4 > 20181216_dblp.xml.gz
gunzip 20181216_dblp.xml.gz
```

Note that the order of the files in the `cat` command above is important.  These datasets are stored here for longevity.  Please refer to the original URL's for more updated versions.


The file was originally split with:

```bash
split -a1 -d -b99MB 20181216_dblp.xml.gz 20181216_dblp.xml.gz_part
```

The dataset for task 3 was harvested by an anacron script I wrote (available on request).

The original datasets were downloaded from:
- [DBLP Computer Science Bibliographic Dataset (Task 1)](https://dblp.uni-trier.de/xml/)

