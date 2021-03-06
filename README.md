Owncloud is an open source file hosting platform. It makes file storage and sharing across multiple devices very easy.
This manual provides detailed steps to install and configure Owncloud server and client applications.

## Minimum System Requirements
Windows supports earlier Owncloud versions under 8.9.x. You must install Xampp server on your Windows machine to install Owncloud server.
+ Operating system - Windows 7 and above
+ Xampp server - 3.2.x and above
+ PHP version - 5.6.x and above
+ Browser - Chrome 66 and above


## Install Owncloud Server
1. Download Zip from official [Owncloud website](https://owncloud.com/download-server/#instructions-server). 
2. Extract Zip file and copy all the content from **owncloud** folder.
3. Open xampp folder installed on your machine (usually C drive) and locate **htdocs** folder. 
![copy files to htdocs](https://user-images.githubusercontent.com/76067033/102495253-e1f57300-409b-11eb-9ab1-a8a489349987.png)
4. Paste Owncloud files copied in Step 2 into htdocs folder. 
5. Open Xampp control panel and start the **Apache** and **Mysql** services.
![xampp](https://user-images.githubusercontent.com/76067033/102471258-03923280-407b-11eb-8926-9441a486e1ef.png)
6. To connect to the Owncloud server, open the browser and enter server address link (for example, http://hostname:portnumber). 
![server login_1](https://user-images.githubusercontent.com/76067033/102473519-8c11d280-407d-11eb-822a-8dcf2cd711f5.png)
7. Enter **Username** and **Password** to create a user on Owncloud server. Click **Finish setup**.

## Getting Started

Once the installation of Owncloud server is completed, you may start creating or uploading files and folders to the server.
![Server dashboard-01](https://user-images.githubusercontent.com/76067033/102485551-caaf8900-408d-11eb-810c-6dd59d6677f4.png)

## Add User Account
1. To add a new user account in the Owncloud server dashboard, click on **Personal settings** drop-down in the top right corner and select **Users**.
2. On the **Users** dashboard, enter **Username** and **Password**. Add existing **User group** or create a new **User group**. Click **Create**.
![create users-01](https://user-images.githubusercontent.com/76067033/102487734-0b5cd180-4091-11eb-8b46-a28c3d9e5a47.png)
3. This will add a new user to your Owncloud server.

## Install Owncloud Client
1. Download Owncloud [desktop client installer](https://owncloud.com/desktop-app/) from Owncloud's official website.
2. Install desktop client application using setup wizard. Choose default options on each step and Click **Next** to proceed.
3. Click **Install** to initiate the installation.
4. Click **Finish** to complete the installation.
![install client](https://user-images.githubusercontent.com/76067033/102496637-aa87c600-409d-11eb-91ce-07619a736f8e.png)

### Connect Ownclient Client to Server
1. In the Owncloud client dashboard, Click **Add Account**.
![Client dashboard](https://user-images.githubusercontent.com/76067033/102490943-888a4580-4095-11eb-8373-860382ebe327.png)
2. Enter **Server Address** (for example, http://hostname:portnumber). Click **Next**.
![Enter server address](https://user-images.githubusercontent.com/76067033/102491918-e8cdb700-4096-11eb-985b-4e0b5d27dccb.png)
3. Enter **Username** and **Password** of the user created on Owncloud Server. Click **Next.**
4. Select your synchronization options as required or proceed with the recommended options. Click **Connect** to initiate connection to the Server. 
![Client config](https://user-images.githubusercontent.com/76067033/102492330-8b863580-4097-11eb-85a7-058d1d2a8da2.png)

Your Owncloud client is now connected to the Owncloud server.
![server connection](https://user-images.githubusercontent.com/76067033/102497435-a6a87380-409e-11eb-9517-857254d2a036.png)
## References
For more information, please visit Owncloud [Help Desk](https://central.owncloud.org/).


