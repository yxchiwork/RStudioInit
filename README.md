# RStudioInit
## Installation 
This project provides the instruction on setting up the Rstudio with R and JRE8 for the first time on a Windows Machine. 
There are 2 steps you need to follow: 
### 1. Install Chocolately (Choco), Choco is a package manangement tool like homebrew on Mac, or PIP in Python, you can install/uninstall software/packages using this tool. The scripts provided by Choco will make sure the installation is smooth and the environment variable is updated correctly. 
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
### 2. Install JRE and R studio using the commands below:
```
choco install jre8 --version 8.0.333 -y
choco install r.studio --version 2022.02.3 -y
```
## Screenshots: 

![step1](https://user-images.githubusercontent.com/55746132/172734602-50db8070-2bbb-4862-8b7d-b58b9363d186.png)
![step2-install-choco](https://user-images.githubusercontent.com/55746132/172734608-9615a4e6-10be-4fa2-aae3-ea613cae7924.png)
![step3-install-jre8](https://user-images.githubusercontent.com/55746132/172734615-4a1b0214-0a05-43fb-8f56-bb3263ad7676.png)
![step4-install-r-rstudio](https://user-images.githubusercontent.com/55746132/172734621-1e74cc36-5dad-4f23-bffd-43eba46a93ea.png)
