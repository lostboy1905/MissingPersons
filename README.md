# Missing Persons
 Group project for IS 303
Project 2 - Group
The project will focus more on the design aspect of the course using the different HTML tools and forms and Python Views. 
There is no limit or requirement as to the number of pages that need to be created. You do NOT have to implement database yet. That will be done in Project 3 as a group.
However, you will need to display provided JSON data on one of the pages as an HTML table. Use the following link https://www.convertjson.com/json-to-html-table.htm to convert the JSON data to the HTML table. You can modify the table using Bootstrap to make it look more professional.
The goal of this project is for you to design and implement a website that will help the BYU community learn about and engage with combatting human trafficking.
Here are some websites that can provide more context:
•	https://attorneygeneral.utah.gov/initiatives/human-trafficking/ 
•	https://www.rideuta.com/news/2021/01/Human-Trafficking#:~:text=BE%20THE%20ONE%20to%20SUPPORT%20victims%20of%20human%20trafficking.&text=victims%20to%20services%3A-,Contact%20the%20National%20Human%20Trafficking%20Hotline%20at%20888%2D373%2D7888,%40aau%2Dslc.org%20. 
•	https://www.acf.hhs.gov/sites/default/files/documents/otip/utah_profile_efforts_to_combat_human_trafficking.pdf 
•	https://www.deseret.com/utah/2021/10/8/22716453/aspen-house-utah-human-trafficking-recovery-center-kicks-off-fundraising-efforts-salt-lake-city 
•	https://humantraffickinghotline.org/state/utah 
•	https://sharedhope.org/PICframe7/reportcards/PIC_RC_2017_UT.pdf 
•	https://sharedhope.org/PICframe7/analysis/PIC_AR_2017_UT.pdf 
•	https://www.ctdatacollaborative.org/story/age-victims-children-and-adults 
I would suggest visiting these sites first and reading out the efforts taking place to combat human trafficking. You can use this information (and images) to help your website also inform.
JSON Data: Over 50% of identified girl victims are aged between 15 and 17 while about 40% of trafficked boys are under 12 years of age. Although every person, no matter age, it important, this project will only use those statistics for providing JSON data Missing Persons Cases Found ages 0 to 27 in the state of Utah.
Here is the JSON data to use in your project that will need to be displayed. You can choose how to display it. Copy this code, including the opening and closing braces and brackets, and paste it into the link supplied to perform the conversion to an HTML table https://www.convertjson.com/json-to-html-table.htm
[
                        {
                            "date_missing": "10/30/2009",
                            "last_name": "Sharmarice",
                            "first_name": "Halima",
                            "age_at_missing": "14",
                            "city": "Granger",
                            "state": "UT",
                            "gender": "F",
                            "race": "W"
                        },

                        {
                            "date_missing": "10/16/2015",
                            "last_name": "Martinez",
                            "first_name": "Kimberly",
                            "age_at_missing": "16",
                            "city": "West Valley City",
                            "state": "UT",
                            "gender": "F",
                            "race": "M"
                        },

                        {
                            "date_missing": "07/23/2004",
                            "last_name": "Gomez",
                            "first_name": "Brenda",
                            "age_at_missing": "3",
                            "city": "Logan",
                            "state": "UT",
                            "gender": "F",
                            "race": "H"
                        },

                        {
                            "date_missing": "05/25/2003",
                            "last_name": "Bishop",
                            "first_name": "Acacia",
                            "age_at_missing": "1",
                            "city": "Salt Lake City",
                            "state": "UT",
                            "gender": "F",
                            "race": "W"
                        },

                        {
                            "date_missing": "08/03/2020",
                            "last_name": "Salazar",
                            "first_name": "Maria",
                            "age_at_missing": "14",
                            "city": "Snowville",
                            "state": "UT",
                            "gender": "F",
                            "race": "H"
                        },

                        {
                            "date_missing": "04/09/2020",
                            "last_name": "Hernandez-Soto",
                            "first_name": "Peggy",
                            "age_at_missing": "6",
                            "city": "Ogden",
                            "state": "UT",
                            "gender": "F",
                            "race": "H"
                        },

                        {
                            "date_missing": "06/24/2021",
                            "last_name": "Jimenez",
                            "first_name": "Lucero",
                            "age_at_missing": "14",
                            "city": "West Valley City",
                            "state": "UT",
                            "gender": "F",
                            "race": "H"
                        },

                        {
                            "date_missing": "11/08/2013",
                            "last_name": "Colindres-Avila",
                            "first_name": "Yuris",
                            "age_at_missing": "17",
                            "city": "West Valley City",
                            "state": "UT",
                            "gender": "F",
                            "race": "M"
                        },

                        {
                            "date_missing": "07/15/2021",
                            "last_name": "Harris",
                            "first_name": "Kandis",
                            "age_at_missing": "16",
                            "city": "Salt Lake City",
                            "state": "UT",
                            "gender": "F",
                            "race": "W"
                        },

                        {
                            "date_missing": "07/30/2006",
                            "last_name": "Seal",
                            "first_name": "Jaydan",
                            "age_at_missing": "1",
                            "city": "Garleys Wash",
                            "state": "UT",
                            "gender": "M",
                            "race": "W"
                        },

                        {
                            "date_missing": "06/13/2018",
                            "last_name": "Lizarraga",
                            "first_name": "Jose",
                            "age_at_missing": "13",
                            "city": "West Valley City",
                            "state": "UT",
                            "gender": "M",
                            "race": "H"
                        },

                        {
                            "date_missing": "04/23/2020",
                            "last_name": "Cortez Trujillo",
                            "first_name": "Eztli",
                            "age_at_missing": "21",
                            "city": "North Ogden",
                            "state": "UT",
                            "gender": "M",
                            "race": "H"
                        },

                        {
                            "date_missing": "10/25/2017",
                            "last_name": "Fowles",
                            "first_name": "Juan",
                            "age_at_missing": "15",
                            "city": "Lehi",
                            "state": "UT",
                            "gender": "M",
                            "race": "M"
                        },

                        {
                            "date_missing": "08/20/2012",
                            "last_name": "Garcia",
                            "first_name": "Isai",
                            "age_at_missing": "17",
                            "city": "West Valley City",
                            "state": "UT",
                            "gender": "M",
                            "race": "M"
                        },

                        {
                            "date_missing": "09/01/2015",
                            "last_name": "Smith",
                            "first_name": "Macin",
                            "age_at_missing": "17",
                            "city": "St. George",
                            "state": "UT",
                            "gender": "M",
                            "race": "W"
                        },

                        {
                            "date_missing": "01/26/2006",
                            "last_name": "Sisco-Ramirez",
                            "first_name": "Jose",
                            "age_at_missing": "4",
                            "city": "West Valley City",
                            "state": "UT",
                            "gender": "M",
                            "race": "M"
                        }
                        ] 
For this project you must have at least one landing web page displaying the JSON data. Your website will also be evaluated for its effectiveness in generating interest in combatting human trafficking, and fulfilling user needs such that they want to continue to visit and interact with your website. Potential users outside of class will help us evaluate this aspect. You will want to have more than just the data on this page. You want this site to be informative. You can have multiple pages if you feel it will help inform the community as to the problem we are trying to help solve.
As with all IT projects, talking with potential users you know can help. The TAs can help answer questions, but they cannot pre-grade the site and provide comments such as "Yes, that is a good site" or "You are doing everything correctly", etc. 
You are welcome to use Bootstrap to make the design easier. Here are some videos that can help if you want to incorporate bootstrap to make your design easier to implement and make it look more professional. However, Bootstrap is not required.
•	Bootstrap 5 Tutorial Lesson 1 https://www.youtube.com/watch?v=O_9u1P5YjVc 
•	Bootstrap 5 Tutorial Lesson 2 https://www.youtube.com/watch?v=YQRmczOYIG0 
•	Bootstrap 5 Tutorial Lesson 3 https://www.youtube.com/watch?v=iUCyU_U0J2E 
•	Bootstrap 5 Tutorial Lesson 4 https://www.youtube.com/watch?v=ZZXGmoQ4PdI 
Good luck and make sure you work hard on this.
Please keep track of the "honest" number of hours you spend working on this project and the entire group.
