# Password Complexity Checker

## 📖 Project Overview

The **Password Complexity Checker** project is a Python-based application designed to evaluate the strength and complexity of a user-provided password. The program analyzes the password based on common security requirements such as length, uppercase letters, lowercase letters, numbers, and special characters.

The application checks the password against multiple complexity criteria and provides feedback about whether the password meets the required security conditions. It also helps identify missing character types so that users can understand how to improve their password strength.

This project demonstrates the practical use of **Python string handling, conditional statements, character validation, and basic cybersecurity concepts**. It provides a simple introduction to password security and the importance of creating strong and complex passwords.

## Step 1 — Create the Project Directory

### Objective

Create a dedicated directory for the **Password Complexity Checker** project and navigate into it.

### 1. Open Kali Linux

Start the **Kali Linux virtual machine** in VirtualBox and log in to the system.

![Kali Linux Running in VirtualBox](images/01-kali-linux-virtualbox.png)

*Screenshot 1: Kali Linux running in VirtualBox.*

### 2. Open the Kali Linux Terminal

Run the following command:

```bash
mkdir Password_Complexity_Checker
```

This creates a new project directory in the current home directory.

![New Project Folder Created](images/02-project-folder-created.png)

*Screenshot 2: Showing the new folder created.*

### 3. Navigate into the Project Directory

Run:

```bash
cd Password_Complexity_Checker
ls
```

The `cd` command navigates into the newly created project directory, while the `ls` command displays its contents.

### 4. Verify the Current Directory

Run:

```bash
pwd
```

You should see a path similar to:

```text
/home/kali/Mini_Projects/Password_Complexity_Checker
```

The `pwd` command confirms the current working directory.

![Current Project Directory](images/03-current-directory.png)

*Screenshot 3: Showing the current directory.*

## Step 2 — Create the Python File

### Objective

Create the Python source file that will contain the **Password Complexity Checker** program.

### 1. Navigate to the Project Directory

Make sure you are inside the **Password Complexity Checker** project directory.

Run:

```bash
cd Password_Complexity_Checker
```

### 2. Create the Python File

Run:

```bash
touch password_checker.py
```

This creates an empty Python file named `password_checker.py`.

### 3. Verify the Python File

Run:

```bash
ls
```

You should see:

```text
password_checker.py
```

![Python File Created](images/04-password-checker-file-created.png)

*Screenshot 4: Terminal showing the creation of `password_checker.py` and the `ls` command displaying the newly created Python file.*
