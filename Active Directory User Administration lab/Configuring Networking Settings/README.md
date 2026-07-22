# Overview
- This section will involve the creation of a custome network using VMware's virtual network editor.
  - I will also assign static IP addresses to each of the virtual machines, and point them to the Domain Controller's IP address for DNS: 192.168.10.10
 
# Creating the VNET
- Using VMware's Virtual Network Editor, I can create a custom NIC, and subnet.
  - For this lab I will be using a 192.168.10.0/24 Subnet
  - I also configured DHCP settings
<img width="695" height="668" alt="image" src="https://github.com/user-attachments/assets/fdedc25e-dd7f-4769-946d-4b0c4b309b11" />


- Now that the VNET is created, I can now begin with the static assignment of IP addresses.

# Assigning IP addresses
- To begin, I will assign the machines with the following IP addresses:
  - 192.168.10.10 for the Domain Controller
  - 192.168.10.20 for the osTicket server
  - 192.168.10.30 for the Windows client
 
- I added the custom NIC to the Domain Controller
<img width="891" height="922" alt="image" src="https://github.com/user-attachments/assets/7b04beba-9cd9-4f20-b14a-41fa56d3358f" />

- To change the IP address on the server, I modified the adapter settings on the machine
<img width="1028" height="775" alt="image" src="https://github.com/user-attachments/assets/5bc1957f-b04f-4b58-b065-836ab83b0922" />

- Now the DC has a static IP address.
  - Using **ipconfig**, I verified the changes were made.

<img width="958" height="278" alt="image" src="https://github.com/user-attachments/assets/66bd88fa-6583-4b5e-9944-aab33669f2b5" />




- I changed the IP address of the Windows 11 client.
<img width="817" height="587" alt="image" src="https://github.com/user-attachments/assets/dc72ffe0-b6f2-4d2c-94d7-d8d400411199" />

- I verified using **ipconfig**
<img width="1028" height="332" alt="image" src="https://github.com/user-attachments/assets/213323d6-12e1-4b23-8304-99b055b57f0f" />

- Next, I began to change the ip address of the osTicket server.
- 
