# Credentials Documentation

## AWS Instance Access
To access the server via SSH, you will need the SSH URL, Username, and either a password or an SSH key.

### SSH Credentials

- **SSH URL:** `ec2-52-52-61-214.us-west-1.compute.amazonaws.com` 
- **SSH Username:** `ubuntu` 
- **SSH Password/Key:** You will need the private key file that corresponds to the public key installed on the server. Ensure the private key file permissions are secure and located in the same directory from which you are doing ssh.

### Connecting via SSH

1. **Using SSH Key Authentication:**
   ```bash
   
   ssh -i /path/to/your/private_key ubuntu@ec2-52-52-61-214.us-west-1.compute.amazonaws.com
   ```

***
## Database Access

Access to the database is crucial for managing and interacting with the application's data. The database URL provides the necessary information to connect to the database.

### Database Info

- DB_HOST/URL = `52.52.61.214`
- DB_USER = `sulavjunghamal`
- DB_PASSWORD = `gidJic-noxzah-xapwe8`
- DB_NAME = `todotoday`

### Connecting to the Database
Below is a general guideline for connecting to a MySQL database:
1. **Using a Database Management Tool:**
   - Open your preferred database management tool (e.g., DBeaver, or Workbench).
   - Create a new database connection and enter your database URL, username, and password.
   - Connect to the database to manage your tables and data.

