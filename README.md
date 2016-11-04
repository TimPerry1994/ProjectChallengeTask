# ProjectChallengeTask

Plan of action:

1) Connect a master/agent with a shared folder from the host
2) Write a module to install MS SQL 2016 on the agent, make sure it is properly set up.
3) Write a new module for Active Directory - If this needs other dependencies, ensure they are present as well.
4) Write a module for Sharepoint Server 2013 trial. As above, check for other dependencies

Foreseen issues:

 - VM runs out of memory or does not have enough processing power. If this happens, either create a new agent and install  Sharepoint on the new one to connect with the original or give the original more processors/RAM
 
 - Run into additional dependencies. If this happens, try to find and install them first.
