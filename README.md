# Conv3ni3nt
[![Kali](https://img.shields.io/badge/-Kali-informational)](https://www.kali.org/) [![Python3](https://img.shields.io/badge/-Python3-yellow)](https://www.python.org/)
"Conv3ni3nt was made for the purpose of simpliying the scanning process of a pentration test. All of a pentester's favorite scans can be initiated from the easy-to-use interface while also providing available output to each file containing the data generated by the scans. There are a number of tools to use with Conv3ni3nt and more tools can be added simply by appending the desired tool to the VALID_TOOLS list defined within the conv3ni3nt.py module. **Note**: appending tools that prompt for user input during scans will cause the problem to run indefinitely. Avoid these kinds of tools."
### Simplifiying the enumeration phase
![Interface](images/conv3ni3nt.png)
## Installation
```
cd /opt

git clone https://github.com/rodriguez10011999/Conv3ni3nt.git

pip3 install -r requirements.txt
```
## Create a symbolic link in /bin directory for more "_conv3ni3nce_"
```
cd /bin

ln -s /opt/Conv3ni3nt/conv3ni3nt.py conv
```
