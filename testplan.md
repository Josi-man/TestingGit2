<h1>Test Plan</h1>
This is the template for your test plan. The parts in italics are concise explanations of what should go in the corresponding sections and should not appear in the final document.

<h2>Author:</h2> Team 115

<h2>1 Testing Strategy</h2>
<h3>1.1 Overall strategy</h3>
The goal of this testing strategy is to validate the functionality, usability, and performance of the single-user job comparison app. The strategy will cover unit testing, integration testing, system testing, and regression testing.

<h4>1.1.1 Unit Testing</h4>

Unit testing will focus on individual components of the app to ensure that each component works correctly.

<b>Activities:</b>
<ul>
    <li>Writing unit tests for each function or method in the code (e.g., adding job offers, ranking jobs).</li>
    <li>Ensuring that error conditions are tested (e.g., negative salary, empty job data).</li>
</ul>
<b>Who Performs:</b> Unit testing will primarily be performed by the development team (developers).<br>
<b>Test Tools:</b> JUnit

<h4>1.1.2 Integration Testing</h4>

Integration testing will used to verify multiple components work together as expected. For instance, the integration between the job offer storage module and the job comparison logic will be tested to ensure data is passed correctly between components.

<b>Activities:</b>
<ul>
    <li>Testing the integration of key modules such as job storage, comparison algorithms, and UI interactions.</li>
    <li>Validating that job data stored in the database is retrieved and processed correctly for comparison.</li>
</ul>
<b>Who Performs:</b> Integration tests will be performed bu both developers and quality assurance (QA).<br>
<b>Test Tools:</b> JUnit (for integration tests).

<h4>1.1.3 System Testing</h4>

System testing will involve testing the entire application as a whole to ensure that it meets all specified functional and non-functional requirements. The system will be tested from a user perspective to ensure that it is fully functional and ready for deployment.

<b>Activities:</b>
<ul>
    <li>Testing the app’s full functionality, including job saving, job comparison, ranking, and criteria customization.</li>
    <li> Testing user interface (UI) for usability, layout, and accessibility.</li>
    <li> Validating system interactions between different components like front-end, back-end, and databases.</li>
      <li> Testing user interface (UI) for usability, layout, and accessibility.</li>
</ul>

<b>Who Performs:</b> QA engineers will primarily perform system testing. They will create test cases based on the app's requirements and specifications, and run manual or automated tests to verify system functionality.<br>
<b>Test Tools:</b> ???

<h4>1.1.4 Regression Testing</h4>

Regression testing will ensure that new changes or additions to the app do not negatively impact the existing functionality. This will be especially important when new features (e.g., adding new job comparison criteria or UI changes) are introduced.

<b>Activities:</b>
<ul>
    <li>Re-running previously executed tests to check if the app still behaves as expected after code changes.</li>
    <li> Testing the core features of the app, like job saving, comparison functionality, and ranking, after each new release or update.</li>
    <li> Validating system interactions between different components like front-end, back-end, and databases.</li>
    <li>Performing automated regression tests to speed up the process of validating common functionalities after changes.</li>
</ul>

<b>Who Performs:</b> QA engineers will primarily conduct regression testing, leveraging automated test scripts to cover major use cases. Developers will also run unit regression tests when working on specific code changes.<br>
<b>Test Tools:</b> JUnit.

<h3>1.2 Test Selection</h3>
Testing will be categorized into the following types:

<h4>1.2.1 Unit Testing</h4>
<b>Objective:</b> Validate individual functions and methods.<br>
<b>Techniques:</b> White-box testing, focusing on functionality like adding jobs, salary validation, and saving settings.

<h4>1.2.2 Integration Testing</h4>
<b>Objective:</b> Test interaction between components.<br>
<b>Techniques:</b> Black-box testing to ensure that job addition integrates smoothly with comparison functionalities.

<h4>1.2.3 System Testing</h4>
<b>Objective:</b> Validate the complete application against requirements.<br>
<b>Techniques:</b> Black-box testing, running end-to-end user scenarios and checking for performance and usability.

<h4>1.2.4 Regression Testing</h4>
<b>Objective:</b> Ensure new changes don’t affect existing functions.<br>
<b>Techniques:</b> Black-box testing, re-running previous test cases to check compatibility with new features and ensuring critical use cases still work.

<h3>1.3 Adequacy Criterion</h3>
Test coverage will be assessed through the following criteria:

Code Coverage: Aim for at least 80% of code coverage through automated tests.
Functional Coverage: Ensure all critical functionalities (entering jobs, editing details, comparing offers) are tested.
Usability Completion Rate: Aim for a successful completion rate of at least 90% in usability scenarios during UAT.


<h3>1.4 Bug Tracking</h3>
A defect tracking system will be used to record, monitor, and manage identified issues. The process will include:

<ul>
    <li>Logging defects with severity classifications (Critical, Major, Minor).</li>
    <li> Hold review meetings regularly to evaluate impact and determine resolution.</li>
    <li>Utilizing tracking tools such as_______ to streamline monitoring.</li>
    
</ul>

<h3>1.5 Technology</h3>
Testing processes will be supported by the following tools and technologies:

<ul>
    <li>JUnit for automated functional test execution.</li>
    <li>____ for defect management and project tracking.</li>
    <li>Git for controlling code versions.</li>    
</ul>


<h2>2 Test Cases</h2>
This section should be the core of this document. You should provide a table of test cases, one per row. For each test case, the table should provide its purpose, the steps necessary to perform the test, the expected result, the actual result (to be filled later), pass/fail information (to be filled later), and any additional information you think is relevant.
<table border="1">
    <tr>
        <td colspan=2 style='display:center'> <b>Test Case Number:</b> 001 </td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td>No existing current job in the record.</td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Enter current job details for the first time.</td>
    </tr>
    <tr>
        <td>Steps</td>
    <td>
        <ol>
        <li>Open the <strong>Job Detail</strong> form.</li>
        <li>Verify that the form loads successfully.</li>
        <li>
            Enter valid data into the following fields:
            <ol type="I">
            <li>Title</li>
            <li>Company</li>
            <li>City</li>
            <li>State</li>
            <li>Cost of Living</li>
            <li>Yearly Salary</li>
            <li>Stock Options</li>
            <li>Wellness Stipend</li>
            <li>Life Insurance</li>
            <li>Personal Development Fund</li>
            </ol>
        </li>
        <li>Click <strong>"Save Job."</strong></li>
        </ol>

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
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 002</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td>Job detail form loads.</td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Cancel and exit from job detail form.</td>
    </tr>
    <tr>
        <td>Steps</td>
        <td>Click on the “ Cancel” button</td>
    </tr>    
    <tr>
        <td>Expected Result</td>
        <td>The user is redirected to the main menu without saving.</td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started</td>
    </tr>

<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 003</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td>Current Job detail form loads.</td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Edit previously entered current job details.</td>
    </tr>
    <tr>
        <td>Steps</td>
        <td>
        <ol>
        <li>From the listed jobs click on the current job.</li>
        <li>Verify the form loads with previously saved data.</li>
        <li>Modify the fields with valid data.</li>
        <li>Click on "Update Job."</li>
        </ol>  
        </td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td>Updated details are saved successfully.</td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>

<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 004</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Adjust comparison settings.</td>
    </tr>
    <tr>
        <td>Steps</td>
        <td>
        <ol>
        <li>Open the comparison setting form.</li>
        <li>Verify the form loads.</li>
        <li>Verify the default value for each field is 1.</li>
        <li>
            Enter valid value [0-9] for each field below:
            <ul>
            <li>Yearly Salary</li>
            <li>Yearly Bonus</li>
            <li>Stock Options Share</li>
            <li>Life Insurance</li>
            <li>Personal Development Fund</li>
            </ul>
        </li>
        <li>Click on the “Save” button.</li>
        </ol>
        </td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td>Settings are saved successfully.</td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>

<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 005</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Cancel and exit from comparison setting form.</td>
    </tr>
    <tr>
        <td>Steps</td>
        <td>Click on the “ Cancel” button</td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td>The user is redirected to the main menu without saving.</td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 006</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td>List ranked job offers</td>
    </tr>
    <tr>
        <td>Steps</td>
        <td>From the main menu click on the “Compare Job Offers” button.</td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td>Job offers are displayed by title and company, ranked from best to worst. The current job is also displayed if a record exists.</td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 007</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td>Compare two jobs.</td>
    </tr>
    <tr>
        <td>Steps</td>
        <td>
            <ol>
                <li>From the main menu, click on the “Compare Job Offers” button.</li>
                <li>Verify the jobs are listed and ranked from best to worst.</li>
                <li>Select two job offers from the list.</li>
                <li>Click on the “Compare” button.</li>
            </ol>
        </td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td>A table comparing the two jobs displayed the following fields for each job.
        <ul>
            <li>Title</li>
            <li>Company</li>
            <li>Location</li>
            <li>Yearly Salary Adjusted for Cost of Living</li>
            <li>Yearly Bonus Adjusted for Cost of Living</li>
            <li>Stock Option Shares (SOS)</li>
            <li>Wellness Stipend (WS)</li>
            <li>Life Insurance (LI)</li>
            <li>Personal Development Fund (PDF)</li>
            <li>Job Score</li>
        </ul>
        </td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 008</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 009</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 0010</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 012</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 013</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 014</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 015</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
<tr>
        <td colspan=2 style='display:center'><b>Test Case Number:</b> 016</td>
    </tr>
    <tr>
        <td>Preconditions</td>
        <td></td>
    </tr>
    <tr>
        <td>Description</td>
        <td></td>
    </tr>
    <tr>
        <td>Steps</td>
        <td></td>
    </tr>
    <tr>
        <td>Expected Result</td>
        <td></td>
    </tr>
    <tr>
        <td>Pass/Fail</td>
        <td>Not started.</td>
    </tr>
</table>