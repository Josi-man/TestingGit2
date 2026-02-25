<h1>Test Plan</h1>
This is the template for your test plan. The parts in italics are concise explanations of what should go in the corresponding sections and should not appear in the final document.

<h2>Author:</h2> Team 115

<h2>1 Testing Strategy</h2>
<h3>1.1 Overall strategy</h3>
The goal of this testing strategy is to validate the functionality, usability, and performance of the single-user job comparison app. The strategy will cover unit testing, integration testing, system testing, and regression testing.

<h4>1.1.1 Unit Testing</h4>

Unit testing will focus on individual components of the app to ensure that each component works correctly.

<b>Activities:</b>

Writing unit tests for each function or method in the code (e.g., adding job offers, ranking jobs).
Ensuring that error conditions are tested (e.g., negative salary, empty job data).

<b>Who Performs:</b> Unit testing will primarily be performed by the development team (developers).

<b>Test Tools:</b> JUnit

<h4>1.1.2 Integration Testing</h4>

Integration testing will used to verify multiple components work together as expected. For instance, the integration between the job offer storage module and the job comparison logic will be tested to ensure data is passed correctly between components.

<b>Activities:</b>

    Testing the integration of key modules such as job storage, comparison algorithms, and UI interactions.
    Validating that job data stored in the database is retrieved and processed correctly for comparison.

<b>Who Performs:</b> Integration tests will be performed bu both developers and quality assurance (QA).

<b>Test Tools:</b> JUnit (for integration tests).

<h4>1.1.3 System Testing</h4>

System testing will involve testing the entire application as a whole to ensure that it meets all specified functional and non-functional requirements. The system will be tested from a user perspective to ensure that it is fully functional and ready for deployment.

<b>Activities:</b>

    Testing the app’s full functionality, including job saving, job comparison, ranking, and criteria customization.

    Testing user interface (UI) for usability, layout, and accessibility.

    Validating system interactions between different components like front-end, back-end, and databases.

    Performance testing to ensure the system works efficiently, even under heavy load (e.g., comparing 100+ job offers).

<b>Who Performs:</b> QA engineers will primarily perform system testing. They will create test cases based on the app's requirements and specifications, and run manual or automated tests to verify system functionality.

<b>Test Tools:</b> ???

<h4>1.1.4 Regression Testing</h4>

Regression testing will ensure that new changes or additions to the app do not negatively impact the existing functionality. This will be especially important when new features (e.g., adding new job comparison criteria or UI changes) are introduced.

<b>Activities:</b>

Re-running previously executed tests to check if the app still behaves as expected after code changes.

Testing the core features of the app, like job saving, comparison functionality, and ranking, after each new release or update.

Performing automated regression tests to speed up the process of validating common functionalities after changes.

<b>Who Performs:</b> QA engineers will primarily conduct regression testing, leveraging automated test scripts to cover major use cases. Developers will also run unit regression tests when working on specific code changes.

<b>Test Tools:</b> JUnit.

<h3>1.2 Test Selection</h3>
Testing will be categorized into the following types:

<h4>Unit Testing</h4>
Objective: Validate individual functions and methods.
Techniques: White-box testing, focusing on functionality like adding jobs, salary validation, and saving settings.

<h4>Integration Testing</h4>
Objective: Test interaction between components.
Techniques: Black-box testing to ensure that job addition integrates smoothly with comparison functionalities.

<h4>System Testing</h4>
Objective: Validate the complete application against requirements.
Techniques: Black-box testing, running end-to-end user scenarios and checking for performance and usability.

<h4>Regression Testing</h4>
Objective: Ensure new changes don’t affect existing functions.
Techniques: Black-box testing, re-running previous test cases to check compatibility with new features and ensuring critical use cases still work.

<h3>1.3 Adequacy Criterion</h3>
Test coverage will be assessed through the following criteria:

Code Coverage: Aim for at least 80% of code coverage through automated tests.
Functional Coverage: Ensure all critical functionalities (entering jobs, editing details, comparing offers) are tested.
Usability Completion Rate: Aim for a successful completion rate of at least 90% in usability scenarios during UAT.


<h3>1.4 Bug Tracking</h3>
A defect tracking system will be used to record, monitor, and manage identified issues. The process will include:

Logging defects with severity classifications (Critical, Major, Minor).
Hold review meetings regularly to evaluate impact and determine resolution.
Utilizing tracking tools such as_______ to streamline monitoring.



<h3>1.5 Technology</h3>
Testing processes will be supported by the following tools and technologies:

JUnit for automated functional test execution.
____ for defect management and project tracking.
Git for controlling code versions.




<h2>2 Test Cases</h2>
This section should be the core of this document. You should provide a table of test cases, one per row. For each test case, the table should provide its purpose, the steps necessary to perform the test, the expected result, the actual result (to be filled later), pass/fail information (to be filled later), and any additional information you think is relevant.
<table border="1">
    <tr>
        <td colspan=2 style='display:center'> Test Case Number: </td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td>No existing current job in the record.</td>
    </tr>
    <tr>
        <td>Enter current job details for the first time.</td>
        <td>
        

        1. Open the **Job Detail** form.  
        2. Verify that the form loads successfully.  
        3. Enter valid data into the following fields:  
            I. Title  
            II. Company  
            III. City  
            IV. State  
            V. Cost of Living  
            VI. Yearly Salary  
            VII. Stock Options  
            VIII. Wellness Stipend  
            IX. Life Insurance  
            X. Personal Development Fund  
        4. Click **"Save Job."**
        </td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td>Job details are saved successfully.</td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started</td>
    </tr>

<tr>
        <td colspan=2 style='display:center'></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>


<tr>
        <td colspan=2 style='display:center'></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>

<tr>
        <td colspan=2 style='display:center'></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>

<tr>
        <td colspan=2 style='display:center'></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>   
   
</table>