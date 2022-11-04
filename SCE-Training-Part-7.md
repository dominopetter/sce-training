# This is PART 7 (Last and final) of the Domino SCE training  
### We assume you have done Part 1, 2, 3, 4, 5, and 6
### Good Luck!
##
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/intro/7.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/1.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/2.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/3.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/4.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/5.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/6.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/7.png)

![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/6.1.png)



```Python
# IMPORT THE DOMINO LIBRARY
from domino import Domino

# INSTANTIATE PROJECT - TOWARDS WHAT PROJECT ARE WE EXECUTING
# Here will will use the QC project. My PATH looks like "petter-not-admin/Domino-Training-101-QC" which you can see in the URL.
domino = Domino("COPY-AND-PASTE-YOUR-PATH-HERE")

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
ENVIRONMENT = "6358f34ccd164750e6b8f0fd"

# TO SEE ALL OPTIONS EXECUTE Domino.job_start? IN A CELL
```
```python
# I have added sleep so we can go to the Projects Job Section and see it appear. Once you execute this navigate to the QC project and Jobs.
import time
time.sleep(30)
domino.job_start(MY_SCRIPT, hardware_tier_id=HARDWARE, environment_id=ENVIRONMENT)
```
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/8.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/9.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/10.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/11.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/12.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/13.png)
 
![Picture 1](https://github.com/dominopetter/sce-training/blob/main/SCE-Training-Part7/14.png)
