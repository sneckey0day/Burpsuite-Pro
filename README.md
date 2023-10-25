# Burp Suite Pro Scripts for Windows and Linux

![Burp Suite Logo](https://portswigger.net/cms/images/12/c8/c338-article-burp-suite-user-community-tips-and-tricks_blog-article.jpg)

## Introduction

📦 This repository contains a collection of scripts and tools designed to enhance and extend the functionality of Burp Suite Pro on both Windows and Linux platforms. These scripts are intended to streamline various tasks, automate repetitive actions, and provide additional features for penetration testers and security professionals.

## Installation For Your OS

🖥️ **Install In Windows** [🔗](#Installation-Guide-for-Burp-Suite-Pro-on-Windows)

🐧 **Install In Linux** [🔗](#Installation-Guide-for-Burp-Suite-Pro-on-Linux)

## Features

🚀 List the key features of your Burp Suite Pro scripts here, such as:

- Automated scanning and vulnerability detection.
- Customizable request/response manipulation.
- Integration with popular security tools.
- Reporting and export capabilities.
- And more!

  
### Prerequisites

🧠 Ensure you have the following prerequisites installed on your system:

- Brain
- Internet :)

## Installation

## Installation-Guide-for-Burp-Suite-Pro-on-Windows

🖥️ This guide will walk you through the installation of Burp Suite Pro on a Windows system using the provided `Windows_setup.ps1` script. The script automates the installation process, including setting up Java JDK and activating Burp Suite Pro.

1. **Download the Windows_setup.ps1 Script**:

   - Download the `Windows_setup.ps1` script from the provided Zip file.

2. **Open the Download Location**:

   - Navigate to the folder where you downloaded the script.

3. **Open PowerShell**:

   - Right-click in the folder where you downloaded the script.
   - Choose "Open PowerShell" from the context menu. This will open a PowerShell terminal in the current directory.

4. **Set Execution Policy**:

   - In the PowerShell terminal, type the following command to set the execution policy for the current session:

     ```powershell
     Set-ExecutionPolicy -ExecutionPolicy bypass -Scope Process
     ```

   This command allows you to run the script.

5. **Run the Windows_setup.ps1 Script**:

   - Now, execute the `Windows_setup.ps1` script by running the following command:

     ```powershell
     .\Windows_setup.ps1
     ```

   This script will perform the following actions:

   - Install Java JDK (if not already installed).
   - Launch the keygen for Burp Suite Pro.
   - Guide you to copy the request and paste it into Burp Suite Pro.
   - In Burp Suite Pro, click on "Manual installation."
   - Copy the response from the keygen and paste it into Burp Suite Pro to activate it.

6. **Launch Burp Suite Pro**:

   - After activating Burp Suite Pro, the script will proceed to launch Burp Suite Pro.

Now, you have successfully installed and activated Burp Suite Pro on your Windows system. You can start using it for your security assessments and penetration testing tasks.


## Installation-Guide-for-Burp-Suite-Pro-on-Linux

🐧 This guide will walk you through the installation of Burp Suite Pro on a Linux system using the provided `Linux.sh` script. The script automates the installation process and includes setting up Java JDK and activating Burp Suite Pro.

### Prerequisites

Before you begin, ensure you have the following prerequisites in place:

- A Linux operating system (e.g., Ubuntu, CentOS, etc.)
- Internet connectivity to download necessary files
- Basic knowledge of the Linux command line

### Installation Steps

1. **Clone the Repository**:

   - Open your terminal and navigate to the directory where you want to clone the repository.
   - Run the following command to clone the repository:

     ```shell
     git clone https://github.com/sneckey0day/Burpsuite-Pro
     cd Burpsuite-Pro
     ```

2. **Run the Linux.sh Script**:

   - In the terminal, navigate to the directory where you cloned the repository.
   - Run the `BS-PRO.sh` script by executing the following command:

     ```shell
     chmod +x BS-PRO.sh
     ./BS-PRO.sh
     ```

   This script will perform the following actions:

   - Install Java JDK (if not already installed).
   - Launch the keygen for Burp Suite Pro.
   - Guide you to copy the request and paste it into Burp Suite Pro.
   - In Burp Suite Pro, click on "Manual installation."
   - Copy the response from the keygen and paste it into Burp Suite Pro to activate it.

3. **Launch Burp Suite Pro**:

   - After activating Burp Suite Pro, the script will proceed to launch Burp Suite Pro.

Now, you have successfully installed and activated Burp Suite Pro on your Linux system. You can start using it for your security assessments and penetration testing tasks.

## Troubleshooting

If you encounter any issues during the installation process or have any questions, feel free to reach out to me on Instagram for assistance.

[![Instagram Profile](https://img.icons8.com/color/48/000000/instagram-new.png)](https://www.instagram.com/sneckey0day/)

I'll be happy to help you with any problems or queries you may have.

