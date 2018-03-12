# Azure Virtual Machine and File Share for Deep Learning Development
![alt text](https://github.com/amarisch/deep-learning-workflow-with-web/blob/master/images/azure-deep-learning-project-framework.jpg)

This repo contains a simple workflow for deep learning development/deployment on Azure using python SDK. You will be able to easily set up a deep learning development environment (CPU-only or GPU-enabled) with access to Azure file where you can preload and share datasets.

**On this page**

- [Run this sample](#run)
- [What does run.py do?](#example)
- [How is the code laid out?](#code)
- [Notes and troubleshooting](#troubleshooting)
- [More Ideas and Functionality](#ideas)

<a id="run"></a>

## Run this sample

1.  If you don't already have them, install the following:

    - [Python](https://www.python.org/downloads/)
    - [Anaconda](#anaconda)
    
1.  Install python requirements
    ```
    pip install -r requirements.txt
    ```
1. To run from commandline
    ```
    python run.py <Azure credentials filename>
    ```
1. To run with a web browser
    ```
    python hello.py <Azure credentials filename>
    ```


<a id="example"></a>
## What does run.py do?


<a id="code"></a>
## Code layout


<a id="troubleshooting"></a>
## Notes and Troubleshooting

Customized Azure VM has:
- Anaconda/Python3
- Tensorflow-CPU

Cloud Config scripting
https://www.digitalocean.com/community/tutorials/an-introduction-to-cloud-config-scripting

Mounting new data disk to VM
https://docs.microsoft.com/en-us/azure/virtual-machines/linux/add-disk#connect-to-the-linux-vm-to-mount-the-new-disk

Pre-loaded Datasets
- Kaggle Titanic
- Kaggle Zillow
- Kaggle Tensorflow Speech Challenge

Kaggle data download
https://github.com/floydwch/kaggle-cli


<a id="ideas"></a>
## More Ideas and Functionality
Things to look further into:
1. GPU-enabled VM
https://azure.microsoft.com/en-us/pricing/details/virtual-machines/series/
2. Docker for Azure
https://azuremarketplace.microsoft.com/en-us/marketplace/apps/docker.dockerdatacenter?tab=Overview

<a id="anaconda"></a>
## Anaconda Installation
```
curl -O https://repo.continuum.io/archive/Anaconda3-5.0.1-Linux-x86_64.sh
chmod +x Anaconda3-5.0.1-Linux-x86_64.sh
bash Anaconda3-5.0.1-Linux-x86_64.sh
```
