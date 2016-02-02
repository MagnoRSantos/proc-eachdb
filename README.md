# DBA Functions and Tools
The aim of this project is to collate useful SQL functions and tools that can be dropped onto a server and provide immediate benefit.

The tools that are to be collated should be
   * Business agnostic - have some use regardless of business processes 
   
Any tools developed should include
   * comments that describe each step
   * descriptions of uncommon functions and stored procedures
   * work within a 2008 r2 plus environment
     * any functions that are limited to a future/legacy version of SQL Server should be labelled clearly

Validation should be done of all code intially this will be done by submission to [Codereview.Stackexchange](http://codereview.stackexchange.com/)

# Red Tagging

Red tagging is a tool from Lean Six Sigma project management. The idea is within an environment all tools that have a question over whether they are being used.

Converting this to SQL is simple, add a logging table and then add a <stored procedure> to each of your stored procedures 