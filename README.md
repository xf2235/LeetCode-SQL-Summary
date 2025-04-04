LeetCode SQL Summary
Last updated on August 8, 2021, covered 106 LeetCode SQL questions

WIP

Update new SQL questions (Estimated Time: 31 August, 2021)
Rearrange the repository (Estimated Time: 25 September, 2021 - My Brithday :D)
Only one solution folder will be kept
Update solution link
Add Column "Topic" for LeetCode SQL Questions by ID
Intro
After finishing all 102 LeetCode SQL questions, I feel it could be good to summarize all questions by topics.

This note aims to help people learn and review SQL effeciently, espeically when trying to have a quick catch up on a certain topic, e.g. complex join, window function, recursive CTE and etc. If you would like to try questions by ID, you could jump to LeetCode SQL Questions by ID where I list all questions coverred in this repository.

And for the first draft, I mainly focus on T-SQL/MS SQL Server.

Table of Content
LeetCode SQL Questions by Topcis
Basics
SQL Command
Join
Subquery
Window Function
CASE WHEN / IIF
OFFSET FETCH
PIVOT & UNPIVOT
Variable
LeetCode SQL Questions by ID
LeetCode SQL Questions by Topics
Basics
#	Title	Difficulty	Solution
182	Duplicate Emails	Easy	Soln.
511	Game Play Analysis I	Easy	Soln.
578	Get Highest Answer Rate Question	Medium	Soln.
584	Find Customer Referee	Easy	Soln.
586	Customer Placing the Largest Number of Orders	Easy	Soln.
595	Big Countries	Easy	Soln.
596	Classes More Than 5 Students	Easy	Soln.
619	Biggest Single Number	Easy	Soln.
620	Not Boring Movies	Easy	Soln.
1050	Actors and Directors Who Cooperated At Least Three Times	Easy	Soln.
1069	Product Sales Analysis II	Easy	Soln.
1076	Project Employees II	Easy	Soln.
1082	Sales Analysis I 	Easy	Soln.
1141	User Activity for the Past 30 Days I	Easy	Soln.
1148	Article Views I	Easy	Soln.
1149	Article Views II	Medium	Soln.
SQL Command
#	Title	Difficulty	Solution
196	Delete Duplicate Emails	Easy	Soln.
627	Swap Salary	Easy	Soln.
Join
Simple Join
#	Title	Difficulty	Solution
175	Combine Two Tables	Easy	Soln.
181	Employees Earning More Than Their Managers	Easy	Soln.
183	Customers Who Never Order	Easy	Soln.
184	Department Highest Salary	Medium	Soln.
197	Rising Temperature	Easy	Soln.
262	Trips and Users 	Hard	Soln.
512	Game Play Analysis II	Easy	Soln.
550	Game Play Analysis IV	Medium	Soln.
570	Managers with at Least 5 Direct Reports	Medium	Soln.
574	Winning Candidate	Medium	Soln.
577	Employee Bonus	Easy	Soln.
580	Count Student Number in Departments	Medium	Soln.
607	Sales Person	Easy	Soln.
614	Second Degree Follower	Medium	Soln.
615	Average Salary: Departments VS Company	Hard	Soln.
1068	Product Sales Analysis I	Easy	Soln.
1070	Product Sales Analysis III	Medium	Soln.
1075	Project Employees I	Easy	Soln.
1077	Project Employees II	Medium	Soln.
1083	Sales Analysis I 	Easy	Soln.
1112	Highest Grade For Each Student	Medium	Soln.
1132	Reported Posts II	Medium	Soln.
1158	Market Analysis I	Medium	Soln.
1164	Product Price at a Given Date	Medium	Soln.
1204	Last Person to Fit in the Elevator	Medium	Soln.
1205	Monthly Transactions II	Medium	Soln.
1241	Number of Comments per Post	Easy	Soln.
1270	All People Report to the Given Manager	Medium	Soln.
1280	Students and Examinations	Easy	Soln.
1294	Weather Type in Each Country	Easy	Soln.
1303	Find the Team Size	Easy	Soln.
1327	List the Products Ordered in a Period	Easy	Soln.
1336	Number of Transactions per Visit	Hard	Soln.
1350	Students With Invalid Departments	Easy	Soln.
1364	Number of Trusted Contacts of a Customer	Medium	Soln.
1378	Replace Employee ID With The Unique Identifier	Easy	Soln.
1384	Total Sales Amount by Year	Hard	Soln.
1407	Top Travellers	Easy	Soln.
Advanced Join
#	Title	Difficulty	Solution
180	Consecutive Numbers	Medium	Soln.
196	Delete Duplicate Emails	Easy	Soln.
534	Game Play Analysis III	Medium	Soln.
569	Median Employee Salary	Hard	Soln.
579	Find Cumulative Salary of an Employee	Hard	Soln.
601	Human Traffic of Stadium	Hard	Soln.
603	Consecutive Available Seats	Easy	Soln.
612	Shortest Distance in a Plane	Medium	Soln.
613	Shortest Distance in a Line 	Easy	Soln.
1097	Game Play Analysis V	Hard	Soln.
1126	Active Businesses	Medium	Soln.
1127	User Purchase Platform	Hard	Soln.
1159	Market Analysis II	Medium	Soln.
1194	Tournament Winners	Hard	Soln.
1212	Team Scores in Football Tournament	Medium	Soln.
1225	Report Contiguous Dates	Hard	Soln.
1251	Average Selling Price	Easy	Soln.
1285	Find the Start and End Number of Continuous Ranges	Medium	Soln.
1308	Running Total for Different Genders	Medium	Soln.
1321	Restaurant Growth	Medium	Soln.
1369	Get the Second Most Recent Activity	Hard	Soln.
Subquery
Simple Subquery
#	Title	Difficulty	Solution
176	Second Highest Salary	Easy	Soln.
183	Customers Who Never Order	Easy	Soln.
184	Department Highest Salary	Medium	Soln.
196	Delete Duplicate Emails	Easy	Soln.
197	Rising Temperature	Easy	Soln.
512	Game Play Analysis II	Easy	Soln.
569	Median Employee Salary	Hard	Soln.
570	Managers with at Least 5 Direct Reports	Medium	Soln.
571	Find Median Given Frequency of Numbers 	Hard	Soln.
574	Winning Candidate	Medium	Soln.
579	Find Cumulative Salary of an Employee	Hard	Soln.
580	Count Student Number in Departments	Medium	Soln.
602	Friend Requests II: Who Has the Most Friends	Medium	Soln.
603	Consecutive Available Seats	Easy	Soln.
607	Sales Person	Easy	Soln.
608	Tree Node	Medium	Soln.
613	Shortest Distance in a Line 	Easy	Soln.
614	Second Degree Follower	Medium	Soln.
615	Average Salary: Departments VS Company	Hard	Soln.
618	Students Report By Geography	Hard	Soln.
626	Exchange Seats	Medium	Soln.
1045	Customers Who Bought All Products	Medium	Soln.
1070	Product Sales Analysis III	Medium	Soln.
1083	Sales Analysis I 	Easy	Soln.
1084	Sales Analysis I 	Easy	Soln.
1097	Game Play Analysis V	Hard	Soln.
1098	Unpopular Books	Medium	Soln.
1107	New Users Daily Count	Medium	Soln.
1112	Highest Grade For Each Student	Medium	Soln.
1126	Active Businesses	Medium	Soln.
1132	Reported Posts II	Medium	Soln.
1142	User Activity for the Past 30 Days II	Easy	Soln.
1158	Market Analysis I	Medium	Soln.
1174	Immediate Food Delivery II	Medium	Soln.
1204	Last Person to Fit in the Elevator	Medium	Soln.
1225	Report Contiguous Dates	Hard	Soln.
1264	Page Recommendations	Medium	Soln.
1280	Students and Examinations	Easy	Soln.
1285	Find the Start and End Number of Continuous Ranges	Medium	Soln.
1294	Weather Type in Each Country	Easy	Soln.
1321	Restaurant Growth	Medium	Soln.
1322	Ads Performance	Easy	Soln.
1336	Number of Transactions per Visit	Hard	Soln.
1341	Movie Rating	Medium	Soln.
1350	Students With Invalid Departments	Easy	Soln.
1355	Activity Participants	Medium	Soln.
1364	Number of Trusted Contacts of a Customer	Medium	Soln.
1369	Get the Second Most Recent Activity	Hard	Soln.
Advanced Subquery
#	Title	Difficulty	Solution
262	Trips and Users 	Hard	Soln.
550	Game Play Analysis IV	Medium	Soln.
569	Median Employee Salary	Hard	Soln.
585	Investments in 2016	Medium	Soln.
597	Friend Requests I: Overall Acceptance Rate	Easy	Soln.
601	Human Traffic of Stadium	Hard	Soln.
1077	Project Employees II	Medium	Soln.
1127	User Purchase Platform	Hard	Soln.
1159	Market Analysis II	Medium	Soln.
1164	Product Price at a Given Date	Medium	Soln.
1194	Tournament Winners	Hard	Soln.
1205	Monthly Transactions II	Medium	Soln.
1270	All People Report to the Given Manager	Medium	Soln.
1398	Customers Who Bought Products A and B but Not C	Medium	Soln.
Recursive CTE
#	Title	Difficulty	Solution
1270	All People Report to the Given Manager	Medium	Soln.
1336	Number of Transactions per Visit	Hard	Soln.
1384	Total Sales Amount by Year	Hard	Soln.
Window Function
#	Title	Difficulty	Solution
176	Second Highest Salary	Easy	Soln.
177	Nth Highest Salary	Medium	Soln.
178	Rank Scores	Medium	Soln.
180	Consecutive Numbers	Medium	Soln.
184	Department Highest Salary	Medium	Soln.
185	Department Top Three Salaries	Hard	Soln.
197	Rising Temperature	Easy	Soln.
512	Game Play Analysis II	Easy	Soln.
534	Game Play Analysis III	Medium	Soln.
550	Game Play Analysis IV	Medium	Soln.
569	Median Employee Salary	Hard	Soln.
571	Find Median Given Frequency of Numbers 	Hard	Soln.
579	Find Cumulative Salary of an Employee	Hard	Soln.
585	Investments in 2016	Medium	Soln.
601	Human Traffic of Stadium	Hard	Soln.
603	Consecutive Available Seats	Easy	Soln.
613	Shortest Distance in a Line 	Easy	Soln.
615	Average Salary: Departments VS Company	Hard	Soln.
618	Students Report By Geography	Hard	Soln.
1070	Product Sales Analysis III	Medium	Soln.
1077	Project Employees II	Medium	Soln.
1107	New Users Daily Count	Medium	Soln.
1112	Highest Grade For Each Student	Medium	Soln.
1126	Active Businesses	Medium	Soln.
1127	User Purchase Platform	Hard	Soln.
1159	Market Analysis II	Medium	Soln.
1164	Product Price at a Given Date	Medium	Soln.
1174	Immediate Food Delivery II	Medium	Soln.
1194	Tournament Winners	Hard	Soln.
1204	Last Person to Fit in the Elevator	Medium	Soln.
1225	Report Contiguous Dates	Hard	Soln.
1285	Find the Start and End Number of Continuous Ranges	Medium	Soln.
1303	Find the Team Size	Easy	Soln.
1308	Running Total for Different Genders	Medium	Soln.
1321	Restaurant Growth	Medium	Soln.
1355	Activity Participants	Medium	Soln.
1369	Get the Second Most Recent Activity	Hard	Soln.
CASE WHEN or IIF
#	Title	Difficulty	Solution
262	Trips and Users 	Hard	Soln.
597	Friend Requests I: Overall Acceptance Rate	Easy	Soln.
608	Tree Node	Medium	Soln.
610	Triangle Judgement	Easy	Soln.
615	Average Salary: Departments VS Company	Hard	Soln.
618	Students Report By Geography	Hard	Soln.
626	Exchange Seats	Medium	Soln.
627	Swap Salary	Easy	Soln.
1126	Active Businesses	Medium	Soln.
1142	User Activity for the Past 30 Days II	Easy	Soln.
1158	Market Analysis I	Medium	Soln.
1159	Market Analysis II	Medium	Soln.
1173	Immediate Food Delivery I	Easy	Soln.
1174	Immediate Food Delivery II	Medium	Soln.
1193	Monthly Transactions I	Medium	Soln.
1194	Tournament Winners	Hard	Soln.
1211	Queries Quality and Percentage	Easy	Soln.
1212	Team Scores in Football Tournament	Medium	Soln.
1264	Page Recommendations	Medium	Soln.
1294	Weather Type in Each Country	Easy	Soln.
1322	Ads Performance	Easy	Soln.
1393	Capital Gain/Loss	Medium	Soln.
1398	Customers Who Bought Products A and B but Not C	Medium	Soln.
OFFSET FETCH
#	Title	Difficulty	Solution
176	Second Highest Salary	Easy	Soln.
177	Nth Highest Salary	Medium	Soln.
1321	Restaurant Growth	Medium	Soln.
PIVOT and UNPIVOT
#	Title	Difficulty	Solution
602	Friend Requests II: Who Has the Most Friends	Medium	Soln.
618	Students Report By Geography	Hard	Soln.
1179	Reformat Department Table	Easy	Soln.
1322	Ads Performance	Easy	Soln.
Variable
#	Title	Difficulty	Solution
597	Friend Requests I: Overall Acceptance Rate	Easy	Soln.
1098	Unpopular Books	Medium	Soln.
1107	New Users Daily Count	Medium	Soln.
1113	Reported Posts	Easy	Soln.
LeetCode SQL Questions by ID
#	Title	Difficulty	Solution
175	Combine Two Tables 	Easy	Soln.
176	Second Highest Salary	Easy	Soln.
177	Nth Highest Salary	Medium	Soln.
178	Rank Scores	Medium	Soln.
180	Consecutive Numbers	Medium	Soln.
181	Employees Earning More Than Their Managers	Easy	Soln.
182	Duplicate Emails	Easy	Soln.
183	Customers Who Never Order	Easy	Soln.
184	Department Highest Salary	Medium	Soln.
185	Department Top Three Salaries	Hard	Soln.
196	Delete Duplicate Emails	Easy	Soln.
197	Rising Temperature	Easy	Soln.
262	Trips and Users 	Hard	Soln.
511	Game Play Analysis I	Easy	Soln.
512	Game Play Analysis II	Easy	Soln.
534	Game Play Analysis III	Medium	Soln.
550	Game Play Analysis IV	Medium	Soln.
569	Median Employee Salary	Hard	Soln.
570	Managers with at Least 5 Direct Reports	Medium	Soln.
571	Find Median Given Frequency of Numbers 	Hard	Soln.
574	Winning Candidate	Medium	Soln.
577	Employee Bonus	Easy	Soln.
578	Get Highest Answer Rate Question	Medium	Soln.
579	Find Cumulative Salary of an Employee	Hard	Soln.
580	Count Student Number in Departments	Medium	Soln.
584	Find Customer Referee	Easy	Soln.
585	Investments in 2016	Medium	Soln.
586	Customer Placing the Largest Number of Orders	Easy	Soln.
595	Big Countries	Easy	Soln.
596	Classes More Than 5 Students	Easy	Soln.
597	Friend Requests I: Overall Acceptance Rate	Easy	Soln.
601	Human Traffic of Stadium	Hard	Soln.
602	Friend Requests II: Who Has the Most Friends	Medium	Soln.
603	Consecutive Available Seats	Easy	Soln.
607	Sales Person	Easy	Soln.
608	Tree Node	Medium	Soln.
610	Triangle Judgement	Easy	Soln.
612	Shortest Distance in a Plane	Medium	Soln.
613	Shortest Distance in a Line 	Easy	Soln.
614	Second Degree Follower	Medium	Soln.
615	Average Salary: Departments VS Company	Hard	Soln.
618	Students Report By Geography	Hard	Soln.
619	Biggest Single Number	Easy	Soln.
620	Not Boring Movies	Easy	Soln.
626	Exchange Seats	Medium	Soln.
627	Swap Salary	Easy	Soln.
1045	Customers Who Bought All Products	Medium	Soln.
1050	Actors and Directors Who Cooperated At Least Three Times	Easy	Soln.
1068	Product Sales Analysis I	Easy	Soln.
1069	Product Sales Analysis II	Easy	Soln.
1070	Product Sales Analysis III	Medium	Soln.
1075	Project Employees I	Easy	Soln.
1076	Project Employees II	Easy	Soln.
1077	Project Employees II	Medium	Soln.
1082	Sales Analysis I 	Easy	Soln.
1083	Sales Analysis I 	Easy	Soln.
1084	Sales Analysis I 	Easy	Soln.
1084	Sales Analysis I 	Easy	Soln.
1097	Game Play Analysis V	Hard	Soln.
1098	Unpopular Books	Medium	Soln.
1107	New Users Daily Count	Medium	Soln.
1112	Highest Grade For Each Student	Medium	Soln.
1113	Reported Posts	Easy	Soln.
1126	Active Businesses	Medium	Soln.
1127	User Purchase Platform	Hard	Soln.
1132	Reported Posts II	Medium	Soln.
1141	User Activity for the Past 30 Days I	Easy	Soln.
1142	User Activity for the Past 30 Days II	Easy	Soln.
1148	Article Views I	Easy	Soln.
1149	Article Views II	Medium	Soln.
1158	Market Analysis I	Medium	Soln.
1159	Market Analysis II	Medium	Soln.
1164	Product Price at a Given Date	Medium	Soln.
1173	Immediate Food Delivery I	Easy	Soln.
1174	Immediate Food Delivery II	Medium	Soln.
1179	Reformat Department Table	Easy	Soln.
1193	Monthly Transactions I	Medium	Soln.
1194	Tournament Winners	Hard	Soln.
1204	Last Person to Fit in the Elevator	Medium	Soln.
1205	Monthly Transactions II	Medium	Soln.
1211	Queries Quality and Percentage	Easy	Soln.
1212	Team Scores in Football Tournament	Medium	Soln.
1225	Report Contiguous Dates	Hard	Soln.
1241	Number of Comments per Post	Easy	Soln.
1251	Average Selling Price	Easy	Soln.
1264	Page Recommendations	Medium	Soln.
1270	All People Report to the Given Manager	Medium	Soln.
1280	Students and Examinations	Easy	Soln.
1285	Find the Start and End Number of Continuous Ranges	Medium	Soln.
1294	Weather Type in Each Country	Easy	Soln.
1303	Find the Team Size	Easy	Soln.
1308	Running Total for Different Genders	Medium	Soln.
1321	Restaurant Growth	Medium	Soln.
1322	Ads Performance	Easy	Soln.
1327	List the Products Ordered in a Period	Easy	Soln.
1336	Number of Transactions per Visit	Hard	Soln.
1341	Movie Rating	Medium	Soln.
1350	Students With Invalid Departments	Easy	Soln.
1355	Activity Participants	Medium	Soln.
1364	Number of Trusted Contacts of a Customer	Medium	Soln.
1369	Get the Second Most Recent Activity	Hard	Soln.
1378	Replace Employee ID With The Unique Identifier	Easy	Soln.
1384	Total Sales Amount by Year	Hard	Soln.
1393	Capital Gain/Loss	Medium	Soln.
1398	Customers Who Bought Products A and B but Not C	Medium	Soln.
1407	Top Travellers	Easy	Soln.
1412	Find The Quiet Students in All Exams	Medium	Soln.
