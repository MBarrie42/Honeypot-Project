# Honeypot Project

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment 

A cloud hosting provider was first need to do the deployment. Google cloud was used and an SDK was installed. After the SDK was initialized, a VM was created and made accessible via SSH. A script later was installed on to the VM to load the external IP in the browser.
<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment

Dionaea is a honeypot that recieves lists of attackers and malware. 

<img src="Dionaea Honeypot Deployment.gif">

### Database Backup

The database MHN-Admins use is JSON. The JSON file records the date of the attack, source ip of the attack, the source port, and identifier number.

## Notes

I had issues with the instances and the ssh. Many times the connection timed out and I had to restart.
