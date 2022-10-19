# This is PART 3 of the Domino SCE training  
### We assume you have done Part 1 and 2. 
### Good Luck!
##
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/1.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/2.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/3.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/4.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/5.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/6.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part3/7.png)

```python
# IMPORT THE DOMINO LIBRARY
from domino import Domino

# INSTANTIATE PROJECT - TOWARDS WHAT PROJECT ARE WE EXECUTING
# Here will will use the QC project. My PATH looks like "petter-not-admin/Domino-Training-101-QC"
domino = Domino("petter-not-admin/Domino-Training-101-QC")

#################################
# CONFIGURE EXECUTION VARIABLES #
#################################

# command
# We are going to execute our QC SAS code. Mine is SDTMQC.sas
MY_SCRIPT = "SDTMQC.sas"

# hardware_tier_id
# Here you can specify how much compute you need. By default it will use your Projects default
HARDWARE = "small-k8s"

# environment_id
# Here we specify the ID of the Environment. By default it will use the default of the project.
ENVIRONMENT = "6345643212c08638181a14c8"

# TO SEE ALL OPTIONS EXECUTE Domino.job_start? IN A CELL
```
```
# I have added sleep so we can go to the Projects Job Section and see it appear. Once you execute this navigate to the QC project and Jobs.
import time
time.sleep(30)
domino.job_start(MY_SCRIPT, hardware_tier_id=HARDWARE, environment_id=ENVIRONMENT)
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
