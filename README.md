# ECE444-F2022-Lab6

Nicola Lawford


## Test cases in group repo

The test case I added in my group project can be found here: https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-2-pitcrew/blob/main/Education_Pathways/tests/test_app.py#L63-L70


## Pros and Cons of Test-Driven Development (TDD)

TDD is an approach to software development where a developer will write test functions for a feature before writing the feature itself. This way, the developer can ensure that the requirements are met fully by the feature.

There are many pros to taking this approach as opposed to traditional testing, which is done after development. One benefit is that if there are delays to deployment, testing cannot be skipped since it has been integrated into the development process for each feature. As well, time is saved, because a feature and test are designed by the same person, rather than having a separate person responsible for testing who needs to learn the details of how a feature was designed before implementing the test. This is especially good in conjunction with Agile methodologies. Another benefit is that the developer can edit or add to the test as they work on the feature, because they may encounter some edge cases or discover better implementations as they work. Again, this works well with Agile methodologies where pivots can happen rapidly and stories can change based on user needs.

TDD also has several cons. First of all, with many tests for each feature, the code base can become quite large, especially if test cases are complicated. As well, with each developer focusing on a test for their own feature, there may be too much focus on unit testing, and not enough integration or end-to-end testing. Furthermore, depending on the test design, refactoring an implementation may cause pre-existing tests to fail. Tests do not necessarily reflect the user experience, especially if they are automated, such as in pytest. Furthermore, the tests themselves could also have bugs in them, so debugging becomes less of a linear process, with more possible points of failure.

When done correctly, and when developers are aware of potential pitfalls, TDD can be very helpful to a software team.