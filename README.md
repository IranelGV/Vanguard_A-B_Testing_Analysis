# Vanguard_A-B_Testing_Analysis

Introduction
Welcome to the Module 2 project! You will apply all of the skills and knowledge you have accumulated throughout the module as well as new things you will learn over the next two weeks. You are not expected to be able to know everything from the beginning of the project - you will learn about the following topics and apply them to your project over the next two weeks:

EDA and Data Cleaning
Performance Metrics
Hypothesis testing
Experiment Evaluation
Tableau
Setup
In this project you will work in pairs. Like with the projects and mini projects, you should create a Kanban board for project management purposes in order to decide how to best divide the work between you.

Typical Day
In this project you will be working on the project during the afternoons with your partner. The final two days of the project you will be able to dedicate the full day to the project ahead of the presentation on the Friday of week 6.

Project Brief
Context
You are a newly employed data analyst in the Customer Experience (CX) team at Vanguard, the US-based investment management company. You’ve been thrown straight into the deep end with your first task. Before your arrival, the team launched an exciting digital experiment, and now, they’re eagerly waiting to uncover the results and need your help!

The Digital Challenge
The digital world is evolving, and so are Vanguard’s clients. Vanguard believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients. The critical question was: Would these changes encourage more clients to complete the process?

The Experiment Conducted
Note: Review what A/B testing is here if you are not already aware of how it works:

AB Testing
An A/B test was set into motion from 3/15/2017 to 6/20/2017 by the team.

Control Group: Clients interacted with Vanguard’s traditional online process.
Test Group: Clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

The goal is to see if the new design leads to a better user experience and higher process completion rates.

Your Data Tools
There are three datasets that will guide your journey:

Client Profiles (df_final_demo): Demographics like age, gender, and account details of our clients.
Digital Footprints (df_final_web_data): A detailed trace of client interactions online, divided into two parts: pt_1 and pt_2. It’s recommended to merge these two files prior to a comprehensive data analysis.
Experiment Roster (df_final_experiment_clients): A list revealing which clients were part of the grand experiment.
Topics & Tasks by Day
Your primary objective is to decode the experiment’s performance. You can find the questions and tasks the team have for you divided by day below. The division of tasks for each day is a suggestion. As long as you have the project ready with all the tasks completed by the end of week 6, you are good to go!

Day 1 & 2 (Week 5)
EDA & Data Cleaning

Dataset Exploration

Client behavior analysis

Client behavior analysis

Day 3 (Week 5)
Note: Review this content on KPIs and Metrics before starting day 3’s tasks:

KPIs & Metrics
Performance Metrics

Success Indicators
Redesign Outcome

Day 4 & 5 (Week 5)
Hypothesis Testing

As part of your analysis, you’ll conduct hypothesis testing to make data-driven conclusions about the effectiveness of the redesign. See the full details below:

Completion Rate
Completion Rate with a Cost-Effectiveness Threshold
Other Hypothesis Examples

Experiment Evaluation

You are also required to carry out an evaluation of the experiment by answering questions about the design effectiveness, duration and any additional data needs. See the full details below:

Design Effectiveness
Duration Assessment
Additional Data Needs

Day 1 & 2 (Week 6)
Tableau

Once you have your findings, use Tableau to create insightful and interactive visualizations.

Tableau Tasks

Day 3 & 4 (Week 6)
Enhance and finalize all tasks from the previous days to create a comprehensive project presentation due this Friday. Ensure that the project is not only complete but also offers clear insights, well-defined deliverables, and is accompanied by organized and structured code. Additionally, consider addressing any optional bonus tasks that may arise or are listed in the bonus task inventory (see below).

Furthermore, please verify that you have thoroughly reviewed the self-guided lessons on the following topics:

Streamlit
Project setup: directories and environments
This comprehensive approach will help you showcase a polished and well-rounded project in your presentation.

Getting Started
Metadata
This comprehensive set of fields will guide your analysis, helping you unravel the intricacies of client behavior and preferences.

client_id: Every client’s unique ID.
variation: Indicates if a client was part of the experiment.
visitor_id: A unique ID for each client-device combination.
visit_id: A unique ID for each web visit/session.
process_step: Marks each step in the digital process.
date_time: Timestamp of each web activity.
clnt_tenure_yr: Represents how long the client has been with Vanguard, measured in years.
clnt_tenure_mnth: Further breaks down the client’s tenure with Vanguard in months.
clnt_age: Indicates the age of the client.
gendr: Specifies the client’s gender.
num_accts: Denotes the number of accounts the client holds with Vanguard.
bal: Gives the total balance spread across all accounts for a particular client.
calls_6_mnth: Records the number of times the client reached out over a call in the past six months.
logons_6_mnth: Reflects the frequency with which the client logged onto Vanguard’s platform over the last six months.
Bonus: Additional Tasks (Optional)
If you complete all of the tasks and have some extra time before the presentation, you can explore the following additional questions and tasks:

Client Behavior Analysis
Power and Effect Size
Streamlit

Deliverables
You must submit the following deliverables in order for the project to be deemed complete:

A new repository with the name vanguard-ab-test on your GitHub account.
Working code that meets all technical requirements, built by you.
At least 1 Jupyter notebook is required
Include your functions in .py files
Additional needed files for your work, such as a Tableau file
A README with the completed project documentation.
The URL of the slides for your project presentation.
Presentation: When presenting your work, there are many important factors to consider, such as the content of your presentation and the way you deliver it.
Remember to allow time to rehearse the presentation beforehand.
See “Presentation” section below for guidelines.
Paste your own repository’s link in the Student Portal Project Activity.
Note: Each student should have their own repository to submit.
Links to the data you are using (sources) and your Kanban board (Trello) in the README.
Rubric
In order to assess your project and ensure all requirements are met, a rubric will be used. This rubric is used to evaluate your project by your teaching staff but also to communicate what constitutes incomplete, acceptable and excellent performance across each of the learning outcomes for the project. Take some time to review the rubric that is in Student Portal and ask your teacher any questions about it if necessary.

The Presentation
Once you’ve started to draw your conclusions, prepare to share your insights through a presentation. Imagine presenting to Vanguard’s top brass in a 10 minute meeting. Remember to back your findings with data and analysis. While you have the freedom to use any advanced tool or language, the team at Vanguard is quite fond of Python and SQL.

All presentations will be done from a staff member’s computer, so your slides need to be online. PowerPoint files, Keynote files or files of any kind will not be accepted.

Suggested online slide applications:
Google Slides
Slides
Prezi
Presentation Structure
Feel free to present the project in as you feel best represents your work, but below you will find a suggested format for the presentation as a guide.

Title Slide (1 slide):
Your project’s title and your team members’ names.
Introduction (1 slide):
Briefly introduce Vanguard and the context of the digital challenge.
State the main question: Did the new UI lead to higher completion rates?
Data Overview (1-2 slides):
Present an overview of the three datasets used: Client Profiles, Digital Footprints, and Experiment Roster.
Outline the data cleaning and merging process you performed.
Exploratory Data Analysis (EDA) (2-3 slides):
Highlight the key demographics and behaviors of Vanguard’s online clients.
Share initial findings about client engagement before diving into the A/B test results.
Performance Metrics (2-3 slides):
Define the KPIs you chose to evaluate the new design’s performance.
Compare the KPIs for the Control Group vs. the Test Group.
Present visual aids to support the KPI analysis.
Hypothesis Testing (2-3 slides):
Discuss the hypothesis tests conducted, the chosen significance levels, and the results.
Include the tests for completion rate differences and cost-effectiveness threshold evaluation.
Present any additional hypothesis tests conducted and their outcomes.
Experiment Evaluation (1-2 slides):
Evaluate the experiment design, discussing the randomization, duration, and potential biases.
Suggest what additional data could have been beneficial.
Tableau Visualizations (2-3 slides):
Showcase the Tableau dashboard and visualizations created.
Demonstrate how viewers can interact with the data based on demographics.
Teamwork & Project Management (1 slide):
Reflect on how you divided and conquered the project tasks using your Kanban board.
Share insights about your team’s collaboration and project management strategies.
Challenges & Learnings (1-2 slides):
Highlight any significant challenges you faced during the analysis.
Discuss how you overcame them and what learnings you took away.
Conclusion (1-2 slides):
Summarize the key findings from your analysis.
State your final verdict on the new digital interface’s effectiveness.
Offer recommendations for Vanguard based on your insights.
Hints
Consider reviewing these hints if you need some extra pointers. It’s even more impressive if you can complete the case study without these pointers!

See hints here
