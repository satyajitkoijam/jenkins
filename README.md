# jenkins

Steps
1.  Open Jenkins URl or localhost:8080
2.  Create new pipeline Job. Example Name : admin-seejob
3.  Add some parameter.
    a. choice Parameter 
        gitUrl = https://github.com/satyajitkoijam/jenkins-jobs-admin.git
    b. choice Parameter
        gitBranch = master
    c. choice Parameter
        dslScripts = jobs/admin/aws_seedjobs.groovy
4.  Pipeline Script
    copy groovy file content from 'jobs/admin/admin.groovy'

