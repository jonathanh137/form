### Tuition and Fees Payment Authorization Form for Graduate Students

---

### <div style="text-align:center">Marton Demeter, Jonathan Ho, Sanika Lakka</div>

---

Files in the drive:
- confirmation.php - Page after advisor/signer approves form. 
- deletion.php - Page after advisor deletes form.
- final.php - Page after the final approver approves the form.
- get_student_info.php - Page displayed for each advisor/signer.
- install - Install script (don't forget to change information)
- java.js - Holds the javascript code used in the websites 
- process_form.php - Stores the data written by the TA into database and send email to advisor
- readme.md - This file
- rejection.php - Page displayed to the advisor after they reject the form
- scu.jpg - Banner at the top of each page
- source.php - Page the TA/RA fills in. 
- style.css - Holds CSS code used in the websites

---

Steps to set up the system:

1. All the files must be put into php-cgi folder (must run with the correct permissions)
2. Put correct database credentials in secrets.txt (first line username, second line password)
3. secrets.txt needs 400 (read only by user) permission

OR

1. Fill in the correct database credentials and install directory in the install script. Running the script will fetch the current version from GitHub.  
