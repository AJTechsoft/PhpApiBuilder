**PHP API Builder - CLI User Manual**

**Introduction:**

PHP API Builder - CLI is a command-line tool designed to facilitate the creation of API files for CRUD operations on a specified database table. By following a few simple steps, users can quickly generate PHP files that handle Create, Read, Update, and Delete operations for a chosen table.

**Requirements:**

- PHP installed on your system.
- Access to the database you want to generate API files for.

**Usage:**

1. **Run the CLI Tool:**
   - Open *PhpApiBuilder.exe* CLI tool where it is located.

2. **Input Hostname:**
   - When prompted, enter the hostname of your database server. If it's 'localhost', you can press Enter to proceed with the default value.

3. **Input Database Name:**
   - Enter the name of the database you want to generate API files for.

4. **Input Username:**
   - Provide the username to access the specified database.

5. **Input Password:**
   - If your database requires a password, enter it when prompted. If there's no password, you can press Enter to proceed with an empty password.

6. **Enter PHP File Name:**
   - Specify the desired name for the PHP file that will be generated. Do not include the ".php" extension.

7. **Enter Table Name:**
   - Input the name of the table for which you want to generate CRUD operations API.

8. **Review Output:**
   - Once all the necessary information is provided, the CLI tool will generate the PHP file containing CRUD operations for the specified table.
   - If any errors occur during the process (e.g., invalid credentials, table not found), the CLI will display an error message and prompt you to restart the process from the beginning.

9. **Accessing Generated Files:**
   - The generated PHP file will be available in the same directory where the CLI tool is located.

**Example:**

Suppose you want to generate API files for a database named "my_database" with the table "users". Here's how you would use the PHP API Builder - CLI tool:

```
Enter hostname (default: localhost): localhost
Enter database name: my_database
Enter username: my_username
Enter password (default: empty):
Enter PHP file name (without .php extension): users_api
Enter table name: users
```

After providing the necessary information, the tool will generate the "users_api.php" file in the tool's directory.

**Note:**
- Make sure to review the generated PHP file to ensure it meets your requirements and security standards before using it in your project.
- It's recommended to back up your database before performing any CRUD operations using the generated API files.
- For any assistance or issues with the PHP API Builder - CLI tool, refer to the documentation or contact support.

This manual provides a comprehensive guide for using the PHP API Builder - CLI tool to efficiently generate API files for CRUD operations on your database tables.
