# 🚀 Microsoft Office Installation and Activation Guide

Follow these step-by-step instructions to easily install and activate Microsoft Office (Word, Excel, PowerPoint, etc.) on your system.

---

## 🛠️ Part 1: Installation

> **⚠️ IMPORTANT:** You **MUST** run your command line as Administrator for this to work. This is the most necessary part of the process.

1. Open **Command Prompt (`cmd`)** from your Windows start menu and make sure to select **Run as administrator**. 
2. Navigate to the root of your `C:` drive by typing the following command and pressing **Enter**:
   ```cmd
   cd C:\
   ```
3. Clone the repository to your system using Git:
   ```cmd
   git clone https://github.com/MAbdullahGp/microsoft-office-download-install-guide.git
   ```
   *(💡 **Note:** If you do not have Git installed, you can simply download this repository as a `.zip` file from the top of this page. As a best practice, move the `.zip` file directly into your `C:\` drive and extract it right there.)*

4. Change your directory into the newly downloaded folder (replace the dots with your exact folder name if it is different):
   ```cmd
   cd microsoft-office-download-install-guide
   ```
5. Run the following setup command. *(Again, double-check you are running as Administrator, otherwise this will fail)*:
   ```cmd
   setup.exe /configure Configuration.xml
   ```
6. A downloading window will pop up. **Be patient.** This step takes a bit of time (around 10-15 minutes) depending on your system specs and internet connection. Let it run completely.
7. Once it downloads successfully and the window finishes, you can close the Command Prompt. 

---

## 🔑 Part 2: Activation

Office and Excel are now downloaded successfully to your computer, but we still need to activate them to use them. Follow these steps for activation:

1. Open **PowerShell** from your Windows start menu and make sure to select **Run as administrator**.
2. Type the following command and press **Enter**:
   ```powershell
   irm https://get.activated.win | iex
   ```
3. Wait for a few seconds and an activation menu will pop up. 
   *(💡 **Note:** If you ever need to activate your Windows OS, you can also do that from this same menu).*
4. Look for the **Office (Ohook) Activation** option and select it by typing the number **`2`** on your keyboard.
5. It will take about 10 seconds to process. 

**🎉 Once finished, you are completely good to go!** You can now open Word or Excel and start working.

---

### ⭐ Did this work for you?
If this guide helped you easily install and activate Office, **please consider leaving a star on this repository!** It helps a lot and lets others know it works.
