**Note** that all of the examples and information displayed in this documentation are made up and do not use actual client information. The documentation guides the users about various aspects of this application.

<br>

## User Guide

This section provides a walkthrough of the HPT Clients Tracker user interface and its capabilities.
<br><br>

### Landing Page

The landing page is the first thing the users see upon visiting the root URL of the site.

Users are prompted to enter their username and password for login. Only users with the admin privilege can register new accounts.

![screenshot of the landing page](doc/landingwithoutlogin.png)

<br>

### Home Page

After you log in, you'll see the main page. Here, you can find important company news, links to other company sites, and recent updates about our services. You can also easily change your password from this page if you need to

![screenshot of the home page](doc/landingwithlogin.png)

<br>
<br>

### Customer Page

To access the Contact information, navigate to the Contacts menu in the navigation bar. The dropdown menu for Contacts contains two options - Customers and Providers. Selecting either option will take you to the respective page. Here, you can view details of all active customers or providers and even send an email to all customers or just one. Remember, Providers can be satellite or internet service providers. On these pages, you can change, remove, or look over customer/provider details.

![screenshot of active customer](doc/activecustomer.png)
<br>
<br>

To **modify** the customer information, select the "Edit" button. This will redirect you to the appropriate page. Utilize the form provided to make the necessary changes. Additionally, users can mark the customer as inactive on this page.

![Update Customer ScreenShot](doc/editcustomer.png)

To **add** a new customer, click on the "Add Customer" button located at the bottom of the page or simply navigate to the Admin dropdown in the navigation bar and click on "Add Customer". Fill out the required information and submit the form to create a new customer record.

![Add Customer ScreenShot](doc/addnewcustomer.png)

**Note** that if you deselect the active checkbox in the edit customer or edit provider page, the customer or provider will be marked as inactive and will no longer be displayed on the customer or provider page. To access inactive customer or provider details, navigate to the "Archive" page.

<br>

**Note** that the Providers page closely resembles the Customers page and serves to store the contact information of various vendors including Satellite Controllers and Internet Service Providers.

<br>

Below is the screenshot of the "Provider" page

<br>

![Provider Page ScreenShot](doc/activeproviders.png)

### Services Page

Select the "Services" tab on the navigation bar to access a list of active services. This page will only display services associated with active customers. Users can access the active customers on the left sidebar to review the services they are currently running.

![screenshot of the services Page](doc/services.png)

**Add Services**
<br>
To add a new service:
Navigate to the "Services" page and select the "Add Services" button or access it from the "Admin" dropdown in the navigation bar.
Complete the form with the required information, and upload any necessary files if desired.
Once complete, submit the form to finalize the process.

> Please note that by default, all services are designated as active services.
> However, users have the option to select the service type as "Upcoming Service" and activate it from the List Services page.

![screenshot of the addservices Page](doc/addnewservice.png)

**Individual Service**
<br>
By selecting the customer button on the left sidebar, the application will display the services associated with that specific customer
<br>
On this page, users have the ability to view and archive the service. Additionally, users have the option to add the service to Spectras, an external device that is utilized for monitoring services. Once added to the Spectras application, users can access the latest graph of the service. This feature allows for quick and efficient monitoring of the service status and aids in troubleshooting during issues and outages.

![screenshot of the individual services Page](doc/individualservice.png)

<br>

> Screenshot of the individual service page that displays an incoming service.
> To activate the service, simply click on the "Set Active" button.

![screenshot of the individual services Incoming Page](doc/individualserviceincoming.png)

<br>
Click on the "Show Details" button to view the service's details.

![screenshot of the show details page](doc/servicedetails.png)

<br>
To add the TX/RX services to LPT Spectras, select the "Add to Spectras" button. After successfully adding the service to Spectras, the button label will change to "Remove (TX/RX)." If you wish to remove the service from Spectras, select the "Remove" button.

![Screenshot of add to spectras page](doc/successfuladdtospectras.png)

<br>
<br>
Please take note that the "Archive" button on the service page will deactivate the service and remove its snapshot from Spectras. Nevertheless, information on inactive services can still be viewed on the "Archives" page.

<br>
<br>

Click on "Display Plot" button to view the latest updated graph of the service.

![screenshot of the plot](doc/spectrasplot.png)

### Antennas

Select the "Antenna" button on the navigation bar to view, edit, and archive existing antennas.

![screenshot of the antenna page](doc/newaddantennas.png)

**_Click on Upload to add new files, or Update to modify existing files._**

To add a new antenna, navigate to the "Antenna" page and select the "Add Antenna" button or access it from the "Admin" dropdown in the navigation bar.

![screenshot of the antenna page](doc/addantenna-1.png)

To upload files for antennas, simply click the 'Upload Diagrams' button located on the right-hand side of the page. The uploaded files will then be displayed in the 'Show Details' section of the respective antenna.

![screenshot of upload diagrams](doc/uploaddiagrams.png)

<br>
<br>

### Facility

In the facility dropdown, you'll find options for 'cross-connects' and 'site-drawings'. Choose 'cross-connects' if you want to make, change, or store cross connections for customers.

![screenshot of the cross connects customer](doc/cross-connects.png)

For individual shelter layouts within our location, select 'site drawings' to upload, see, or edit the diagrams.

![screenshot of the site drawings](doc/site-drawings.png)

### Archive

To access information on inactive entities such as Customers, Providers, Services, Shelters, Cross-Connects and Antennas, navigate to the "Archive" page via the navigation bar. Once on the page, simply select the desired entity and click on "Find" to display the related information

![screenshot of the archive page customer](doc/archiveantenna.png)

![screenshot of the archive page](doc/archiveservice.png)

Only users with "ADMIN" privilege can delete services permanently
![screenshot of delete service page](doc/deleteservice.png)

**_To reactivate an entity, simply click on the "Activate" button._**

### Helper

In the 'Helper' dropdown, there are three options: 'Frequency Lookup', 'HPT Calculator', and 'Audit Antenna'.

With 'Frequency Lookup', you can type in a full or partial frequency to see which customer is using it.

![screenshot of dreq lookup page](doc/freq-lookup.png)

The 'HPT Calculator' lets you convert between dbm and watts, and also use the 'LO Calculator' to switch between L band and RF frequencies.

![screenshot of HPT calculator](doc/hpt-calculator.png)

Through 'Audit Antenna', by entering the Antenna type and Band, you'll get a list of all services using that particular antenna

![screenshot of audit antenna page](doc/audit-antenna.png)

### Admin

The "Admin" dropdown button on the navigation bar provides access to the functionality for adding customers, providers, services, cross-connects and antennas. Additionally, it includes options for the administrator to manage user accounts.

![screenshot of the Admin page](doc/admindropdown.png)

<br>

Additionally, the admin user is capable of accessing information about recently altered services and the individuals accountable for the modifications. Upon confirmation by the administrator, the service in question will be excluded from the roster of recent updates.

![screenshot of the Admin notification](doc/adminnotifs.png)

<br>
The "Manage Account" page is accessible only to users with an "Admin" role and allows them to delete/register users. This page is not visible to users with different roles.

![screenshot of the manage account page](doc/manageaccounts.png)

<br>

### SignOut

To sign out, simply click on the username located at the top right of the navigation bar and select "Sign Out"

![screenshot of signout page](doc/signout.png)

## Contact Me

**HPT Clients Tracker** is designed, implemented, and maintained by [Ujjwal Gautam](mailto:ujjwalgautam00@gmail.com)

<br><br><br><br>
