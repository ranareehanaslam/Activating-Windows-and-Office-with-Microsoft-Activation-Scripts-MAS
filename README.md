# Activating Windows and Office with Microsoft Activation Scripts (MAS)



## Overview
Microsoft Activation Scripts (MAS) offers a variety of methods to activate Windows and Office products. This guide will walk you through the steps to use these scripts, making the process simple even for beginners.

## Prerequisites
- **PowerShell**: Ensure PowerShell is installed (pre-installed on Windows 8 and later).
- **Administrator Rights**: You need to run PowerShell or Command Prompt as an administrator.

## Steps to Activate Windows and Office

### Step 1: Open PowerShell
1. **Open Start Menu**: Click on the Windows icon.
2. **Find PowerShell**: Type "PowerShell" in the search bar.
3. **Run as Administrator**: Right-click on **Windows PowerShell** and select **Run as Administrator**.


### Step 2: Run the Activation Script
Copy and paste the following command into PowerShell and press Enter:

```powershell
irm https://get.activated.win | iex
```

*Note: The old URL `https://massgrave.dev/get` will be deprecated after Dec 31, 2024. Use the updated link.*

### Step 3: Choose Activation Method
You will see a menu with several options:
- **[1] HWID**: Permanent activation for Windows.
- **[2] Ohook**: Permanent activation for Office.
- **[3] KMS38**: Activation for Windows until the year 2038.
- **[4] Online KMS**: 180 days activation for both Windows and Office.

For permanent activation:
- Select **[1] HWID** for Windows.
- Select **[2] Ohook** for Office.



### Step 4: Follow On-Screen Instructions
The script will guide you through the necessary steps, including:
- Changing the Windows region if needed.
- Generating the required keys.
- Confirming successful activation.



## Alternative Method: Traditional Method
If you are using Windows 7 or have issues with the PowerShell method, use this method:
1. **Download the Script**: Get the script from [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts).
2. **Extract ZIP File**: Right-click the downloaded ZIP file and select **Extract All**.
3. **Run the Script**: Open the extracted folder and run `MAS_AIO.cmd`.
4. **Follow Instructions**: Follow the on-screen instructions to activate your products.



## Troubleshooting
For any issues, refer to the [troubleshooting guide](https://massgrave.dev/troubleshoot) on the MAS website. Additional help and FAQs can also be found there.

## Additional Resources
- [MAS GitHub Repository](https://github.com/massgravel/Microsoft-Activation-Scripts)
- [MAS Official Website](https://massgrave.dev/)
- [Download Genuine Windows & Office](https://massgrave.dev/genuine-installation-media)

By following these detailed steps, you can easily activate your Windows and Office products using Microsoft Activation Scripts, ensuring they are genuine and permanently activated.

---

**Important**: Always download scripts from trusted sources to avoid security risks. MAS is open-source, and you can review the code yourself on [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts).
