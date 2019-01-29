# Python for Data Center
Research Python for monitor system

## vSphere Automation System
### Ubuntu

```
git clone https://github.com/vmware/vsphere-automation-sdk-python.git
cd vsphere-automation-sdk-python
pip install --upgrade --force-reinstall -r requirements.txt --extra-index-url file:\\\C:\Users\strefethen\github\vsphere-automation-sdk-python\lib
```
### Create a new virtual machine in Vsphere by Pysphere and the VMWare API
```
sudo yum install python-pip
sudo pip install pysphere
```
+ vm_include.py: Library in manipulate to Vsphere 
+ host-info.py: Connect to a Vsphere 
  ```
  chmod +x host-info.py
  ./host-info.py
  ```
+ create-vm.py: Create a new VM
  
  ```
  chmod +x create-vm.py
  ./create-vm.py
  ```
### References 
+ [vSphere Automation SDK for REST](https://blogs.vmware.com/code/2017/02/02/getting-started-vsphere-automation-sdk-rest/)
+ [vSphere Automation SDK for REST Part 2](https://blogs.vmware.com/code/2017/02/15/getting-started-vsphere-automation-sdk-rest-p2/)
+ [vSphere Automation SDK for Python](https://blogs.vmware.com/code/2017/04/11/get-started-vsphere-automation-sdk-for-python/)
+ [vSphere Automation SDK for Ruby](https://blogs.vmware.com/code/2017/08/17/get-started-vsphere-automation-sdk-for-ruby/)
+ [vSphere Automation SDK for .NET](https://blogs.vmware.com/code/2018/03/05/getting-started-vsphere-automation-sdk-net/)
