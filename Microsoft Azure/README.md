# Microsoft Azure

Microsoft Azure services do have unique functionality in comparison to other cloud services. Azure offers Cloud Active Directory services which presents unique opportunities to perform common Active Directory techniques. Furthermore, these services offer syncing services to onsite server which are acting as Domain Controllers, and compromising service accounts that perform these functions may lead to sensitive information disclosure including credentials.

Below is a whitepaper for an Azure AD Connect exploit which has been used in the HTB machine Monteverde. A basic writeup is also included in the CTF folder.

https://blog.xpnsec.com/azuread-connect-for-redteam/

Although this exploit is linked to Microsoft Azure, the exploit essentially is used for a local privilege escalation after you have gained access to a DC with this module installed. Therefore it does not directly link to testinng a Microsoft Azure tenancy, but is an excellent place to understand how Active Directory syncing tools can be exploited.
