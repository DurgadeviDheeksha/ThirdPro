1. What will you do once you find the Bug?

Once a bug is found this should be communicated to the developer. Before reporting the bug make sure that the bug is well documented with steps to repro, conditions under which this bug is occurring, how many time it occurs &  the excepted result of the bug. The bug report should accurate & complete, so that developer can get the exact failure reason. Based on this developer can get an exact idea of the problem faced by user & it helps to resolve the problem accurately. To facilitate this task tester should repro the bug & verify that this is a bug & add same repro steps with example & attach screenshots which helps to prove that a bug has been encountered. Also, attach the related logs that provide the activities about the time of bug occurrence.

Bug-Defect-TrackingWhile reporting the bug, it should be divided into various categories like GUI, Functional or Business, Navigational, Validation error etc. which will again help to categorize the bugs in the bug management.

The approach of tester would help a lot to get bug fixed bug quickly & correctly. The main thumb rule is that you (tester) should be confident enough while reporting the bug. Before adding a bug makes sure that you are not adding duplicate bug (which is already logged). Many of the bug defect tracking systems are a help to identify or prevent to add a duplicate bug, which is restricting to adding unnecessary bugs which will help to reduce rework in case of bug management.

Along with bug report adding few extra information would definitely help the developer to get exact scenario or steps to understand the problem like types of hardware & software, environment configuration, setup, versions (like Browser version & name) etc.

This page describes the various fields that you see on a bug.

Bug Title: This is the title of bug help to identify the bug in one-liner description.
Bug identifier: It is auto-generated unique ID helps to identify the bug.
In the Bug Tracking Tool, this field is auto-populated.
Description: This should cover bug description along with the exact Steps To Reproduce, Expected Result, Actual Result and example.
Status: This field indicates the actual status of the bug in the Bug life cycle.
Here is the list of Bug Statuses in standard Bug life cycle:
New, Assigned, Resolved, Reopened, Verified (Vary based on Bug Tracking Tool)
Bug Assignee: This is the name of the developer who is responsible to resolve the bug.
Bug Cc: Add the manager and lead email address in CC list.
In the Bug Tracking Tool, this field is auto-populated based on configuration.
Reported On: The date on which the bug is occurred & reported the bug.
Browser: This field indicates on which browser & version this issue occurs.
Bug Type: The bug is categories into a different category like Functional, Navigational, GUI etc.
Environment: On which OS, platform this bug occurs.
Component: This field indicates the sub-modules of the product.
Priority: Urgency to fix the bug?
Priority can be set as P1 to P5.
The P1 means “first fix this bug i.e. priority is highest” and P5 means “No urgent, when get time then fix it”.
Blocker: Unless and until this fix no further testing can be done
Critical: Application is crashing or Losing the data.
Major: Major function under test is not working.
Minor: Minor function under test is not working.
Trivial: UI issues
Enhancement: Asking for new changes as an enhancement.Severity: This tells you about the impact of the bug.
Types of Severity:
Product
Reporter: Your name.
In the Bug Tracking Tool, this field is auto-populated.
Reproduces: In this section, you can have options like Always and Sometimes etc.
URL: The page URL on which bug occurred.
Build number: The Build number field describes the number of Builds on which the bug is found in.
Some Bonus tips to write a good bug report:
1) Report the problem as early as possible:
While testing if you observed any bug, add this bug to the bug defect tracking tool immediately, don’t wait to write bug in details afterward. If you thinking of reporting bug later then it might be possible that miss few important reproduce steps. Reporting bug immediately will help to write a good bug report, which help developer to get an exact idea of the problem faced by the user.

2) Double cross checks bug before reporting the bug:
Thumb rule is the bug should be reproducible using added “Steps to reproduce” in the bug report. If you are thinking that the bug is not reproducing all the time then it should be reported in the bug by using the field “Reproduces: Sometimes” field in the bug report.

3) Check if the same bug is occurring in some other related module:
Many of the time the same issue might be occurring in the other module of the project as well. So might be possible that occurrence of the same issue in another module. Check this before filing a bug & if it is happening then this should be added to the bug report.

4) Write a good bug summary:
Based on the summary of the bug the developers are getting nature of the bug. If bug summary is not that good enough then because of such poor quality bugs will unnecessary increasing the bug cycle? The bug summary should be well communicated & good enough to understand developer about exact problem. Also, keep in mind that this bug summary will be used to search the bug afterward from the all reported bug.

5) Don’t make use of offensive language in the bug:
It is very nice that you found the bug but it not mean that you use offensive language in a bug against the developer or any individual or should not all blame to the developer.

6) Before clicking Submit button please review the bug report:
This is good practice to read bug before reporting it. You should check for Title, Summary, and Steps to repro in the bug report. As mention in above point check for if any offensive language used in bug report which might create misunderstanding or false impression. Such sentences or words should be kept away from the bug report. Also, add Screenshots which helps prove that a bug has been encountered.




















