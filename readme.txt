Step 1: Prerequisites

You need to have Python installed on your computer( works well with python 3.9 and 3.11.1 ). You can download it from the 
official Python website: https://www.python.org/downloads/.
Step 2: Download and Install Chrome

If you don't already have Google Chrome installed, download and install it from the
official website: https://www.google.com/chrome/.
Step 3: Download the Python Script

Download the Python script from your source, and save it to a location on your
computer.
Step 4: Install Required Python Libraries

Open a command prompt or terminal window on your computer,
REFER THIS to run this code on command prompt (https://www.youtube.com/watch?v=bgSSJQolR0E)

or in any IDE you have (VsCode, etc)
Navigate to the directory where you saved the Python script using the cd command.
For example, if you saved it on your desktop, you can use cd Desktop to navigate
there.
Run the following command to install the necessary Python libraries:
Copy code
pip install openpyxl selenium
Step 5: Run the Python Script

Open a command prompt or terminal window and navigate to the directory where you saved the Python script.
Run the script by typing the following command and pressing Enter:
Copy code
python script_name.py
Replace script_name.py with the actual name of the Python script you downloaded.
( In your case, it is "python main.py")


Step 6: Sign in to LinkedIn

The script will open a Chrome window and navigate to the LinkedIn login page.
Enter your LinkedIn email address and password when prompted.You can either type it
manually on your browser or use this script to avoid the hassle of entering details
everytime by entering your linkedin account email and password so the script
automatically logs in. Please Check line 21 and 25 of main.py and find this code
mentioned as:

//Enter your email and password inside the quotes
username.send_keys('yourlinkedinemail@email.com') 
password.send_keys('yourlinkedinpassword')
Note: You can use any linkedin account to log in.

You may need to complete any additional authentication steps required by LinkedIn.
Step 7: Verification

The script will ask you to verify the sign-in process. Press Enter to continue.
Step 8: Enter LinkedIn Profile URLs

The script will prompt you to enter LinkedIn profile URLs. You can find these URLs
by visiting a LinkedIn profile and copying the address from your browser's address
bar.
Enter the profile URLs one at a time, and press Enter after each one.
If you want to finish entering URLs, you can type 'exit' and press Enter.
Step 9: Data Collection

The script will attempt to collect data from the LinkedIn profiles you entered.
If an error occurs while collecting data for a particular profile (e.g., an invalid
URL), the script will display an error message and allow you to enter another URL.
Continue entering URLs until you have collected all the data you need.
Step 10: Data Saved

Once you finish entering URLs, the script will save the collected data to an Excel
file named 'linkedin_profiles.xlsx'.
The Excel file will contain the profile names, profile image URLs, and profile URLs
of the LinkedIn profiles you entered.
Step 11: Viewing the Data

You can open the 'linkedin_profiles.xlsx' file using Microsoft Excel or a similar
spreadsheet program to view and analyze the collected data.
That's it! You've successfully used the Python script to scrape LinkedIn profile data.
