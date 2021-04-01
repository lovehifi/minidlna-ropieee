### Hi Audiophile 👋

# MinDLNA to RopieeeXL setup instructions

SSH
> User: root
> 
> Pass: ropieee

###### Step by Step

#1./ **Download**
> 
> 
>
> 
> 
>
####
####
#2./ **WinSCP Copy 3 file from PC to Pi /root/**
> 
>
> 

####
####
#2./ **Extract**
> tar -xf /root/ --overwrite -C /
> 
> tar -xf /root/ --overwrite -C /
>
> tar -xf /root/ --overwrite -C /
>

####
#3./ **Config**

WinSCP edit file
>  /etc/minidlna.conf
>  
Add #
> #user=minidlna
> 
Change media_dir
> media_dir=/mnt
> 

####

####
#4./ **Start Service**

> systemctl daemon-reload
> 
> systemctl enable minidlna.service
> 
> systemctl restart minidlna.service
> 
> systemctl status minidlna.service
####
####
