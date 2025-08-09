# File-Permissions-Task

# Description
This project demonstrates understanding and applying Linux file permissions using both symbolic and numeric methods.  
The required permission is `rwxrwxr-x` (numeric value `775`).

# Steps Performed
1. Created a test file:
   ```bash
   touch myfile.py
------------------------------
Changed permissions to 775:
   chmod 775 myfile.py
--------------------------------
Verified the changes:
ls -l myfile.py
----------------------------------
Output:
-rwxrwxr-x  1 user group   0 Aug 9 07:31 myfile.py
----------------------------------------------------

# Flowchart
A flowchart is provided to illustrate the process of determining permissions and applying them.
-----------------------------------------------------
You can also set file permissions using Python:

import os
os.chmod("myfile.py", 0o775)
print("Permissions changed to rwxrwxr-x")

نسخ
تحرير


