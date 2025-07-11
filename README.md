# University Honours Degree Applications Analysis

### Dataset: 
- 14 Excel sheets of honours degree student application records from a local university merged into one dataset
- Contains fields like Name, Surname, Gender, Course Applied for, etc.
- Cleaned in Excel and Python

### Tools Used: 
- Excel
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebooks

### Objectives: 
- Clean and prepare data in Excel for further analysis in Python
- Determine gender distribution across applicants
- Discover most and least applied courses
- Classify course popularrity (Popularity, Moderate, Niche)

### Key Visuals

#### Gender Distribution
The chart below shows us that there more females who applied for honours degree courses thant those who didn't

<img width="1890" height="1406" alt="gender_distribution" src="https://github.com/user-attachments/assets/0b28e71f-685a-4e2a-a227-8aba1ce7a2db" />

#### Course Preference by Gender

The heat map below shows us which courses are popular amongst the different genders.
For example, we see that the most popular course amongst male applicants is BSc in Information Technology while females applied for Human Resource Management the most.

<img width="2993" height="3566" alt="preference_by_gender" src="https://github.com/user-attachments/assets/76e50ef2-27e3-4a97-acfe-a3e7a0c4a1dd" />

#### Popular Courses

The chart below shows us which courses were the most popular amongst applicants this year
BSc(HONS) in Information Technology, BBUS(HONS) in International Business and BA(HONS)Human Resource Management were the top 3 popular courses in this particular year.

<img width="2374" height="2966" alt="popular_courses" src="https://github.com/user-attachments/assets/a84b5dac-b251-4689-8e21-a0fce0a2dc4f" />

#### Least Popular Courses

The chart below shows the least popular courses amongst applicants on this particular year
BA (HONS) in Digital Film & Television, BSc(HONS) in Business Information Technology and B DES(HONS) in Professional Design

<img width="2374" height="1466" alt="least_popular_courses" src="https://github.com/user-attachments/assets/2aaec1b2-3fff-48bd-b0b8-1798c1e90192" />

#### Gender Distribution Per Applied Course

The chart below shows the rate of course application per gender.
- The chart shows us that IT and Design courses were more popular amongst males than they were amongst females
- However Business and Communication courses were more popular amongst females than they were amongst males

<img width="3564" height="1769" alt="gender_distribution_per_applied_course" src="https://github.com/user-attachments/assets/e9cc852c-c525-469d-865c-8b8ea1c153d1" />

#### Applications by Course Category

The chart below is  avisual representation on the numbers we got when sorting out the applications to see which ones were the `Most Popular`, `Moderate` and `Niche`

<img width="406" height="242" alt="course_category" src="https://github.com/user-attachments/assets/1d15a28d-ed91-4a1a-ae84-4e050e229252" />


<img width="1770" height="1165" alt="course_category_distribution" src="https://github.com/user-attachments/assets/003a7ecb-4b38-4bad-b846-edecfa6d1f81" />

#### Gaps in Data

The image below outlines the irregularities in the data we received - particularly missing data
- ID, Contacts and Receipt NO were missing because students did not submit details on these
- Second Option is the course that each student is willing to study incase they don't make it into their first option. Sometimes, students who apply for Honours Degrees had previously studied for Associate Degrees in this University but then come back to upgrade to higher qualification, that means they usually don't have or need second options when applying.

<img width="401" height="296" alt="gaps_in_data" src="https://github.com/user-attachments/assets/75f980a3-d58f-4e86-afd3-a055ee0b3e67" />

### Recommendations 
- The University either needs to stregthen their marketing efforts for courses like Digital Film & Television, Professional Design and Business Information Technology or discontinue said course.
- Seeing the rise of efforts made towards empowering women in STEM globally, the universty would benefit a lot by offering course couselling & strengthning their marketing efforts to prospective female applicants for tech & design courses.
- Design and Communication courses have the least applications not because students are not interested in them but mainly because thye are niche in the country and prospective students don't know about them or aren't familiar with the career paths they can follow after gaining these qualifications. The university can therefore strengthen their marketing efforts for these courses by posting content that explores the dynamics of these courses on their social media platforms for students to interact with.

### Challenges

- I started working on this project in Python before first merging the sheets and cleaning the data in Excel. While learning how to merge sheets in excel was eye-opening it was very challenging because at the end of the project i had lost a lot of data. I was expecting 1004 entries but only had 100. I redid the project in excel first and then migrated to Python which was smooth sailing.
- Missing data corrupted my file when i tried working on this project in Python before cleaning it up in Excel first which made it very challenging. Everything was much easier after I did basic cleaning in Excel.   

### Future Work
- Analyze second option data
- Build a dashboard using Tableau or Power BI
