>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 13      |
|-----------------|
| Student 1 : Tien Dat Johny Do                |   
| Student 2 : Tommy Dinh              |   
| Student 3 : Stuart Johnstone               |   
| Student 4 : Sina Tavakol Moghaddam                |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

Before the lab our group summarized that exploratory testing is learning the system while concurrently testing the SUT. The exploratory testing is focusing on the discovery of bugs/defects through the tester. Our group thought of exploratory testing as testing each function to ensure they work. On the other hand, manual functional testing, our team supposes that this testing method included a manual/script of some-sort taking the tester through very specific scenarios of test cases that they would have to verify against the system at hand. In brief, before the lab our group had an understanding that exploratory testing is about discovery and learning of the system and for the methodology of manual functional testing, we focus on generated prompts/test cases that the tester has to verify. 

# High-level description of the exploratory testing plan

As a high level plan, our group will divide and conquer the assignment. We will divide the work into 2 equal sections. After reading the requirements in Appendix B, each group of two will explore different functions of the ATM for 30 minutes. One group will look at the the first half of the program including (system on/off buttons, card validation, pin validation) and the other group will look at the second half of the program including the functions (withdrawal, deposit, transfer and inquiry). We will have a bug tracking took such as an Excel/Jira project that we will all collaborate on as we do this pair-testing. We will then comeback as a whole group and we will explain each defect/big that we have put into the bug tracking tool. 

# Comparison of exploratory and manual functional testing

Exploratory testing :
	In the event of using exploratory testing we found some benefits. Some of the benefits our team highlighted is the benefit of learning the system while testing and it feels like a freestyle/flexible way of testing. With reading the Appendix B to learn about the requirements of the system, we were about to learn and familizarize ourselves with the system and how each function works with limited preparation time. As well in exploratory testing, we were not constrained by test cases, we could freely test the system in a way that a “user” could potentially use it which could lead to finding bugs that are not highlight through a test case. Some shortcomings that our group found with exploratory testing was that we could also miss bugs due to time and it was a more tedious process to document the bug. Although we could explore the system, within 30 minutes we could not go through the whole system and we could potentially miss bugs. This being the case in our lab, applying this to a real-life scenario we can imagine that exploratory testing takes a significantly longer time to explore the whole SUT and report the bugs. In addition, for our exploratory testing, we had a Excel sheet that documented all the bugs we have found. This took as well more time to document the bugs that we have found and we would have to frequently check back with the requirements in Appendix B in order to make sure what to put in the section of “Expected Output” to ensure that the function is not bugged. We often found that we would spend more time on some parts of the system over other parts due to this time management which made this testing method not as effective and efficient as our group wanted. 

Manual Functional Testing : 
	In our manial functional testing our group highlight the benefit of having well documented test cases to find functional defects which in turn made testing faster, and the test cases did cover most functionalities of the system. This testing method was quite well laid out in terms of all the column headers of test case numbers, use case, functions being test, initial system state, input, expected outputs, actual output, and pass/fail. This scripted testing made testing easy to navigate with each test case having specific instructions. This significantly made documenting bug fixes easily and faster just having to put the actual output and a simple pass/fail. Furthermore, the manual function testing seem to cover the more important functions/sections of the system which makes the testing coverage of the system better. All the instructions of the manual testing really emulated what a “user” would do if they were to go about using this system. A pitfall even within this testing method, could be that we only stuck to the scripted testing, which could lead to missing some other bugs that are potentially not listed as a test case. If those bugs are not in the scrip of the test cases, then they will be missed in the testing phase. It was still a quite effective and efficient testing method because we are able to cover a wide range of functions with a well documented script to follow which made testing faster and easier. 

Comparison : 
	In all our group found that manual functional testing had a great structure compared to exploratory. Within exploratory, we have to make all of our test cases and document all the information, but with manual scripted testing we are able to follow clear laid out instructions that tested the system. The test cases covered a wide range of the functionalities of the system compared to the exploratory method. We found that we took more time to test specific functions in the exploratory method which gave us a good understanding of the program, compared to the overview of test from the scripted testing. In conclusion the overview of both methods are as follows, the exploratory testing gave us a flexible way of learning and testing the system simultaneously and the manual scripted testing gave us a structured requirements to verify and document the results.

-   Note that you need to submit a report generated by your defect tracking
    system, containing all defects recorded in the system.

# Notes and discussion of the peer reviews of defect reports

 per group would do all 20 test cases in one go while the other group member took all the documentation of test case number, use case, function being tested, initial system state, input, expected output, actual output, pass/fail. Then we would do a switch where the person testing will check over the documentation and the person documenting will be the tester. In this way we were about to double check with each other and familiarize with the system. Our group found this useful because it allowed us to be sure of the documentation, but as well as learn the system and how we can interact with it. We then would upload any of the bugs found into a Jira project with containers of Bugs to Fix, In-progress/under review, and Bugs Fixed. We would then come into a full group where we all check together all of our test cases and make sure that bugs are documented correctly with reproducibility as well as added to the bug tracking device correctly and under the correct containers. Our group liked the peer-review structure because it helped us double check our test cases as well as helped us deliver feedback and create discussion on the bugs/defects we have found or we have missed. Within the whole group we only changed one test case which was debated in favour of failing the test case which was missed in the peer review. We found the peer reviews of the defect reports very valuable in terms of starting discussions among the test cases. 

# How the pair testing was managed and team work/effort was divided 

Our group will separate into individual work and then come together in pair testing and again in collective group testing. We will meet outside of lab/class time in order to look over the test cases. Referencing from Appendix C, Stuart will work on test cases 1-10, Johny will take test cases 11-20, Sina will take on test cases 21-30, and Tommy will work on test cases 31-40.  The individuals will then pair up and go over each other's work. Once the initial individual check is finished, each pair will then swap their work with the other pair and another check will be done. We have an excel masterfile to tabulate our results. We will be looking at all the functionalities of the program such as the system startup, system shutdown, session, transactions, withdrawal, deposit, transfer, inquiry, and invalid pin extension. We are referencing our test cases from Appendix C and will add any other test cases if necessary considering the High Level Requirements from Appendix B.  

# Difficulties encountered, challenges overcome, and lessons learned

One difficulty that was encountered was the use of Jira as a bug tracking tool. Since every group member is new to software testing and bug tracking. There was a learning curve on how to use Jira as a bug tracking tool. Some features were creating projects, creating issues, as well as categorizing how the containers are labelled for bug fixing. In the end, we have learned how to use Jira and how to set up an environment for bug fixing 

Another difficulty was through the first phase of the exploratory testing phase, our difficulty was that we did not assess enough time to do more of a general search of bugs in the system, rather we testing each function in depth. Each function had to also be documented as well which cause us to use up our 30 minutes quicker than we expected. Our lesson learned was that we had to plan out more of our time management in order to fully experience the exploratory testing phase to its maximum potential. 

The final difficulty was finding time to do our peer testing outside of lab time due to conflicting schedules. Since this lab was focused on peer testing and peer reviewing we found it essential to find time outside of lab time in order to finish the lab. Lessons learned are to decide ahead of time which days everyone is free and be proactive in scheduling. 


# Comments/feedback on the lab and lab document itself

Our group found the lab document sufficiently detailed while also being concise. This allowed our group to effectively divide the work among ourselves to best tackle the assignment, though it would have been nice to include the appendix C in an excel file to avoid some minor formatting issues that were present in the assignment outline. In addition, it was a good learning introductory lab to system testing. 
