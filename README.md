# Web_Design_Practice
This repository contains my very primitive web design practice

## How to install (or say construct) your own website on your own Linux workstation server in nctu
1.You have to apply an account at EC324 in NCTU

2.SSH into your Linux workstation
```
ssh yourusername@linux1.cs.nctu.edu.tw
```
![alt text](https://github.com/Alfons0329/Web_Design_Practice/blob/master/Tutorial/scn1.png)


3.
Upload all your needed file into your FTP server same as the ID/PW you use to login the Linux workstation
make a directory named public_html put your needed file in it.

![alt text](https://github.com/Alfons0329/Web_Design_Practice/blob/master/Tutorial/scn2.png)

4.Make it rwxr-xr-x (self-group-other)
```
chmod 755 /public_html
```
