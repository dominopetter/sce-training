# This is PART 4 of the Domino SCE training  
### We assume you have done Part 1, 2 and 3. 
### Good Luck!
##
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/intro/4.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/1.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/2.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/3.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/4.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/5.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/6.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/7.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/8.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/9.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/10.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/11.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/12.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/13.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/14.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/15.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/16.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/7%202.png)

```sas
* A simple SDTMQC program;
 
libname RAW "THIS IS WHERE YOUR RAW PATH GOES" access=readonly;
libname SDTM "THIS IS WHERE YOUR SDTM PATH GOES" access=readonly;
libname SDTMQC "THIS IS WHERE YOUR SDTMQC PATH GOES";
 
* Create a QC Dataset;
data sdtmqc.dm;
  set raw.demog;
run;
 
proc compare base=SDTMQC.DM compare=SDTM.DM;
run;
```

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/17.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/18.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/19.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/20.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/21.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part4/22.png)
