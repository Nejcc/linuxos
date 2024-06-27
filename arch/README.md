
https://archlinux.org/

https://archlinux.org/download/

1. 
![alt text](media/1.png "Title")
2. 
![alt text](media/2.png "Title")

![alt text](media/3.png "Title")

![alt text](media/4.png "Title")

![alt text](media/5.png "Title")

![alt text](media/6.png "Title")
![alt text](media/7.png "Title")
![alt text](media/8.png "Title")
![alt text](media/9.png "Title")
![alt text](media/10.png "Title")
![alt text](media/11.png "Title")
 after installing type ```exit```
 and then ```shutdown -h now```
 ![alt text](media/12.png "Title")

then start again and login as user you created

 ![alt text](media/13.png "Title")

 as you can see GDM is not started yet. this is because we didnt link (enabled system service) it

```sudo systemctl enable gdm.service```

 ![alt text](media/14.png "Title")

 ```sudo systemctl start gdm.service```

  ![alt text](media/15.png "Title")

desc env

- gnome (default) + GDM (display manager)
- kde


select grub for bootloader

sudo pacman -S neofetch