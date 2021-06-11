
# task1 Screenshot

![task2 day11](https://user-images.githubusercontent.com/85029049/121677548-a0d29e80-cad3-11eb-8a77-3550d8d46be8.png)
![task1 day12](https://user-images.githubusercontent.com/85029049/121677586-b5169b80-cad3-11eb-9338-144a7b4fb507.png)

# task1 Text File
```
EC2 > EBS > Volume > Create Volume > Actions > Attach Volume
mount /dev/xvdf1 /root/welcome
df -hT

```

# task2 Screenshot

![task2 day12](https://user-images.githubusercontent.com/85029049/121678006-40902c80-cad4-11eb-8a58-009434217c01.png)



# task2 Text File

```

cd welcome/
vim index.html
cat index.html

```

# task3 Screenshot

![task3 day12](https://user-images.githubusercontent.com/85029049/121678166-7c2af680-cad4-11eb-9457-d7144f133771.png)

![task3 1 day12](https://user-images.githubusercontent.com/85029049/121678135-70d7cb00-cad4-11eb-8597-a16bcb9d1c73.png)


# task3 Text File

```
EC2 > EBS > Volume > Create Volume > Actions > Detach Volume > Attach Volume
cd /etc/apache2/sites-availabile
ls
sudo vim 000-default.conf
   --- Change Document root to /root/new/
   --- :wq
systemctl restart apache2
```


