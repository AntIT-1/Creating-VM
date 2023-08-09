![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/a66b6e77-0c17-4f6d-8fea-81304c3beadc)



<h1>How to create a Virtual Machine in Azure </h1>
In this tutorial I will demonstrate how to create a Virtual Machine in Azure cloud.<br />


<h2>Deployment and Configuration Steps</h2>

- First you must sign up to Microsoft Azure and set up a subscription. Once your setup with a subscription you will able to create the Virtual machine.
  
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/e02f85cd-619b-482a-8a7c-2e444558b869)
 
- Second step is to create a resource group. A resource group will store and seperate VMs and other resources you want to add. Click create resource group. We can name it "RG-1". Once you named it click review and create. After it validates, the resource group will be created. 
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/4ca0f03b-39f9-4aa3-b604-84a465bc7934)

  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/75c06045-b498-48d5-9486-8cca76b83a5f)

- Now we create the virtual machine. You can search virtual machine on the top search bar. Select create and click on Azure virtual machine. We will name this VM "VM1". Ensure that you have selected the "RG-1" resource group we created in the previous step. For the operating system we will go with Windows 10. Select 2 cpu's with 16Gb of ram at least. Now, for the username and password you can put anthing you want. We will enter "labuser" for username and "Password1" for the password. In Networking, you can see that vnet (virtual network) was created for this enviroment. Click review and create.  
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/19863f09-e44b-4d7d-bc23-38514010ff55)
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/7f2f5a67-3841-4222-85fb-9793539a50e9)
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/55b7db94-07ed-469c-aed8-03579125aeab)
  


  

- Now that the VM has been created, it's time to remote log in to it. In the list of VMs, click on VM1. 
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/8f8214ec-43d2-403d-aa44-2e58becb890d)
- Find the public IP address. Copy the IP address
  
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/16fe094c-ea18-4542-b223-9c2e5907ef3d)
- In your local computer, search for the remote desktop connection and paste the VM's public IP address. 
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/b9b2b8c6-79c7-45d1-897c-1fe933948a2b)
- Enter the username and password that was entered when setting up the VM in the Azure Portal.
  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/2e2033d2-db24-4cbd-a65a-61abe3f82775)
  
- Setup of the Azure Virtual Machine is now completed.

  ![image](https://github.com/AntIT-1/Creating-VM/assets/141161539/8a7fc551-86b5-4cbf-92ec-30063b48cacd)





