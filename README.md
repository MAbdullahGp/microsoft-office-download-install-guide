Microsoft Office Installation and Activation Guide

Follow these step-by-step instructions to easily install and activate Microsoft Office (Word, Excel, etc.) on your system.
Part 1: Installation

⚠️ IMPORTANT: You must run your command line as Administrator for this to work. This is the most necessary part.

    Open Command Prompt (cmd) and make sure to Run as administrator.

    Navigate to the root of your C: drive by typing the following command and pressing Enter:
    DOS

cd C:\

Clone the repository to your system:
DOS

git clone https://github.com/MAbdullahGp/microsoft-office-download-install-guide.git

(Note: If you do not have Git installed, you can just download this repository as a .zip file. As a best practice, paste the .zip file directly into your C:\ drive and extract it there.)

Change your directory into the newly downloaded folder (replace the dots with your exact folder name):
DOS

cd microsoft-office-download-install-guide

Run the following setup command. (Again, make sure you are running as Administrator, otherwise it won't work):
DOS

    setup.exe /configure Configuration.xml

    A downloading window will pop up. Be patient. This step takes a lot of time (around 10-15 minutes) depending on your system specs and internet connection. Let it run.

    Once it downloads successfully, you can close the Command Prompt.

Part 2: Activation

Office and Excel are now downloaded successfully, but we need to activate them. Follow these steps for activation:

    Open PowerShell and make sure to Run as administrator.

    Type the following command and press Enter:
    PowerShell

    irm https://get.activated.win | iex

    Wait for a few seconds and a menu will pop up. (Note: If you ever want to activate your Windows, you can also do that from here).

    Look for the Office (Ohook) Activation option and select it by typing the number 2 on your keyboard.

    It will take something like 10 seconds to process.

Once finished, you are good to go for everything!

⭐ If this worked for you, please consider leaving a star on this repository!
