# This is PART 3 of the Domino SCE training  
### We assume you have done Part 1 and 2. 
### Good Luck!
##
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/intro/3.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/1.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/2.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/3.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/4.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/ws-launch-time.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/5.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/6.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/7.png)

```sas
* Simple example of a Data Management Program - SDTM;
 
libname RAW "THIS IS WHERE YOUR RAW PATH GOES" access=readonly;
libname  SDTM "THIS IS WHERE YOUR SDTM PATH GOES";
 
data sdtm.dm (keep=usubjid age ageu);
  set raw.demog;
  usubjid = pt;
  ageu = "YEARS";
run;
```

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/8.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/9.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/10.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/11.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/12.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/13.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/14.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/15.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/16.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/17.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/18.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/19.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/20.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/21.png)

<!--![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/22.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/23.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/24.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/25.png)-->
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/26.png)
