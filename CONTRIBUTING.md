# Contributing to Overture Stack

Overture-stack is an open source project focusing on advancing genomic science through data management and visualizations. We love to see contributions from our community, so please let us know how we can improve or help us by putting up some code that we will help review.

## Bug Reports
If you think you have found a bug, we want to know! First, search our issues list on GitHub in case a similar issue has already been opened and add your comments or experience to that issue. If you think you have a new bug, please:
-   Submit a ticket with the `bug` template.    
-   Add the label `user-submitted`.    
-   Provide a repo with a minimal reproducible setup (if possible).    
-   Describe in as much detail, with steps, how to reproduce the bug.    
-   Include screenshots or specific commands in the bug report if applicable.  
-   Provide as much information as you can (e.g. context, os, browser). Anything helps when debugging.
-   Provide an example of what you think the expected behaviour should be.
 
The better your bug submission, that faster we will get to fixing it!

## Feature Requests
Have a feature you would love to see? Submit a ticket with the `Feature Request` template which describes the feature you would like to see, why you need it, and how it should work.
-   Add the label `user-submitted`.
-   Describe in as much detail as you can the feature request.
-   Include example usage or why it would be of benefit to users.

# Contributing Code
1.  You will need to fork the repository and clone it to your local machine. See [github help page](https://help.github.com/articles/fork-a-repo) for help.  
1.  Develop your changes, with tests included.    
1.  Run the test suite to make sure that nothing is broken.
1.  Submit a Pull Request against the `develop` branch of the repository.
1.  Add [Overture-stack/Reviewers](https://github.com/orgs/overture-stack/teams/reviewers) as a the reviewer for your PR.    
1.  Wait for one of our reviewers to get back to you about your PR. Any questions/comments or requests for changes will be completed through the PR request.
   
## Testing
1.  Test databases via test containers - no in-memory DB or OS specific services
1.  Tests should have no dependencies on any external services (ie. production micro-service)
1.  Tests DO NOT clear their data between runs, meaning that no test should rely on or expect a clean DB when running
    

## Code of Conduct
Please respect our [Code of Conduct](https://github.com/overture-stack/.github/blob/master/CODE_OF_CONDUCT.md) in all interactions, including ticket submission and pull request conversations.
