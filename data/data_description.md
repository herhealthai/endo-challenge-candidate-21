# Endometriosis Diagnosis and Analysis Dataset
This dataset is part of an AI project focused on improving diagnostic and therapeutic approaches for endometriosis. It contains various categories of medical data collected during patient care, including clinical observations, imaging findings, intraoperative details, and postoperative analyses.

# Dataset Overview
This dataset includes the following categories:

- __Clinical Data__: Information collected through patient history and physical examination.
- __Imaging Data__: Data derived from radiological assessments, primarily MRI.
- __Intraoperative Data__: Findings and actions documented during surgical procedures.
- __Postoperative Data__: Results from pathological analysis following surgery.

|Variable	|Category|
|---------------|-------------|
|v.1.11 - Age (at consultation)|Clinical data|
|v.1.12 - Breed declared|Clinical data|
|v.1.13 - Education|Clinical data|
|v.1.14 - Marital status|Image|
|v.7.3 - Is there a retrocervical lesion?|Image|
|v.7.5 - Presence of rectus/sigmoid lesion?|Image|
|v.7.5.1 - If there is a rectus/sigmoid lesion, how many|Image|
|v.7.5.1.1.1 - Lesion 1 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.7.5.1.1.2 - Injury 1 - Straight/sigmoid anteroposterior diameter.|Image|
|v.7.5.1.1.3 - Injury 1 - Straight/sigmoid TR diameter.|Image|
|v.7.5.1.1.4 - Injury 1 - Layers of the intestine compromised by Endometriosis?|Image|
|v.7.5.1.1.5 - Injury 1 - Percentage of intestinal loop involvement.|Image|
|v.4.9 - Peritoneum Injury (sum)|Intraoperative|
|v.4.9.0 - Site of Peritoneal Injury|Intraoperative|
|v.4.9.1 - Peritoneal Lesion Size|Intraoperative|
|v.4.11.1 - If Left Ovary - Endometrioma|Intraoperative|
|v.4.16 - Retrocervical (LUS)|Intraoperative|
|v.4.19 - Rectosigmoid|Intraoperative|
|v.4.19.1 - If Rectosigmoid, how many injuries|Intraoperative|
|v.4.19.1.1 - Rectosigmoid, lesion size 1|Intraoperative|
|v.4.19.1.2 - Rectosigmoid, distance from the anal edge of the lesion 1|Intraoperative|
|v.4.34 - Surgical difficulty|Intraoperative|
|v.9.3 - Anatomopathological Result in the Peritoneum|Postoperative|
|v.9.3.1 - Peritoneum - Endometriosis not classified|Postoperative|
|v.9.3.2 - Peritoneum - Stromal|Postoperative|
|v.9.3.5 - Peritoneum - Mixed|Postoperative|
|v.9.11 - Anatomopathological Result of the Retrocervical Region|Postoperative|
|v.9.11.1 - Result of the Retrocervical Region - Endometriosis not classified|Postoperative|
|v.9.11.2 - Result of the Retrocervical Region - Stromal|Postoperative|
|v.9.11.3 - Result of the Retrocervical Region - Well Differentiated|Postoperative|
|v.9.11.4 - Result of the Retrocervical Region - Undifferentiated|Postoperative|
|v.9.11.5 - Result of the Retrocervical Region - Mixed|Postoperative|
|v.9.14 - Has injury to the Rectum/Sigmoid|Postoperative|
|v.9.14.1 - Number of injuries in the Rectum/Sigmoid|Postoperative|
|v.9.14.1.1.1 - Lesion 1 - Rectum / Sigmoid Result - Endometriosis not classified|Postoperative|
|v.9.14.1.1.2 - Injury 1 - Result of Rectum / Sigmoid - Stromal|Postoperative|
|v.9.14.1.1.3 - Injury 1 - Rectum / Sigmoid Result - Well Differentiated|Postoperative|
|v.9.14.1.1.4 - Injury 1 - Rectum / Sigmoid Result - Undifferentiated|Postoperative|
|v.9.14.1.1.5 - Injury 1 - Rectum / Sigmoid Result - Mixed|Postoperative|
|AAGL Classification|Intraoperative|
|Event Name|Clinical data|
|v.4.1 - Date of Surgery|Intraoperative|
|Complete?|Intraoperative|
|v.1.3 - Location of Service|Clinical data|
|v.1.3.0 - If another location of service, which one?|Clinical data|
|v.1.4 - Consultation Date|Clinical data|
|v.1.14 - Marital status|Clinical data|
|Complete?|Clinical data|
|Questionnaire Application Date|Clinical data|
|Options|Clinical data|
|a.Rigorous activities, which require a lot of effort, such as running, lifting heavy objects, participating in strenuous sports.|Clinical data|
|b. Moderate activities, such as moving a table, vacuuming, playing ball, sweeping the house.|Clinical data|
|c.Lifting or carrying supplies|Clinical data|
|d. Climb several flights of stairs|Clinical data|
|and. Climb a flight of stairs|Clinical data|
|f. Bow, kneel or bend|Clinical data|
|g. Walk more than 1 kilometer|Clinical data|
|h. Walk several blocks|Clinical data|
|i. Walk a block|Clinical data|
|j. Bathing or getting dressed|Clinical data|
|Score question 3|Clinical data|
|a. Do you reduce the amount of time you dedicate to your work or other activities?|Clinical data|
|b. Did you perform fewer tasks than you would like?|Clinical data|
|w. You were limited in your type of work or other activities.|Clinical data|
|d. Had difficulty doing work or other activities (for example, needed extra effort).|Clinical data|
|Score question 4|Clinical data|
|the. Do you reduce the amount of time you dedicate to your work or other activities?|Clinical data|
|w. He did not carry out or do any of the activities as carefully as he usually does.|Clinical data|
|Score question 5|Clinical data|
|Score|Clinical data|
|the. How long have you been feeling full of vigor, will and strength?|Clinical data|
|b. How long have you felt like a very nervous person?|Clinical data|
|w. How long have you been feeling so depressed that nothing can cheer you up?|Clinical data|
|d. How long have you felt calm or peaceful?|Clinical data|
|and. How long have you felt very energetic?|Clinical data|
|f. How long have you been feeling discouraged or down?|Clinical data|
|g. How long have you been feeling exhausted?|Clinical data|
|h. How long have you felt like a happy person?|Clinical data|
|i. How long have you been feeling tired?|Clinical data|
|Score question 09 (Vitality a,e,g,i)|Clinical data|
|Score question 09 Mental Health (b,c,d,f,h)|Clinical data|
|the. I tend to obey a little more easily than other people|Clinical data|
|w. I think my health will get worse|Clinical data|
|b. I'm as healthy as anyone I know|Clinical data|
|d. My health is excellent|Clinical data|
|Score question 11|Clinical data|
|1. Functional Capacity|Clinical data|
|2.Limitation due to physical aspects|Clinical data|
|3.Pain|Clinical data|
|4.General Health Status|Clinical data|
|5. Vitality|Clinical data|
|6. Social Aspects|Clinical data|
|7. Limitation due to emotional aspects|Clinical data|
|8. Mental Health|Clinical data|
|v.1.15 - Height|Clinical data|
|v.1.16 - Weight|Clinical data|
|v.1.17 - BMI|Clinical data|
|v.2.1 - Does the patient have any comorbidities?|Clinical data|
|v.2.1.2 - What comorbidities(are)|Clinical data|
|v.2.1.2.1 - Cardiovascular/metabolic diseases|Clinical data|
|v.2.1.2.1.1 - Cardiovascular/metabolic diseases - Others|Clinical data|
|v.2.1.2.2 - Heart Diseases|Clinical data|
|v.2.1.2.2.1 - Heart Diseases - Others|Clinical data|
|v.2.1.2.3 - Vascular diseases|Clinical data|
|v.2.1.2.3.1 - Vascular diseases - Others|Clinical data|
|v.2.1.2.4 - Thromboembolic disease|Clinical data|
|v.2.1.2.4.1 - Thromboembolic disease - Others|Clinical data|
|v.2.1.2.5 - Psychiatric illnesses|Clinical data|
|v.2.1.2.5.1 - Psychiatric illnesses - Others|Clinical data|
|v.2.1.2.6 - Painful syndromes|Clinical data|
|v.2.1.2.6.1 - Painful syndromes - Others|Clinical data|
|v.2.1.2.7 - Autoimmune diseases|Clinical data|
|v.2.1.2.7.1 - Autoimmune diseases - Others|Clinical data|
|v.2.1.2.8 - Inflammatory bowel diseases|Clinical data|
|v.2.1.2.8.1 - Inflammatory bowel diseases - Others|Clinical data|
|v.2.1.2.9 - Thyroid diseases|Clinical data|
|v.2.1.2.9.1 - Thyroid diseases - Others|Clinical data|
|v.2.1.2.10 - Congenital malformations|Clinical data|
|v.2.1.2.10.1 - Congenital malformations - Others|Clinical data|
|v.2.1.2.11 - Cancer (except thyroid)|Clinical data|
|v.2.1.2.11.1 - Cancer (except thyroid) - Others|Clinical data|
|v.2.1.2.12 - Kidney diseases|Clinical data|
|v.2.1.2.12.1 - Kidney diseases - Others|Clinical data|
|v.2.1.2.13 - Neurological diseases|Clinical data|
|v.2.1.2.13.1 - Neurological diseases - Others|Clinical data|
|v.2.1.2.14 - Liver diseases|Clinical data|
|v.2.1.2.14.1 - Liver diseases - Others|Clinical data|
|v.2.1.2.15 - Lung diseases|Clinical data|
|v.2.1.2.15.1 - Lung diseases - Others|Clinical data|
|v.2.1.2.16 - Other Comorbidities|Clinical data|
|v.2.2 - Regular Physical Activity|Clinical data|
|v.2.3 - Smoking|Clinical data|
|v.2.4 - Previous surgeries for endometriosis|Clinical data|
|v.2.4.1 - How many previous surgeries for endometriosis performed?|Clinical data|
|v.2.5 - Other previous abdominal surgeries?|Clinical data|
|v.2.5.1 - How many previous abdominal surgeries performed|Clinical data|
|v.2.6 - How long have you been without using hormonal medication|Clinical data|
|v.2.6.1 - What medication is used?|Clinical data|
|v.2.6.1.1 - If another medication, which one?|Clinical data|
|v.2.7 - Diagnosis of endometriosis in the family?|Clinical data|
|v.2.7.1 - Endometriosis Kinship Degree - Mother|Clinical data|
|v.2.7.2 - Endometriosis Kinship Degree - Irma|Clinical data|
|v.2.7.3 - Endometriosis Kinship Degree - Cousins|Clinical data|
|v.2.7.4 - Endometriosis Kinship Degree - Aunts|Clinical data|
|v.2.7.5 - Endometriosis Kinship Degree - Avos|Clinical data|
|v.2.7.6 - Endometriosis Kinship Degree - Daughters|Clinical data|
|v.2.8 - Menstruation interval in the last 6 months|Clinical data|
|v.2.9 - Amount of Menstrual Flow|Clinical data|
|v.2.26 - You are in menopause|Clinical data|
|2.26.1 - If you are in menopause, what type?|Clinical data|
|v.2.26.2 - Age at menopause?|Clinical data|
|v.2.10 - Age of first menstruation (menarche)?|Clinical data|
|v.2.11 - Number of Pregnancies|Clinical data|
|v.2.11.1 - Parity (Number of children born)|Clinical data|
|v.2.11.2 - Number of normal births|Clinical data|
|v.2.11.3 - Number of cesarean births|Clinical data|
|v.2.11.4 - Number of abortions|Clinical data|
|v.2.11.5 - Number of Ectopic Pregnancies.|Clinical data|
|v.2.11.6 - Obstetric Complications|Clinical data|
|v.2.11.6.1 - Obstetric complications, which ones?|Clinical data|
|v.2.11.6.1.1 - Other Obstetric Complications, which ones?|Clinical data|
|v.2.12 - Dysmenorrhea (menstrual cramps)|Clinical data|
|v.2.13 - Had sexual activity (vaginal penetration)|Clinical data|
|v.2.13.1 - Dyspareunia (pain with deep penetration)|Clinical data|
|v.2.14 - Acyclic pelvic pain (outside the menstrual period)|Clinical data|
|v.2.15 - Cyclical Intestinal Change (pain during bowel movements during menstruation)|Clinical data|
|v.2.24 - Other cyclical intestinal changes (during the menstrual period)?|Clinical data|
|v.2.16 - What other intestinal changes during menstruation|Clinical data|
|v.2.16.1 - If other intestinal changes, what are they?|Clinical data|
|v.2.17 - Cyclical Urinary Change (Pain when urinating during menstruation)|Clinical data|
|v.2.25 - Another cyclical urinary change (during the menstrual period)|Clinical data|
|v.2.18 - What are urinary changes during menstruation|Clinical data|
|v.2.18.1 - If there are other urinary complications during menstruation, what are they?|Clinical data|
|v.2.19 - Do you have infertility?|Clinical data|
|v.2.20 - Had previous treatment for infertility|Clinical data|
|v.2.20.1 - What is the previous treatment for infertility|Clinical data|
|v.2.21 - Did you perform Gamete Freezing prior to surgery?|Clinical data|
|v.2.21.1 - What type of Pre-Freezing|Clinical data|
|v.2.21.1.1 - Number of frozen eggs|Clinical data|
|v.2.21.1.2 - Number of frozen embryos|Clinical data|
|7.1 - Ultrasound Exam Date|Image|
|v.7.2 - Examiner|Image|
|v.7.30 - Is there peritoneal injury?|Image|
|v.7.30.1 - Site of Peritoneal Injury|Image|
|v.7.30.2 - Peritoneal Lesion Size|Image|
|v.7.3.1 - Largest diameter of the retrocervical lesion.|Image|
|v.7.4 - Presence of vaginal injury?|Image|
|v.7.4.1 - Largest diameter of the vaginal lesion.|Image|
|v.7.5.1.1.6 - Injury 1 - Distance from the Anal Edge.|Image|
|v.7.5.1.2.1 - Lesion 2 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.7.5.1.2.2 - Injury 2 - Straight/sigmoid anteroposterior diameter.|Image|
|v.7.5.1.2.3 - Lesion 2 - Straight/sigmoid TR diameter.|Image|
|v.7.5.1.2.4 - Injury 2 - Layers of the intestine compromised by Endometriosis?|Image|
|v.7.5.1.2.5 - Injury 2 - Percentage of intestinal loop involvement.|Image|
|v.7.5.1.2.6 - Injury 2 - Distance from the Anal Edge.|Image|
|v.7.5.1.3.1 - Lesion 3 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.7.5.1.3.2 - Injury 3 - Straight/sigmoid anteroposterior diameter.|Image|
|v.7.5.1.3.3 - Lesion 3 - Straight/sigmoid TR diameter.|Image|
|v.7.5.1.3.4 - Injury 3 - Layers of the intestine compromised by Endometriosis?|Image|
|v.7.5.1.3.5 - Injury 3 - Percentage of intestinal loop involvement.|Image|
|v.7.5.1.3.6 - Injury 3 - Distance from the Anal Edge.|Image|
|v.7.5.1.4.1 - Lesion 4 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.7.5.1.4.2 - Injury 4 - Straight/sigmoid anteroposterior diameter.|Image|
|v.7.5.1.4.3 - Lesion 4 - Straight/sigmoid TR diameter.|Image|
|v.7.5.1.4.4 - Injury 4 - Layers of the intestine compromised by Endometriosis?|Image|
|v.7.5.1.4.5 - Injury 4 - Percentage of intestinal loop involvement.|Image|
|v.7.5.1.4.6 - Injury 4 - Distance from the Anal Edge.|Image|
|v.7.5.1.5.1 - Lesion 5 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.7.5.1.5.2 - Injury 5 - Straight/sigmoid anteroposterior diameter.|Image|
|v.7.5.1.5.3 - Lesion 5 - Straight/sigmoid TR diameter.|Image|
|v.7.5.1.5.4 - Injury 5 - Layers of the intestine compromised by Endometriosis?|Image|
|v.7.5.1.5.5 - Injury 5 - Percentage of intestinal loop involvement.|Image|
|v.7.5.1.5.6 - Injury 5 - Distance from the Anal Edge.|Image|
|7.31 - Bottom of the bag block|Image|
|7.32 - Injury to the rectovaginal septum|Image|
|7.32.1 - Rectovaginal septum injury - Size|Image|
|v.7.6 - Presence of injury to the appendix?|Image|
|v.7.6.1 - Largest diameter of the lesion in the appendix|Image|
|v.7.6.2 - Site involved in the appendix injury|Image|
|v.7.7 - Presence of lesion in the ileum/small intestine?|Image|
|v.7.7.1 - Largest diameter of the lesion in the ileum/small intestine|Image|
|v.7.29 - Presence of lesion in the cecum|Image|
|v.7.29.1 - Largest diameter of the lesion in the cecum|Image|
|v.7.8 - Presence of Bladder (muscle) injury?|Image|
|v.7.8.1 - Largest diameter of bladder (muscle) injury|Image|
|v.7.9 - There are signs of injury to the Right Ureter (intrinsic)|Image|
|v.7.10 - There are signs of injury to the Left Ureter (intrinsic)|Image|
|v.7.13 - Hydronephrosis|Image|
|v.7.13.1 - If Hydronephrosis 'yes', where|Image|
|v.7.11 - Right ovary|Image|
|v.7.11.1 - Right Ovary - Superficial|Image|
|v.7.11.2 - If Right ovary - Endometrioma|Image|
|v.7.11.2.1 - If right ovary 'Endometrioma', larger diameter|Image|
|v.7.11.3 - If Right ovary - Another cyst|Image|
|v.7.11.3.1 - If Right Ovary 'Another Cyst', which|Image|
|v.7.12 - Left ovary|Image|
|v.7.12.1 - If Left Ovary - Superficial|Image|
|v.7.12.2 - If Left Ovary - Endometrioma|Image|
|v.7.12.2.1 - If left ovary 'Endometrioma', larger diameter|Image|
|v.7.12.3 - If Left ovary - Another cyst|Image|
|v.7.12.3.1 - If Left Ovary 'Another Cyst', which|Image|
|v.7.14 - Right Tubas|Image|
|v.7.15 - Left Tubas|Image|
|v.7.16 - Right Hydrosalpinx|Image|
|v.7.17 - Left Hydrosalpinx|Image|
|v.7.18 - Right Hematosalpinx|Image|
|v.7.19 - Left Hematosalpinx|Image|
|v.7.22 - Uterus Volume|Image|
|v.7.23 - Uterine endometrial echo|Image|
|v.7.24 - Fibroids|Image|
|v.7.25 - Adenomyosis|Image|
|v.7.28 - Endometrial Polyp|Image|
|v.7.26 - Other ultrasound findings|Image|
|v.7.27 - Upload Ultrasonography Exam|Image|
|Complete?|Image|
|v.8.1 - Exam Date|Image|
|v.8.2 - Examiner|Image|
|v.8.31 - Is there peritoneal injury?|Image|
|v.8.31.1 - Site of Peritoneal Injury|Image|
|v.8.31.2 - Peritoneal Lesion Size|Image|
|v.8.3 - Is there a retrocervical lesion?|Image|
|v.8.3.1 - Largest diameter of the retrocervical lesion.|Image|
|v.8.4 - Presence of vaginal injury?|Image|
|v.8.4.1 - Largest diameter of the vaginal lesion.|Image|
|v.8.5 - Presence of rectus/sigmoid lesion?|Image|
|v.8.5.1 - If there is a rectus/sigmoid lesion, how many|Image|
|v.8.5.1.1.1 - Lesion 1 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.8.5.1.1.2 - Injury 1 - Straight/sigmoid anteroposterior diameter.|Image|
|v.8.5.1.1.3 - Lesion 1 - Straight/sigmoid TR diameter.|Image|
|v.8.5.1.1.4 - Injury 1 - Layers of the intestine compromised by Endometriosis?|Image|
|v.8.5.1.1.5 - Injury 1 - Percentage of intestinal loop involvement.|Image|
|v.8.5.1.1.6 - Injury 1 - Distance from the Anal Edge.|Image|
|v.8.5.1.2.1 - Lesion 2 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.8.5.1.2.2 - Injury 2 - Straight/sigmoid anteroposterior diameter.|Image|
|v.8.5.1.2.3 - Lesion 2 - Straight/sigmoid TR diameter.|Image|
|v.8.5.1.2.4 - Injury 2 - Layers of the intestine compromised by Endometriosis?|Image|
|v.8.5.1.2.5 - Injury 2 - Percentage of intestinal loop involvement.|Image|
|v.8.5.1.2.6 - Injury 2 - Distance from the Anal Edge.|Image|
|v.8.5.1.3.1 - Lesion 3 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.8.5.1.3.2 - Injury 3 - Straight/sigmoid anteroposterior diameter.|Image|
|v.8.5.1.3.3 - Lesion 3 - Straight/sigmoid TR diameter.|Image|
|v.8.5.1.3.4 - Injury 3 - Layers of the intestine compromised by Endometriosis?|Image|
|v.8.5.1.3.5 - Injury 3 - Percentage of intestinal loop involvement.|Image|
|v.8.5.1.3.6 - Injury 3 - Distance from the Anal Edge.|Image|
|v.8.5.1.4.1 - Lesion 4 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.8.5.1.4.2 - Injury 4 - Straight/sigmoid anteroposterior diameter.|Image|
|v.8.5.1.4.3 - Lesion 4 - Straight/sigmoid TR diameter.|Image|
|v.8.5.1.4.4 - Injury 4 - Layers of the intestine compromised by Endometriosis?|Image|
|v.8.5.1.4.5 - Injury 4 - Percentage of intestinal loop involvement.|Image|
|v.8.5.1.4.6 - Injury 4 - Distance from the Anal Edge.|Image|
|v.8.5.1.5.1 - Lesion 5 - Straight/sigmoid Longitudinal Diameter.|Image|
|v.8.5.1.5.2 - Injury 5 - Straight/sigmoid anteroposterior diameter.|Image|
|v.8.5.1.5.3 - Lesion 5 - Straight/sigmoid TR diameter.|Image|
|v.8.5.1.5.4 - Injury 5 - Layers of the intestine compromised by Endometriosis?|Image|
|v.8.5.1.5.5 - Injury 5 - Percentage of intestinal loop involvement.|Image|
|v.8.5.1.5.6 - Injury 5 - Distance from the Anal Edge.|Image|
|v.8.33 - Bottom of the Bag Block|Image|
|v.8.34 - Rectovaginal septal injury|Image|
|v.8.34.1 - Rectovaginal septum injury - Size|Image|
|v.8.6 - Presence of injury to the appendix?|Image|
|v.8.6.1 - Largest diameter of the lesion in the appendix|Image|
|v.8.6.2 - Site involved in the appendix injury|Image|
|v.8.7 - Presence of lesion in the ileum/small intestine?|Image|
|v.8.7.1 - Largest diameter of the lesion in the ileum/small intestine|Image|
|v.8.31 - Presence of lesion in the cecum?|Image|
|v.8.31.1 - Largest diameter of the lesion in the cecum|Image|
|v.8.8 - Presence of Bladder (muscular) injury?|Image|
|v.8.8.1 - Largest diameter of Bladder (muscle) injury|Image|
|v.8.9 - There are signs of injury to the Right Ureter (intrinsic)|Image|
|v.8.10 - There are signs of injury to the Left Ureter (intrinsic)|Image|
|v.8.13 - Hydronephrosis|Image|
|v.8.13.1 - If Hydronephrosis 'yes', where|Image|
|v.8.11 - Right ovary|Image|
|v.8.11.1 - Right ovary - Superficial|Image|
|v.8.11.2 - Right ovary - Endometrioma|Image|
|v.8.11.2.1 - If right ovary 'Endometrioma', larger diameter|Image|
|v.8.11.3 - Right ovary - Another cyst|Image|
|v.8.11.3.1 - If Right ovary 'Another cyst', which|Image|
|v.8.12 - Left ovary|Image|
|v.8.12.1 - Left ovary - Superficial|Image|
|v.8.12.2 - Left ovary - Endometrioma|Image|
|v.8.12.2.1 - If left ovary 'Endometrioma', larger diameter|Image|
|v.8.12.3 - Left ovary - Another cyst|Image|
|v.8.12.3.1 - If Left Ovary 'Another Cyst', which|Image|
|v.8.14 - Right Tubas|Image|
|v.8.15 - Left Tubas|Image|
|v.8.16 - Right Hydrosalpinx|Image|
|v.8.17 - Left Hydrosalpinx|Image|
|v.8.18 - Right Hematosalpinx|Image|
|v.8.19 - Left Hematosalpinx|Image|
|v.8.22 - Uterus Volume|Image|
|v.8.23 - Uterine Endometrial Echo|Image|
|v.8.26 - Presence of adenomyosis?|Image|
|v.8.26.1 - Junctional Zone Thickness, in adenomyosis|Image|
|v.8.26.2 - Location of Adenomyosis|Image|
|v.8.27 - Is there the presence of fibroids?|Image|
|v.8.27.1 - How Many Fibroids|Image|
|v.8.27.2 - What is the largest extension of the largest fibroid|Image|
|v.8.28 - There is the presence of Endometrial Polypus|Image|
|v.8.29 - Other MRI findings|Image|
|v.8.30 - Upload Resonance exam|Image|
|v.2.22.0 - Vaginal touch (Description)|Clinical data|
|v.2.22.1 - Vaginal touch|Clinical data|
|v.2.22.1.1 - Palpable nodule size|Clinical data|
|v.2.22.4.1 - If adnexal increase, which side|Clinical data|
|v.4.2 - Surgical Team - Number of Doctors|Intraoperative|
|v.4.2.1 - Surgical Team - Doctor 1|Intraoperative|
|v.4.2.2 - Surgical Team - Doctor 2|Intraoperative|
|v.4.2.3 - Surgical Team - Doctor 3|Intraoperative|
|v.4.2.4 - Surgical Team - Doctor 4|Intraoperative|
|v.4.2.5 - Surgical Team - Doctor 5|Intraoperative|
|v.4.2.6 - Surgical Team - Doctor 6|Intraoperative|
|v.4.3 - Surgery Performed|Intraoperative|
|v.4.4 - Date of last menstruation|Clinical data|
|v.4.5 - Menstrual Cycle Day|Clinical data|
|v.4.6 - Mirena|Intraoperative|
|v.4.7 - Hysteroscopy|Intraoperative|
|v.4.7.1 - Which Hysteroscopy?|Intraoperative|
|v.4.7.2 - Endometry|Intraoperative|
|v.4.7.2.1 - Endometrium - Others|Intraoperative|
|v.4.35 - Hysterectomy Performed|Intraoperative|
|v.4.35.1 - If hysterectomy is performed, what type?|Intraoperative|
|v.4.10 - Right ovary|Intraoperative|
|v.4.10.2 - Right ovary - Superficial|Intraoperative|
|v.4.10.1 - Right ovary - Endometrioma|Intraoperative|
|v.4.10.1.1 - If Right Ovary 'Endometrioma', size|Intraoperative|
|v.4.10.3 - Right ovary - Another cyst|Intraoperative|
|v.4.10.3.1 - If Right Ovary 'Another Cyst', which|Intraoperative|
|v.4.11 - Left ovary|Intraoperative|
|v.4.11.2 - Left Ovary - Superficial|Intraoperative|
|v.4.11.1.1 - If Left Ovary 'Endometrioma', size|Intraoperative|
|v.4.11.3 - Left ovary - Another cyst|Intraoperative|
|v.4.11.3.1 - If Left Ovary 'Another Cyst', which|Intraoperative|
|v.4.12 - Bladder (Muscular)|Intraoperative|
|v.4.12.1.2 - If Muscle Bladder, size|Intraoperative|
|v.4.13 - Right Ureter (intrinsic)|Intraoperative|
|v.4.14 - Left Ureter (intrinsic)|Intraoperative|
|v.4.15 - Hydronephrosis|Intraoperative|
|v.4.16.1 - If Retrocervical (LUS), size|Intraoperative|
|v.4.17 - Rectovaginal Septum|Intraoperative|
|v.4.17.1 - If Rectovaginal Septum, size|Intraoperative|
|v.4.18 - Vagina (Muscular)|Intraoperative|
|v.4.18.1 - If Vagina (Muscular), size|Intraoperative|
|v.4.19.1.3 - Rectosigmoid, lesion size 2|Intraoperative|
|v.4.19.1.4 - Rectosigmoid, distance from the anal edge of the lesion 2|Intraoperative|
|v.4.19.1.5 - Rectosigmoid, lesion size 3|Intraoperative|
|v.4.19.1.6 - Rectosigmoid, distance from the anal edge of the lesion 3|Intraoperative|
|v.4.21 - Ileo/Slender|Intraoperative|
|v.4.20 - Appendix|Intraoperative|
|v.4.22 - Cecum|Intraoperative|
|v.4.23 - Right Tubas|Intraoperative|
|v.4.23.1 - Right Tuba - Mild Serous Injury|Intraoperative|
|v.4.23.2 - Right Tuba - Moderate Serous Injury / Moderate Immobility|Intraoperative|
|v.4.23.3 - Right Tuba - Severe Immobility|Intraoperative|
|v.4.23.4 - Right Tuba - Complete Obstruction|Intraoperative|
|v.4.24 - Left Tuba|Intraoperative|
|v.4.24.1 - Left Tuba - Mild Serous Injury|Intraoperative|
|v.4.24.2 - Left Tuba - Moderate Serous Injury / Moderate Immobility|Intraoperative|
|v.4.24.3 - Left Tuba - Severe Immobility|Intraoperative|
|v.4.24.4 - Left Tuba - Complete Obstruction|Intraoperative|
|v.4.25 - Right Pararectal|Intraoperative|
|v.4.25.1 - Right pararectal se|Intraoperative|
|v.4.26 - Left Pararectal|Intraoperative|
|v.4.26.1 - Left pararectal|Intraoperative|
|v.4.27 - Round Ligament|Intraoperative|
|v.4.27.1 - Round Ligament, which|Intraoperative|
|v.4.28 - EDT abdominal wall|Intraoperative|
|v.4.28.1 - If EDT abdominal wall|Intraoperative|
|v.4.29 - Fibroids|Intraoperative|
|v.4.29.1 - Fibroids, larger fibroid size|Intraoperative|
|v.4.30 - Adenomyosis|Intraoperative|
|v.4.31 - Chromotubing|Intraoperative|
|v.4.31.1 - Right Chromotubing|Intraoperative|
|v.4.31.2 - Left Chromotubing|Intraoperative|
|v.4.32 - Resection of all visible foci|Intraoperative|
|v.4.32.1 - Extra-pelvic sites|Intraoperative|
|v.4.32.1.1 - If extra-pelvic sites Other, which|Intraoperative|
|v.4.33.1 - Reported complications - Surgical Site Infection|Intraoperative|
|v.4.33.2 - Reported complications - Hemorrhage|Intraoperative|
|v.4.33.3 - Reported complications - Post-operative fever|Intraoperative|
|v.4.33.4 - Reported complications - Fistula / Dehiscence|Intraoperative|
|v.4.33.5 - Reported complications - Pseudomembranous Colitis|Intraoperative|
|v.4.33.6 - Reported complications - Others|Intraoperative|
|v.4.33.6.1 - If Other complications, what|Intraoperative|
|Upload Laparoscopy exam|Intraoperative|
|v.6.1 - Superficial Peritoneal|Intraoperative|
|v.6.2 - Retrocervical|Intraoperative|
|v.6.3 - Vagina (Muscular)|Intraoperative|
|v.6.4 - Bladder|Intraoperative|
|v.6.5 - Rectovaginal Septum|Intraoperative|
|v.6.6 - Straight|Intraoperative|
|v.6.7 - Sigmoid|Intraoperative|
|v.6.6 - Straight and v.6.7 - Sigmoid|Intraoperative|
|v.6.8 - Small Intestine|Intraoperative|
|v.6.16 - Appendix|Intraoperative|
|v.6.9 - Right Ovary|Intraoperative|
|v.6.10 - Left Ovary|Intraoperative|
|v.6.11 - Ureter|Intraoperative|
|v.6.12 - Obstruction of the Bottom of the Sac|Intraoperative|
|v.6.13 - Condition of the Left Fallopian Tube|Intraoperative|
|v.6.14 - Condition of the Right Fallopian Tube|Intraoperative|
|AAGL Score|Intraoperative|
|v.9.3.3 - Peritoneum - Well Differentiated|Postoperative|
|v.9.3.4 - Peritoneum - Undifferentiated|Postoperative|
|v.9.18 - Vagina Anatomopathological Result|Postoperative|
|v.9.18.1 - Vagina Result - Endometriosis not classified|Postoperative|
|v.9.18.2 - Vagina Result - Stromal|Postoperative|
|v.9.18.3 - Vagina Result - Well Differentiated|Postoperative|
|v.9.18.4 - Vagina Result - Undifferentiated|Postoperative|
|v.9.18.5 - Vagina Result - Mixed|Postoperative|
|v.9.14.1.2.1 - Lesion 2 - Rectum / Sigmoid Result - Endometriosis not classified|Postoperative|
|v.9.14.1.2.2 - Injury 2 - Result of Rectum / Sigmoid - Stromal|Postoperative|
|v.9.14.1.2.3 - Injury 2 - Rectum / Sigmoid Result - Well Differentiated|Postoperative|
|v.9.14.1.2.4 - Injury 2 - Result of the Rectum / Sigmoid - Undifferentiated|Postoperative|
|v.9.14.1.2.5 - Injury 2 - Rectum / Sigmoid Result - Mixed|Postoperative|
|v.9.14.1.3.1 - Lesion 3 - Rectum / Sigmoid Result - Endometriosis not classified|Postoperative|
|v.9.14.1.3.2 - Injury 3 - Result of Rectum / Sigmoid - Stromal|Postoperative|
|v.9.14.1.3.3 - Injury 3 - Rectum / Sigmoid Result - Well Differentiated|Postoperative|
|v.9.14.1.3.4 - Injury 3 - Rectum / Sigmoid Result - Undifferentiated|Postoperative|
|v.9.14.1.3.5 - Injury 3 - Rectum / Sigmoid Result - Mixed|Postoperative|
|v.9.14.1.4.1 - Lesion 4 - Rectum / Sigmoid Result - Endometriosis not classified|Postoperative|
|v.9.14.1.4.2 - Injury 4 - Result of Rectum / Sigmoid - Stromal|Postoperative|
|v.9.14.1.4.3 - Injury 4 - Rectum / Sigmoid Result - Well Differentiated|Postoperative|
|v.9.14.1.4.4 - Injury 4 - Rectum / Sigmoid Result - Undifferentiated|Postoperative|
|v.9.14.1.4.5 - Injury 4 - Rectum / Sigmoid Result - Mixed|Postoperative|
|v.9.12 - Appendix Anatomopathological Result|Postoperative|
|v.9.12.1 - Appendix Result - Endometriosis not classified|Postoperative|
|v.9.12.2 - Appendix Result - Stromal|Postoperative|
|v.9.12.3 - Appendix Result - Well Differentiated|Postoperative|
|v.9.12.4 - Appendix Result - Undifferentiated|Postoperative|
|v.9.12.5 - Appendix Result - Mixed|Postoperative|
|v.9.13 - Anatomopathological Result of ILEO/Delgado|Postoperative|
|v.9.13.1 - ILEO/Delgado result - Endometriosis not classified|Postoperative|
|v.9.13.2 - ILEO/Delgado Result - Estromal|Postoperative|
|v.9.13.3 - ILEO/Delgado Result - Well Differentiated|Postoperative|
|v.9.13.4 - ILEO/Delgado Result - Undifferentiated|Postoperative|
|v.9.13.5 - ILEO/Delgado Result - Mixed|Postoperative|
|v.9.23 - CECO Result|Postoperative|
|v.9.23.1 - CECO Result - Endometriosis not classified|Postoperative|
|v.9.23.2 - CECO Result - Estromal|Postoperative|
|v.9.23.3 - CECO Result - Well Differentiated|Postoperative|
|v.9.23.4 - CECO Result - Undifferentiated|Postoperative|
|v.9.23.5 - CECO Result - Mixed|Postoperative|
|v.9.9 - Anatomopathological Result of the Bladder (muscular)|Postoperative|
|v.9.9.1 - Bladder Result - Endometriosis not classified|Postoperative|
|v.9.9.2 - Bladder Result - Stromal|Postoperative|
|v.9.9.3 - Bladder Result - Well Differentiated|Postoperative|
|v.9.9.4 - Bladder Result - Undifferentiated|Postoperative|
|v.9.9.5 - Bladder Result - Mixed|Postoperative|
|v.9.10 - Ureter Anatomopathological Result|Postoperative|
|v.9.10.1 - Ureter Result - Endometriosis not classified|Postoperative|
|v.9.10.2 - Ureter - Stromal Result|Postoperative|
|v.9.10.3 - Ureter Result - Well differentiated|Postoperative|
|v.9.10.4 - Ureter Result - Undifferentiated|Postoperative|
|v.9.10.5 - Ureter Result - Mixed|Postoperative|
|v.9.4 - Anatomopathological Result of the Right Ovary|Postoperative|
|v.9.4.1 - Right Ovary Result - Endometriosis not classified|Postoperative|
|v.9.4.2 - Right Ovary Result - Stromal|Postoperative|
|v.9.4.3 - Right Ovary Result - Well Differentiated|Postoperative|
|v.9.4.4 - Right Ovary Result - Undifferentiated|Postoperative|
|v.9.4.5 - Right Ovary Result - Mixed|Postoperative|
|v.9.5.1 - Right Ovary Classification - Endometriosis not classified|Postoperative|
|v.9.5.2 - Right Ovary Classification - Cystic|Postoperative|
|v.9.5.3 - Right Ovary Classification - Intraparenchymal|Postoperative|
|v.9.5.4 - Right Ovary Classification - Superficial|Postoperative|
|v.9.6 - Anatomopathological Result of the Left Ovary|Postoperative|
|v.9.6.1 - Left Ovary Result - Endometriosis not classified|Postoperative|
|v.9.6.2 - Left Ovary Result - Stromal|Postoperative|
|v.9.6.3 - Left Ovary Result - Well Differentiated|Postoperative|
|v.9.6.4 - Left Ovary Result - Undifferentiated|Postoperative|
|v.9.6.5 - Left Ovary Result - Mixed|Postoperative|
|v.9.7.1 - Left Ovary Classification - Endometriosis not classified|Postoperative|
|v.9.7.2 - Left Ovary Classification - Cystic|Postoperative|
|v.9.7.3 - Left Ovary Classification - Intraparenchymal|Postoperative|
|v.9.7.4 - Left Ovary Classification - Superficial|Postoperative|
|v.9.19 - Anatomopathological Result of the Right Tuba|Postoperative|
|v.9.19.1 - Right Tube Result - Endometriosis not classified|Postoperative|
|v.9.19.2 - Right Tuba Result - Stromal|Postoperative|
|v.9.19.3 - Result of the Right Tuba - Well differentiated|Postoperative|
|v.9.19.4 - Right Tuba Result - Undifferentiated|Postoperative|
|v.9.19.5 - Right Tuba Result - Mixed|Postoperative|
|v.9.20 - Anatomopathological Result of the Left Tuba|Postoperative|
|v.9.20.1 - Left Tube Result - Endometriosis not classified|Postoperative|
|v.9.20.2 - Left Tuba Result - Stromal|Postoperative|
|v.9.20.3 - Left Tuba Result - Well Differentiated|Postoperative|
|v.9.20.4 - Left Tuba Result - Indifference|Postoperative|
|v.9.20.5 - Left Tuba Result - Mixed|Postoperative|
|v.9.21 - Uterine Anatomopathological Result|Postoperative|
|v.9.21.1 - Uterine Result - Normal|Postoperative|
|v.9.21.2 - Uterine Result - Endometrial Polyp|Postoperative|
|v.9.21.3 - Uterine Result - Myoma|Postoperative|
|v.9.21.4 - Uterine Result - Adenomyosis|Postoperative|
|v.9.21.5 - Uterine Result - others|Postoperative|
|v.9.21.5.1 - Uterine Pathology Result, if others:|Postoperative|
|v.9.22 - Anatomopathological Result on the Abdominal Wall|Postoperative|
|v.9.22.1 - Abdominal Wall - Endometriosis not classified|Postoperative|
|v.9.22.2 - Abdominal Wall - Stromal|Postoperative|
|v.9.22.3 - Abdominal Wall - Well Differentiated|Postoperative|
|v.9.22.4 - Abdominal Wall - Undifferentiated|Postoperative|
|v.9.22.5 - Abdominal Wall - Mixed|Postoperative|
|v.9.17 - Anatomopathological Upload|Postoperative|
