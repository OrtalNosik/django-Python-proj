# Django web application, crafted with Python - MedicalCare
offer the treatment the most suitable for the patient with django and python
this Django web application, crafted with Python and seamlessly integrates robust features for efficient data management and a user-friendly experience.
The software adhere to the following fundamental requirements:

1. **Doctor Authentication:**
   - An initial screen where the doctor provides credentials (username and password) to access the system.
   - Display an appropriate error message for any discrepancies in the provided details.

2. **User Registration:**
   - New user registration with the following criteria:
     - Username: Between 6 and 8 characters, with at most 2 digits and the rest being English letters.
     - Password: Between 8 and 10 characters, including at least one letter, one digit, and one special character (!$, #, etc.).
     - Unique identifier (Number 17).
   - Display an appropriate error message for any discrepancies in the registration details.

3. **Patient Information:**
   - Capability to input patient details and their medical condition, with necessary fields to be determined.
   
4. **Excel File Import:**
   - Option to import an Excel file containing the patient's medical condition, including blood test values. Note that percentage values in Appendix 1 should also be reflected as percentages in the Excel file.

5. **Diagnosis and Treatment:**
   - A button that, when pressed, reveals the medical diagnosis and recommended treatment based on Appendix 1.

6. **Record Keeping:**
   - Save all patient visit details, including patient information, indicators, diagnosis, and treatment, in an Excel file.

7. **Questioning System:**
   - The system can prompt the patient with predefined yes/no questions during the diagnosis process (e.g., do you smoke?).
   - Consider the patient's responses in the diagnosis.
   - The list of questions is predetermined in the software, and there is no provision for adding more questions.

run from your terminal: python manage.py runserver

These requirements form the foundation of the software, ensuring a secure and comprehensive system for managing patient data and medical conditions.

![image](https://github.com/OrtalNosik/django-Python-proj/assets/93153515/e893b7cc-5227-49f0-bda5-531c2c7ca9dc)
![image](https://github.com/OrtalNosik/django-Python-proj/assets/93153515/2d24f92f-d628-46ed-a503-04fff6e72147)
![image](https://github.com/OrtalNosik/django-Python-proj/assets/93153515/3e47f6d4-1b36-4ee4-bac4-9c0f6fa536c4)
![image](https://github.com/OrtalNosik/django-Python-proj/assets/93153515/42d31e27-f941-4599-8ebc-87f3e3e1cb19)

