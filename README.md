#   Donot write in main branch


# task1 Screenshot
![task1 day11](https://user-images.githubusercontent.com/85029049/121675722-67009880-cad1-11eb-96ca-fc2981982c03.png)


# task1 Text File

```
cd /mnt
sudo mkdir new
ls
```


# task2 Screenshot
![task2 day11](https://user-images.githubusercontent.com/85029049/121675977-b941b980-cad1-11eb-85ce-54a89056aad3.png)


# task2 Task File

```
EC2 > EBS > Volume > Create Volume > Actions > Attach Volume

```
# task3 Screenshot
![task3 day11](https://user-images.githubusercontent.com/85029049/121676306-19386000-cad2-11eb-99fa-183f2de70c9d.png)
![task3 2 day11](https://user-images.githubusercontent.com/85029049/121676723-99f75c00-cad2-11eb-9af6-c840881d96d8.png)


# task3 Task File

```
sudo fdisk /dev/xvdf
n ---- Create New Partition
Enter ---- Use Default as Primary Partiton
Enter ---- Use Default as 1 as Partition Number
Enter ---- Use Default as 2048 as First Sector
+1G ---- As Last Sector
p ---- Print Created Partition
w ---- Save Partition
sudo mkfs.xfs /dev/xvdf1
sudo mount /dev/xvdf1 /mnt/new/
df -hT

```

# task4 Screenshot
![task4 day11](https://user-images.githubusercontent.com/85029049/121676744-a11e6a00-cad2-11eb-98ea-ffb611ea3b49.png)

# task4 Task File
```
sudo apt install apache2
systemctl status apache2
```

# task5 Screenshot
![task5 day11](https://user-images.githubusercontent.com/85029049/121676926-db880700-cad2-11eb-8df8-07a5e3d530b6.png)

# task5 Task File
```
cd /etc/apache2/sites-availabile
ls
sudo vim 000-default.conf
   --- Change Document root to /mnt/new/
   --- :wq
systemctl restart apache
```





