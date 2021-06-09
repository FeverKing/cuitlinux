# 作业答案



## 4.9

```bash
#!/bin/bash
dir=$1
shift

while [ $1 ]
do
cp $1 $dir
shift
done

ls $dir
```



## 4.12

```bash
#! /bin/bash

dir=$1

for i in *.c
do
    mv $i ${dir}/
done

cd ${dir}
ls -al .
```





## 4.13

```bash
#! /bin/bash
name=(a b c d e f g h j i)

for i in ${name[*]}
do
echo $i
done
```

