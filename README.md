# WeBest-Support
Its an online ticket based support system 

##WeBestSupport System (SPA) Using MEAN STACK

##Project Description :Support is an essential feature for any platform, and dedicated support is best approach in case you are really concerned 
about the user experience of your platform. The Aim of the project is to create an online ticket based support system, 
which should be usable by any kind of platform to get support queries from their users and resolve them.

##Features of this application:
-> Users can register themselves and be a part of the support system.
-->Users can post their queries in support portal.
-->SupportTeam(Admin) who will reply for user queries.
-->There is chat like panel for interaction between user and admin.
-->Both admin and user can close or reopen a particular ticket.
-->User is provided with additional feature to delete the query.
-->Whenever some reply is given to that ticket user will receive email notication or 
-->WHenever ticket is closed notification email is sent to particular user email address.
-->In the user dashboard queries are listed with an option to delete ,reopen or close the query.
-->Admin is provided with facility to close the ticket.
-->Dashboard has option to filter queries on the basis of ticket status (open/closed/AllQueries).


##Assumptions made while building this application -
Access to admin panel can done using an account with following credentials -

name : Admin 
email : admin@domain.com 
Password can be given as per user wish.

#Prerequisites of using this application -
1)nodejs  
2)mongodb 
should be installed and running.

#Email Notificaton:
Set the username :'senders email'
password:'email password' 
in the mailing events (server/app/controllers/ticket) 
in order to successfully deliver the notification emails to the user.
