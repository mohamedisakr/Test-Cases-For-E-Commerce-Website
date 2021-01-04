#### Reusable methods or page classes: Create reusable methods wherever you discover repeatable code. Don’t duplicate an equivalent thing multiple tests.
#### Data driven: Test data like URLs / User Names and Passwords are maintained in properties file or Excel files. Don’t hard code everywhere.
#### Explicit waits: Thread sleep delays everywhere in test scenarios. Also reduce the performance. So attempt to use Explicit waits.
#### Variables names should be meaningful.
#### Try to use public API’s rather than creating more utility files from scratch.
#### Reporting: Don’t print results using System.out.println. Always use Reporting mechanisms.
#### Headless test execution support when there's a necessity
#### Don’t hard code absolute paths given to files utilized in the framework, instead of just putting the files into a folder relative to the framework.
#### Data should read from test scenarios but not in page classes.
#### Try to reduce Unnecessary program loops within the code.
#### Test framework should organize into well-defined packages
#### Pages: Where page classes reside
#### Test: Where test reside
#### Utility: Where utility classes resides. like reporting and file reading classes
#### Documentation on deploying the test framework
#### Logging facility for frameworks, when something goes wrong
#### Base driver support to run in multiple browsers
#### Good naming conventions for page class and test class naming
#### Tests should be independent when executing
#### Detailed reports on test executions and failures
#### Use design patterns and principals
#### Use BDD: But this is often not mandatory always
#### Screen shots on failures - Helps failure investigation easy.
#### Use dependency management like Maven for Java, Nuget for .net, PIP for Python
