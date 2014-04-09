This is a Pentaho Kettle Job that finds SP cases to bugs which developer has already fixed.

###Parameters:

*user* - user name of Pentaho JIRA user(jira.pentaho.com)

*password* - JIRA password

*sprint_id* - ID (not name) of the sprint the user has access to. To find it, open any SP case, hover Active Sprint link and look into it's URL

*sprint_team* - JIRA Spring Team name (e.g. Pervach) 

###Output:

[Sample report](report.html)

####Note:

'Developer fixed an original bug' == 'developer who set label 'code-complete''. 
