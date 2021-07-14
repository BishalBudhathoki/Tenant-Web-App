# Tenant-Web-App
The app that we are developing is called “Hamro Ghar” which literally Means “Our Home”. The idea behind the app comes from the problem general people faces when that time of the month comes to pay the landlord. Issues like past remaining amount or like unclear transaction that occurred. Now from this app that we are developing, our intention is to solve that issue providing landlord to manage tenant details along with all bills and past transaction record. Now this will provide clarity in every transaction that occurs, and every detail are backed up on the cloud, so no data is stored on the device.

# Motivation
The people in Nepal faces issues in every month to month transaction when need to pay monthly rent, water bill, electricity bill, other bills to the landlord/owner. There can always be some past transaction issue or the issue in the current transaction. Now with the help of this every detail can be shared with the tenant so every transaction is seamless and clear. This issue is not always the same with other country people and for now this app is targeted to the people in Nepal and more generally towards the people in cities. And not every house will have this kind of issue but to make transaction clear between both parties is always a plus point. </br>

# Summary
Summary of task: The Major tasks to be completed in this app are as follow:
1.	Add details of tenant in Mongo Database.
Every details of the tenant are stored in the Mongo database that include their Name, permanent residency, Citizenship Number and more. Local storage is also used in some constraints. So, the app is real-time.
2.	Display data of Tenant from Mongo Database.
Stored data of the tenant is retrieved from the database only and displayed to the user.
3.	Bill calculation for every user on per month basis.
Bill calculation include Room/unit/apartment rent, drinking water bill, miscellaneous bill, electricity bill with details like per unit charge and the date the bill is to be paid or paid.
4.	Storing the bill calculation data in new Collection in database that includes user data and user ID.
Every bill calculated data is stored in the new collection database and managed using the user ID and their data.
Every transaction made using the app is recorded on the cloud and that can be retrieved to view.
5.	Delete Tenant.
Tenant after leaving the unit can be deleted from the database so only the active tenants’ details can be accessed and managed. The data is not deleted, it will be on the database, only the status is changed and not displayed. If future dispute arises then we can settle the dispute by going back to the history records.

# User Interface Prototypes
The user interface prototype that we came up with contains a n app name at the top of the screen then have a 2 * 3 grid that contains various options to deal with along with the icons/images for better user interface. So, the protype screenshots are as follow:
<p align="center">
<img src="https://github.com/BishalBudhathoki/Tenant-Web-App/blob/master/Screenshots/1.PNG"> </br>Home Page
</p>

<p align="center">
<img src="https://github.com/BishalBudhathoki/Tenant-Web-App/blob/master/Screenshots/2.PNG"> </br>Add Tenant Detail Page
</p>

<p align="center">
<img src="https://github.com/BishalBudhathoki/Tenant-Web-App/blob/master/Screenshots/3.PNG"> </br>Calculate Invoice page prototype
</p>

<p align="center">
<img src="https://github.com/BishalBudhathoki/Tenant-Web-App/blob/master/Screenshots/4.PNG"> </br>First figure is validation alert for Joined Date not selected or provided.
Another figure is validation alert for tenant name.
</p>

<p align="center">
<img src="https://github.com/BishalBudhathoki/Tenant-Web-App/blob/master/Screenshots/5.PNG"> </br>First figure is validation alert for Citizenship Number
Another figure is the tenant’s details after selecting the tenants name from the list.
</p>

<p align="center">
<img src="https://github.com/BishalBudhathoki/Tenant-Web-App/blob/master/Screenshots/9.PNG"> </br>First figure is About Us page.
Another figure is validation alert for Invoice saved successfully in the local storage and the database.
</p>


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Davis, O. (2020). What are Market Demographics? - Definition & Overview. Retrieved 21 October 2020, from https://study.com/academy/lesson/what-are-market-demographics-definition-lesson-quiz.html <br /><br />
RentPal – Property Manager, Rent Manager, Rental Management, Apartment Managemen. (2020). Retrieved 21 October 2020, from https://apps.apple.com/us/app/rentpal-property-manager-rent-manager-rental-management/id1028943100 <br /><br />
Ward 09. (2020). Retrieved 21 October 2020, from https://www.kathmandu.gov.np/sites/kathmandu.gov.np/files/ward%209.pdf  <br />
