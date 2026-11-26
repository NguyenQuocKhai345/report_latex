Software Testing – 2026S1 

Project 

1 

# **Project description** 

# Part#2: Black-box testing 

## **I. Description** 

Apply the black box testing techniques to the Moodle LMS applications. 

(A docker version as declared at https://moodle.org/mod/forum/discuss.php?d=473779 The code is at <u>https://github.com/mutms/demo)</u> 

## Techniques to be applied: **_boundary value analysis, equivalent class partitioning, decision table (bonus) and use-case testing methods_** . 

## **II. Instruction** 

1/ For each student, select at least one feature that can be used to apply all the testing methods mentioned above for generating test cases. Two students in the same group cannot select the same feature. 

For each feature, provide a brief description, its use case, and instructions for usage. For example, when adding a new user to Moodle, you may need to validate the associated login details depending on the selected alternative options. 

## **_Restrictions:_** 

- Do not select login/logout functionalities and change password of default users for testing, if such features exist. 

- All relevant testing techniques must be applied to each selected feature. 

- For Boundary Value Analysis (BVA) and Equivalence Class Partitioning (ECP), all input variables of a feature must be taken into account during the analysis. 

## 2/ Document your entire process, including: 

- The selected features, including their description (and use case and activity diagrams), 

- A detailed, step-by-step description of how each testing technique was applied, and 

- Any other relevant information related to the test case generation process. 

Also note: Each test case should be identified using the format TC-XXX-YYY, where XXX represents the feature number (001, 002, …) and YYY represents the test case serial number (001, 002, …). 

## 3/ Use of AI Tools: 

Students may use free, non-professional AI tools to assist with test case generating. The report (PDF file) must include a section titled “AI Usage Declaration” that clearly states: 

- The AI tool(s) used; 

- The prompts provided to the AI tool(s). 

If no AI tools were used, the “AI Usage Declaration” section should contain only the following statement: 

Software Testing – 2026S1 

Project 

2 

“We hereby confirm that no AI assistance was used in this work.” 

Important: Failure to declare AI assistance accurately, including falsely claiming that no AI was used, may result in 0 marks for this mini-project and may be subject to further academicintegrity review. 

4/ Document all generated test cases in the provided .xlsx template. 

Note: Each test case must be described in **sufficient detail** so that any individual can execute the tests solely based on the information contained in the .xlsx file, without requiring additional instructions. 

5/ Learn how to use the Katalon Recorder (https://docs.katalon.com/katalon-platform/pluginsand-add-ons/katalon-recorder-extension/get-started/katalon-recorder-gui-overview) - a web automation testing tool - and implement all generated test cases using it. 

**Download** the completed test cases in **.krecorder** format so that they can be easily re-executed in the future. 

Please the re-execute the downloaded test cases in another machine before submitting them. 

Note: Each test case must include at least one “verify” action to compare the actual output with the expected result. 

There may be a script for data preparation such as setting up a course (in Moodle), a new user… and a script to clean up the data. Those scripts will be executed before and after running other test scripts. 

## **III. Report** 

- Represent your team workload (task assignments/member contribution) and your works mentioned in I.2  and I.3 in a .pdf file. 

   - Represent test cases in a .xlsx file (using the given template). 

- Compress all files in I.4 in a .zip format. 

## **IV. Submission** 

- One member of each group submit the group report (.pdf), test cases (.xlsx) and Katalon files (.zip) via the Proj#2 assignment. 

## **V. Marking schema** 

||**Max**<br>**point**|**Rubric**||
|---|---|---|---|
|**1. Requirement spec.**|**1.0**|No. of features =[No. members]x 1||
|**2. Testing techniques**|**5.0**|||
|2.1. Boundary value|**1.5**|Try: 0.5|No expected result: -|
|analysis technique||Fair: 1.0<br>Good: 1.5|0.5|



Software Testing – 2026S1 

Project 

3 

|2.2. Equivalence class<br>partitioning technique|**1.5**|Try: 0.5<br>Fair: 1.0<br>Good: 1.5||No expected result: -<br>0.5|
|---|---|---|---|---|
|2.3. Decision table<br>technique|**+1.0**|Fair: 0.5<br>Good: 1,0||No expected result: -<br>0.5|
|2.4. Use-case testing<br>technique|**2.0**|Activity graph: 0.5<br>Test-scenarios: 0.5<br>(paths)|Test-cases: 1.0<br>(steps<br>+<br>expected<br>results)|Missing cases: -0.25<br>each|
|**3. Katalon Recorder**|**2.0**|A few: 0.5<br>All: 1.0|Somehow work:<br>0.5<br>Work well: 1.0|No “verifyXXX” step:<br>no mark|
|**4. Report**|**2.0**|.pdf: 0.5<br>+ good: 0.5|.xls:<br>0.5<br>precond: +0.5|AI section:<br>no = -2.0,<br>not clear = -1.0 upto<br>-1.5|
||**10**||||



