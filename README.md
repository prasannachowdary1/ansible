# These are the ansible scripts for deploying applications from Nexus Repository Manager to targeted servers.
# Ansible in installed in Nexus Server (10.0.4.31).
# No need to change the entire script for deploying different Java Applications, Just change the list of targeted servers in hosts and vars folder in roles.
# In vars, we need to specify the application to be deployed with respective groupID, artifactID and Version. We can pass the verison Dynamically if required.
