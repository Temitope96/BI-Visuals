## U.S Health Analytics

I leveraged a U.S Health Dataset to perform descriptive analytics, comparing 10 hospitals across patient demographics, prevalence of major health conditions, medical patterns and treatment costs versus insurance providers.

![Case 1 pix](https://dl.boxcloud.com/api/2.0/internal_files/1880642382570/versions/2074136087370/representations/png_paged_2048x2048/content/1.png?access_token=1!8nJKWzLIPezakAzNI2EpO8v2ZataeoaZP8-AIsiXoNTUpmDSaptgJcaiVN9DvMmdVqCynDtwSDfOYO3pKC-m-XvxbsIzEyPbB6fyB4OV4k8j0-3kei_0BC30hCCI3Ny9voImw-HOBASyp4EpfCzkvMFAf2fR3_iYXzGyb0D2iaeKkQVUIsIVS50DdSgoM-JccXXmNONgRZQ0BkoU1PIu5sO29jZ8cPLNAZ3tF57t8lYAHwCtId2qSDuy03yHbSzZuSDnMSC__mTileT6AfDNwT2D6PBqwBA74Y6BsWkcBxT32iS57O8EfPBTBrNUIWeiXEtTcEmrxZoGMGWAN2_9ExMUEeK8Cmcfx4FYkU1CsORDqyW7kwzpdlHqgvfZ_fwgsv4n28LfligbYX-dPeSBGYIudmJ9rORR_0JJcdWlg46gNepyIAGlA7Cw1vnKT-Ja178qIBUhScb2WRjyNvk9nYQ83Hd5I6BOVjj-a_lYD6fcqcYzs9wxj2JvsTDDJCe-dPF9sERIGjXdalWRnlvJ5_REdY-F3MnCw8oROaBm4QZ6rZ9WZJo_Su-UE9MaefEyofJ97zajzbpaXXg_9H0eCDNVV5d1JS7i5QZnPTaigMBk-ux8p_kvAgqFrpUEp028ZGE45Adzloxr8sl_lZwZeXBVnFiQxFZNHwiPWa-KpQKGm3XkGDijZxwBdgkVePD3M5H0VAvYr8JBAqI5v75MBj7WxIfuSOUYVQ1yEDXMjm-aYP58n213YzmpdfjW&box_client_name=box-content-preview&box_client_version=3.7.0?fit=scale)

## 📕 Project Summary
This dashboard provides a comprehensive analysis of hospital operations, patient demographics, and medical trends using the U.S. Health Dataset. By exploring dimensions such as gender, age, medical conditions, insurance coverage, and admission patterns, several actionable insights were uncovered, a few of which are:
- Hospital Utilization: Certain hospitals (like Houston Methodist and Johns Hopkins Hospital) consistently receive the highest patient volume, particularly for urgent and elective admissions, suggesting a need for better capacity planning and resource allocation.
- Medical Condition Trends: Hypertensive, Diabetic and Obesity-related conditions appear as the most prevalent diagnoses, with clear spikes in most hospitals and age and gender groups.
- Insurance Coverage Impact: Patients covered by "Medicare" and "Cigna" generated the highest billing amounts, across the most prevalent medical conditions hinting at potential differences in coverage or care complexity.
- Demographic Patterns: Female patients slightly outnumber males in all admission types. All Asthma and Cancer patients possessed blood type A+, while all Arthritis patients were O-. Obese patients were of 5 different blood types compared to Diabetes and Hypertension which had 3 and 2 blood types respectively. It is also worthy of note that Asthmatic conditions was not noticed in any non-binary patient.
- Length of Stay Insights: Patients admitted for elective procedures had medium stays on average, while emergency cases saw longer durations, especially in elderly patients (aged 60 and above) as they had more urgent and emergency cases.

These insights can support decision-making in hospital management, resource allocation, and personalized patient care strategies.

## 🛠️ Tools & Skills Used
- Data Exploration: I surfed through the data to understand what its about. While doing that, I observed for inconsistencies (dirts) in the dataset too. I also created my list of possible insights-to-explore and trends-to-uncover in the data (and sketched what I like to call my abstract/imaginary dashboard.) ;)
- Data Cleaning: Upon checking for blanks, inconsistent data types, non-standardized data types, I discovered that the dataset was fairly clean. However, I did remove irrelevant columns and features not needed for my analysis.
- Data Segmentation (Derived Variables): I stratified columns like 'Age' into groups for clarity. I also grouped the difference between the two dates ('Admission date' and 'Discharge date') into three (3) groups. This was done to avoid data ambiguity and redundancy.
- Data Modeling: USing DAX, I created measures (and tables where necessary especially for explicit sorting orders), columns and hierarchies to aid my statistical logics, KPIs and aggregations. This is to make slicing and dicing of the data across filters dynamic, smooth and more insightful.
- Data Analysis & Visualizations: I inserted multiple visuals (bar, column & doughnut charts, matrix tables, slicers and text boxes.

## 🗒️ Note
I documented every step taken along the way indicating the need for every measure, hiererchy, stratification, and even charts to substantially track every progress and milestone along the way.



