# HosAppointmentSys
Hospital Appointment System

An OpenSource Smart Appointment system to check doctor's availability, developed on LAMP Stack for devpost openshift hackathon.
Feel Free to contribute.

#Exporting the database:

    $ mysqldump -u username -p[pass] HosAppointmentSys > has.sql

#Importing the database:

    $ mysql -u username -p[pass] HosAppointmentSys < has.sql     
    
    Note: Create a database named **HosAppointmentSys** before running above command

