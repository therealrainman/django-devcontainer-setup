# Remote development on AWS

### 1. Launch instance, with desired settings
![](./screenshots/01_instance_launch_1.png)

### 2. Allow all SSH, HTTP, HTTPS traffic; launch instance
![](./screenshots/02_instance_launch_2.png)

### 3. Open the security group attached to the instance
![](./screenshots/03_security_group_1.png)

### 4. Click "Edit inbound rules"
![](./screenshots/04_security_group_2.png)

### 5. Add rule to open port 8000 (or whichever port is used) to all traffic
![](./screenshots/05_security_group_3.png)

### 6. Open VSCode's Remote Window and select "Connect to Host"
![](./screenshots/06_vscode_remotehost_1.png)

### 7. Select "Configure SSH Hosts"
![](./screenshots/07_vscode_remotehost_2.png)

### 8. Select the user ssh config file
![](./screenshots/08_vscode_remotehost_3.png)

### 9. Add details for connecting to the EC2 instance as such
![](./screenshots/09_vscode_remotehost_4.png)

### 10. Verify VSCode connects to the EC2 instance successfully
![](./screenshots/10_vscode_connected.png)

### 11. Clone the project repo; install needed packages
![](./screenshots/11_git_setup.png)

### 12. Start server
![](./screenshots/12_start_server.png)

### 13. Browser is able to connect both with localhost or EC2 instance's public IP address
![](./screenshots/13_browser_connect_1.png)
![](./screenshots/14_browser_connect_2.png)

### 14. Open the project folder in VSCode and develop the same as on a local machine
![](./screenshots/15_vscode_folder_browser.png)
