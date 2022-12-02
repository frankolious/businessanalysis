## Test cases are step-by-step instructions, including specific inputs and conditions, that testers follow to validate the system’s functionality as part of the business analysis and implementation. They also include the expected result. You and the project team can create hundreds — if not thousands — of test cases when supporting the testing effort. The larger the project, the more test cases you create. To create a test case, do the following:

Identify the test items.

Read through whatever project artifacts you have available to identify the test items. These documents may include the scope diagram, use case diagram, user stories, workflow diagrams, prototypes, and so on.

If you’re working on a program to search for airfares, the use case diagram may tell you that passengers are able to search for flights, which means you want to be able to test search for flights to ensure passengers can do it.

Create the input and output specifications.

Use the artifacts you reviewed in Step 1 to determine what data you need to put into the test and what the expected result is. When searching for flights, what inputs do you need to have in order to get the output? The answer may be something like the flight dates and times and the origin and destination locations.

Define the environmental needs.

These items come primarily from your nonfunctional requirements. For example, you may have a configuration requirement that states the solution must be able to run on iOS 5.1 and iOS 6. So you create a test case to operate under the iOS 5.1 environment and another for the iOS 6 environment.

You may also need to consider whether this new flight searching system works only on regular computers or is being rolled out as an app for tablets.

List any special procedural requirements.

If you need to process anything special, such as if you have to go outside the test to set something up prior to continuing the test procedure, list that here.

For example, suppose the interface with the master list of all flights isn’t working; in that case, you fake the test by mocking up flights in the master flight database between the steps for submitting the flights and receiving the results.

Document any inter-case dependencies.

List any other test cases or other artifacts that the test case must include to be complete. The flight searching system may contain dependencies on the list of airports and airlines in the system.

List any approvals.

Include who needs to approve the test case.

Test case writing is an iterative process, which means you go through it one piece at a time. Walk through the steps with one artifact (say, the use case diagram) and get the information out of that. Then, go through the six steps again with another artifact (such as the prototype) to uncover more test cases.

If you’re having a hard time uncovering test cases for any requirements or artifacts it may be because they aren’t written clearly or in enough detail. You may have to go back and redefine the requirement.

### What Are the Types of Acceptance Testing?
There is a number of acceptance testing types differing by their function and methods of application. The main 6 acceptance tests are listed below.

- User Acceptance Testing (UAT)
- Business Acceptance Testing (BAT)
- Operational Acceptance Testing (OAT)
- Contract Acceptance Testing (CAT)
- Alpha Testing
- Beta Testing

1. User Acceptance Testing (UAT)
User acceptance testing represents test scenarios designed to focus and measure the functionality of a system. Real UAT examples can be real applications of a product to ensure its compliance with the business usage requirements from the end-user perspective. The tests should be developed and performed by the end-users or the general audience. In software development, they are usually done by quality assurance engineers.

2. Business Acceptance Testing (BAT)
The scope of the business acceptance testing (BAT) is assessing whether the product is aligned with the business requirements and needs. BAT tests rely on a deep understanding of customer behavior and require industry knowledge of the testing team members. The primary goals of the BAT are to reduce major reworks and cut project costs.

3. Operational Acceptance Testing (OAT)
Operational acceptance testing (OAT) focuses on both the functional and non-functional requirements of a system. These can be related to the product’s functional stability, reliability, and operational readiness. Examples of OAT can be disaster recovery, maintenance, and security procedures.

4. Regulatory/Compliance Acceptance Testing (RAT)
In regulation acceptance testing (RAT), a system is measured whether it meets legal, safety, and governmental regulations. These acceptance criteria are pre-determined and documented in a contract.

5. Alpha Testing
The scope of the alpha testing is to test the operating system prior to its delivery to the customers. The tests are performed by internal staff in a testing environment before taking it to test at the customer’s site.

6. Beta Testing/Field Testing
Beta testing, also known as field testing represents tests performed at the customers’ sites. Customers are using the product at their locations and provide feedback which is essential before releasing it to the general audience.



### What Is the Acceptance Testing Process?
An effective acceptance testing process includes the following 5 major steps.

1. Business Requirements Analysis. All documentation referring to specifications, business requirements, and use cases is thoroughly analyzed.

2. Design Acceptance Test Plan. The plan should include the scope of the testing, defined entry and exit criteria, detailed acceptance tests design manner, testing schedule, and other details about the agreed-upon testing procedure.

3. Design Acceptance Tests. Each acceptance test scenario should explain what has to be done and it should be written to reference a specific business requirement. 

4. Acceptance Test Bed Set Up. Refers to the configuration of the tests execution environment including any required hardware, software, operating systems, etc.

5. Acceptance Test Data Set Up. Requires the inclusion of all production data as test data. The data should be precise, exhaustive, and well-documented.




### What Are the Best Practices to Conduct a Successful Acceptance Testing?
Conducting acceptance testing must ensure that a system is compliant and sufficient for business usage. Below you can find the best practices for a successful acceptance testing cycle.

Identify Target Users.
Create Acceptance Test Plan.
Develop and Document Test Cases.
Set Up Testing Environment.
Define Reporting Standards.

### What Are the Mistakes to Avoid during Acceptance Testing?
The common mistakes that occur during acceptance testing are included below.

Highly technical details. Including too many technical details about the tests implementation may make them hard for the testing audience to comprehend.
Wrong testing audience. Not finding suitable testers hinders the testing itself due to their lack of interest in the system.
Lack of enough data. Not providing the testers with sufficient production data can render the acceptance testing unrealistic.