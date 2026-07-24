# Overview
- This section features the promotion of a Windows server 2022 into a domain controller, and create a domain called **company.com**

# Promoting the server
- The first step in creating a domain is the installation of Active Directory Domain Services onto the Windows server
- I began with the addition of roles and features, and choose the role-based installation.
<img width="787" height="565" alt="image" src="https://github.com/user-attachments/assets/e71ccef1-3df5-4f69-ab0a-cf75b9219af0" />

- I installed the features of Active Directory Domain Services, and DNS server to make the DC the DNS server for the domain.
<img width="788" height="568" alt="image" src="https://github.com/user-attachments/assets/2cf1c852-661e-4514-9a16-35cab8df89ed" />

- The installation of the features was complete, and now the next step is to create the forest.
<img width="790" height="563" alt="image" src="https://github.com/user-attachments/assets/2c944346-ec1a-49f1-893a-79245e60b15b" />


- I added the new forest.
<img width="761" height="565" alt="image" src="https://github.com/user-attachments/assets/8b896e80-6b7e-4563-aba9-922790904df1" />

- After the successful check of prequisites, the forest was created, and the Windows server was promoted to Domain Controller.
<img width="758" height="562" alt="image" src="https://github.com/user-attachments/assets/fce3b500-072d-4188-a380-54b6578af723" />

