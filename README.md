## osTicket - Prerequisites and Installation

### Prerequisites

Before you install osTicket, make sure your environment meets the following requirements:

1. **Web Server:** Apache or IIS
2. **PHP:** Version 8.0 or higher
3. **Database:** MySQL 5.5 (or later) or MariaDB
4. **PHP Extensions:** Ensure the following extensions are enabled:
   - mysqli
   - gd
   - gettext
   - mbstring
   - xml
   - json
   - fileinfo
5. **Access Permissions:** Proper read, write, and execute permissions on osTicket directories

---

### Installation Steps

1. **Download osTicket:**

   - Visit the official osTicket website: https://osticket.com/download/ and download the latest stable release.
![image](https://github.com/user-attachments/assets/f4261365-1d0c-44ea-8ba7-07fadd147c5b)


2. **Upload Files:**

   - Extract the downloaded osTicket package and upload its contents to your web server’s root directory or a subdirectory of your choice.
   ![image](https://github.com/user-attachments/assets/5fd42889-15eb-4ed4-ad97-28e9504a472c)




3. **Set Permissions:**

   - Ensure the following directories are writable:
     - `include/ost-config.php`
     - `attachments/`
     - `logs/`
       
![image](https://github.com/user-attachments/assets/4301a47b-d1de-4a61-b348-7ce7768a2265)

4. **Create Database:**

   - Use your database management tool (like phpMyAdmin) to create a new database for osTicket.

5. **Run Installer:**
 - Navigate to the URL where you uploaded osTicket (e.g., `http://yourdomain.com/support/`) and follow the on-screen installation wizard.
   
![image](https://github.com/user-attachments/assets/59292973-16f2-4e4c-9e1b-9fde559a54c2)

6. **Configure Settings:**

   - Enter the required information:
     - Database details (host, name, username, password)
     - Admin user account details
       
![image](https://github.com/user-attachments/assets/a29eba66-1de4-43bc-a355-1181f35c66e1)


7. **Complete Installation:**

   - Once the installation finishes, remove or rename the `setup/` directory for security purposes.

8. **Access osTicket:**

   - Admin Panel: `http://yourdomain.com/support/scp/`
   - Client Portal: `http://yourdomain.com/support/`

Congratulations! osTicket is now installed and ready to use.

