Dataset Source: State that the dataset is synthetically generated using Python scripts and predefined templates for school-related scenarios. Mention that no real personal data was used.
Labeling Guidelines: Explain that emails are categorized into 'Admissions', 'Finance', 'Support', and 'General' based on their content and purpose.
Admissions: Emails related to application status, offers of admission, open days, and enrollment.
Finance: Emails concerning tuition fees, financial aid, scholarships, and outstanding balances.
Support: Emails addressing technical issues, IT announcements, resource access, and general help requests.
General: Broad communications like holiday announcements, campus events, policy updates, and general reminders.
Sample Rows: Include a few sample rows from the school_emails.csv file to illustrate the data format. You can copy these directly from the output of the df_loaded_emails.head() command above.
Here is an example of how you might structure the sample rows in your README:

## Sample Data

| email_content                                                                                                                                                                                                                                                                       | category   |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------|
| Dear Maria Garcia, congratulations! We are pleased to offer you admission to Computer Science for the upcoming academic year. Please refer to the attached documents for next steps. Sincerely, Admissions Office.                                                                       | Admissions |
| Subject: Your application to English Literature at City College - Update. Dear David Kim, your application is currently under review. We will notify you of our decision by 2024-11-20. Thank you for your patience. Regards, Admissions Team.                                         | Admissions |
| Dear Alex Lee, this is a reminder that your tuition fee payment for the Fall 2024 semester is due on 2024-10-05. Please visit the student portal to make your payment. Thank you, Finance Department.                                                                                   | Finance    |
| Subject: Financial Aid Application Update. Dear Sarah Chen, your financial aid application for 2024-2025 has been processed. Please check your student account for details. Best regards, Financial Aid Office.                                                                         | Finance    |
| Dear Maria Garcia, your support ticket #7890 regarding Wi-Fi connectivity has been received. We aim to respond within 24 hours. Thank you, IT Support.                                                                                                                               | Support    |
