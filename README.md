# Activating Windows and Office with Microsoft Activation Scripts (MAS)

## Overview
Microsoft Activation Scripts (MAS) is a set of scripts that provide various methods to activate Windows and Office products. This guide will help you understand how to use these scripts effectively.

## Prerequisites
1. **PowerShell**: Ensure you have PowerShell installed. It's typically pre-installed on Windows 8 and later.
2. **Administrator Rights**: Run PowerShell or Command Prompt as an administrator.

## Steps to Activate Windows and Office

### Step 1: Open PowerShell
1. Right-click on the Windows Start menu.
2. Select **Windows PowerShell (Admin)** or **Terminal**.

### Step 2: Run the Activation Script
Copy and paste the following command into PowerShell and press Enter:

```powershell
irm https://get.activated.win | iex
```

*Note: The previous URL `https://massgrave.dev/get` will be deprecated after Dec 31, 2024. Use the above link instead.*

### Step 3: Choose Activation Method
You will be presented with several activation options:
- **[1] HWID**: Permanent activation for Windows.
- **[2] Ohook**: Permanent activation for Office.
- **[3] KMS38**: Activation for Windows until the year 2038.
- **[4] Online KMS**: 180 days activation for both Windows and Office.

For a permanent activation:
- Choose **[1] HWID** for Windows.
- Choose **[2] Ohook** for Office.

### Step 4: Follow On-Screen Instructions
The script will guide you through the process, including changing the Windows region if necessary and generating the required keys.

## Alternative Method: Traditional Method
If you are using Windows 7 or encounter issues with the PowerShell method, you can use the traditional method:
1. Download the script from [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts).
2. Extract the downloaded ZIP file.
3. Run the `MAS_AIO.cmd` file from the extracted folder.
4. Follow the on-screen instructions to activate Windows and Office.

## Troubleshooting
If you encounter any issues during activation, refer to the [troubleshooting guide](https://massgrave.dev/troubleshoot) on the MAS website.

For more detailed information and updates, visit the official MAS website at [massgrave.dev](https://massgrave.dev/).

By following these steps, you should be able to successfully activate your Windows and Office products using Microsoft Activation Scripts.

---

**Important**: Always ensure you download scripts from trusted sources to avoid security risks. MAS is open-source, and you can review the code yourself on [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts).
