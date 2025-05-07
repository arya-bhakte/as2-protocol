A demonstration of the AS2 protocol concept using two Node.js servers communicating with each other.

Server 1 (port 8448): Provides sample JSON data

Server 2 (port 8449): Requests data from Server 1 and processes it

Running the Application

Start Server 1: node server1.js
![image](https://github.com/user-attachments/assets/687ba736-469b-4ed3-830a-66394301d7fa)

In a new terminal, start Server 2: node server2.js
![image](https://github.com/user-attachments/assets/1a0ad7c6-c831-4239-bfdb-b267b9c69fcd)

In a third terminal, trigger the communication: curl http://localhost:8449/start
![image](https://github.com/user-attachments/assets/a561c3bd-7c40-49d1-b479-5558c4921482)

Check the Server 2 terminal to see the received data logs:
![image](https://github.com/user-attachments/assets/2e3d2cc3-0cc2-485d-a707-fd3003070c5a)
