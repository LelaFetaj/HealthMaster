# HealthMaster
This repository contains a Healthcare Management System aimed at streamlining patient registration and user management. It provides a platform for managing user profiles, patient data, and hospital information, all while ensuring robust security through authentication measures to enhance the efficiency of healthcare services.

Technologies Used
C#: For backend development.
ASP.NET Core: Web framework for building web applications and APIs.
SQL Server: Database for storing user and patient data.
Docker: For containerization, ensuring consistent deployment across environments.
RabbitMQ: For asynchronous messaging and handling background tasks.


1. User master data
2. Patient registrations fotm table (one table or more)
3. Hospital master data
4. Healthcare prefessionals master data

1. Captcha -> https://learn.microsoft.com/en-us/aspnet/web-pages/overview/security/using-a-catpcha-to-prevent-automated-programs-bots-from-using-your-aspnet-web-site
2. Configuration code via sms for patients (wave 4)
3. Configuration code via email for patients (wave 4)
4. MFA for users with @nhs.net email/sms -> https://learn.microsoft.com/en-us/aspnet/core/security/authentication/mfa?view=aspnetcore-8.0

wave 1
1. Register +
2. Login +
3. Profile ( change password, email)
4. Reset Password +
5. Home Screen +
6. Patient Registration Page: Patient fields | Service and delivery fields I Referring physician fields | Invoicing details fields I Invoicing details fields | Patient registrations list fields I Atttachments to reg forms I Review | Submit
7. Dashboard
8. Header
9. Footer
10. Support no login required

wave 2 
7. Patiert user view (with filter) - Add new patient

-> Internal user o Healthcare Professional

1. Healthcare Professianal
2. Healthcare Admin
3. Polar speed Admin
4. Master admin

1. Password Complexity
2. Password Auto Lock
3. Auto Log off - 5 min
4. Email check
5. Patient Check

1. Registrations Loads - 100.000 patient registrations 
2. Registration Performance - 100 Registrations Per Second
3. User Stress - 10.00 Users

1. Attachments will be saved in a blob azure storagein a folder that has the name of web portal patient id
2. Patient web portal ID & Patient CRM ID ->
3. TBD Patient Registration Form will in one page or we should split with steps so you complete step 1 andthen move forward -> with sections Next & Previous

*  View all patients in hospital if they are assigned to the hospital also -> requst to view all hospitals patients on an user.
*  User registrations with confiramtion from Polar Speed Admin or Master Admin.
*
