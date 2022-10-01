# squire
Squire interview project

Steps in development:
1. read 'README.md' and 'README.dev.md' in multiple interations to understand what is requested
2. install Visual Studios and Docker.  
3. Attempt instructions in 'README.dev.md' on launching Docker environment
    a. experienced error, => ERROR [build 5/5] RUN dotnet publish -c Release -o publishedOutput with exit code 1
    b. attempted to troubleshoot by reading the log details and researching similiar errors with ASP.net
    c. removed project folder and started again.  Removed all existing images and containers from past attempts.
    d. attempted to load 'localhost:8100/doc/swagger' and 'http://localhost:8100' but got 'This site can't be reached' response each time
4. Launched project AppCode in Visual Studios that launched 
