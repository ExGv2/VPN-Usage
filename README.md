## VPN - Demonstrating changes in IP address using a Virtual Machine & Virtual Private Network (AZURE) - (PROTON)

<p align="center">
<img src="https://github.com/user-attachments/assets/9757a3b3-2a84-4277-a920-b419589441b0" alt="osTicket logo"/>
</p

<h1>This simple tutorial will outline the method of creating a vitual machine and how to change its local IP address using a VPN.</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop Connection
- Laptop/desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)

- <h2>Tutorial on VPN and Azure setup</h2>

![image](https://github.com/user-attachments/assets/f90c8351-3aee-4728-bfb2-1217af2c0c2c)

- Step 1: Browse to https://whatismyipaddress.com/ (Take note of your own IP addresses PERSONAL COMPUTER)

![image](https://github.com/user-attachments/assets/7a1d5e54-02b9-436c-9187-6a3b0f0be501)

- Step 2: Create a free account at https://portal.azure.com/

![image](https://github.com/user-attachments/assets/7b10c314-8fe1-43e3-9f9b-703151e0a226)

- Step 3: Once you have created your account, go to the home page and select "Virtual Machines" under "Azure services"

![image](https://github.com/user-attachments/assets/286e357f-d146-476d-a2c3-208d1c6fe3a2)

- Step 4: Select "+ Create", then select "Azure virtual machine"

![image](https://github.com/user-attachments/assets/38cd5c19-ae29-4297-a7b5-969c87f3007a)

- Step 5: Create new resource group (name it whatever you like)

![image](https://github.com/user-attachments/assets/ef450f2e-9c5b-4ed8-869e-07c78bc1b883)

- Step 6: Name your vitual machine to whatever you like, for "region", select any, for a better representation select a region OUTSIDE your country

![image](https://github.com/user-attachments/assets/6aa292fd-3b87-4c94-979a-49ae4c8fc13d)

- Step 7: Select "Zone 1" (May vary based on location), select Windows 10 Pro (22H2), select "size" 2 vcpus (no more than 2 is required for this tutorial)

![image](https://github.com/user-attachments/assets/7f231840-7014-46eb-9f30-2bad36515f41)

- Step 8: Create a username and password (Take note of it before proceeding), next check "Licensing" box, then select "Review + create" (you can skip all other settings).

![image](https://github.com/user-attachments/assets/0c2c40ec-a3a9-4e24-9c91-4d4c9dc99a19)

- Step 9: If everything went accordingly, you should be able to "create" your virual machine (be patient, it will take a moment to create).

![image](https://github.com/user-attachments/assets/24002bc0-8793-444d-bfcc-957cf6db1b6c)

- Step 10: Login to your virtual machine by opening "Remote Desktop Connection", then copy the public IP address provided to you to login, your credentials will be the one you created before creating the virtual machine.

![image](https://github.com/user-attachments/assets/d8d6f3bd-111f-4983-abc4-541864cf72e4)

- Step 11: Once logged in the VM, open MS EDGE, then type https://whatismyipaddress.com/ within the VM (Take note of it before proceeding).

![image](https://github.com/user-attachments/assets/28485ac9-e4e0-4822-9926-4cd330382f4e)

- Step 12: In this tutorial we will be using PROTON VPN. Sign up for a free account at this URL - https://account.protonvpn.com/signup?plan=free&language=en

![image](https://github.com/user-attachments/assets/5103c03e-9a15-4840-89b0-1ea73ac5e117)

- Step 13: Once you've signed up for your free account, you will login with your credentials IN the virtual machine, then download the PROTON VPN Software (For this tutorial we'll use Windows).

![image](https://github.com/user-attachments/assets/2270bb48-f33c-49d9-a92e-f962ff5ff705)

- Step 14: Once logged in to PROTON VPN select "Quick Connect" (The FREE version only allows us to auto-assign a server by PROTON).

![image](https://github.com/user-attachments/assets/bf0e2097-62d5-4194-97b0-11d488b3e615)

- Step 15: Once you've connected, you should see a connection established to a server (example above)

![image](https://github.com/user-attachments/assets/baf1378b-bbf9-40b7-9c01-4bd048d3e594)

- Step 16: Go back to https://whatismyipaddress.com/ - If done correctly you should now see a different IP address from the previous one you had.

This should give an overview of how VPNs work and can work within a virtual machine as well.









