# CEH_Practical_Commands

* Check Message signing enabled/desabled:
    ```console
         nmaap --script=smb2-security-mode
    ```  
* how to check and kill running ports(session):
    ```console
         sudo lsof -i :<port_no>
    ```
    ```console
         sudo kill -9 <PID> 
    ```
* check active session in metasploit console:
    ```console
         sessions -i*
    ```
* Bruteforce or password srying using CME(RDP, SMB, MSSQL):
    ```console
         cme rdp <subnet> -u users.txt -p passwords.txt
    ```
* wireshark filters:
    ```console
         http.request.method == POST --> for finding the credentials
         mqtt --> find IOT/OT related
    ```
* bruteforce:
  - SSH :~
     ```console
          hydra -L                                     


