Owncloud is an open source file server. It makes file storage and sharing across multiple devices very easy.
This manual provides detailed steps to install and configure Owncloud server and client application.

## Minimum System Requirements
Windows supports earlier Owncloud versions under 8.9.x. You must install Xampp server on your Windows machine to install Owncloud server.
+ Operating system - Windows 7 and above
+ Xampp server - 3.2.x and above
+ PHP version - 5.6.x and above
+ Browser - Chrome 66 and above


## Install Owncloud Server
1. Download Zip from official [Owncloud website](https://owncloud.com/download-server/#instructions-server). 
2. Extract Zip file and copy all the content from **Owncloud** folder.
3. Open Xampp folder where you have configured it and search htdocs folder in it. 
4. Copy Owncloud files in htdocs folder. 
5. Open Xampp and start the **Apache** and **Mysql** services.
![xampp](https://user-images.githubusercontent.com/76067033/102471258-03923280-407b-11eb-8926-9441a486e1ef.png)
6. To enable the user to connect to the Owncloud server, open browser and enter server address link (for example, host name:port number). 
![server login_1](https://user-images.githubusercontent.com/76067033/102473519-8c11d280-407d-11eb-822a-8dcf2cd711f5.png)
7. Enter **Username** and **Password**. Cick **Finish setup**.

## Getting Started

Once the installation of owncloud is complete, you can start uploading files to the server.
![Server dashboard-01](https://user-images.githubusercontent.com/76067033/102485551-caaf8900-408d-11eb-810c-6dd59d6677f4.png)

## Add User Account
1. To add user account, in the Owncloud server dashboard, click **Personal settings** drop-down in the right corner and select **Users**.
2. In the **Users** menu, enter **Username**, **Password**. Add existing **User group** or create new group. Click **Create**.
![create users-01](https://user-images.githubusercontent.com/76067033/102487734-0b5cd180-4091-11eb-8b46-a28c3d9e5a47.png)

## Install Owncloud Client
1. Download Owncloud [desktop client installer](https://owncloud.com/features/desktop-app/) from Owncloud official website.
2. Install desktop client application using setup wizard.

## Connect Ownclient Client to Server
1. In the Owncloud client dashboard, Click **Add Account**.
![Client dashboard](https://user-images.githubusercontent.com/76067033/102490943-888a4580-4095-11eb-8373-860382ebe327.png)
2. Enter **Server Address** (for example, host name:Port numer). Click **Next**.
![Enter server address](https://user-images.githubusercontent.com/76067033/102491918-e8cdb700-4096-11eb-985b-4e0b5d27dccb.png)
3. Enter **Username** and **Password**. Click **Next.**
4. Select your synchronization options. Click **Connect**. You can see the server is connected to client.




















































