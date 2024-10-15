# 
<h5>Directory</h5> 

<b>[Tech Portfolio Home](https://github.com/Jays1115/Jalen-Smith.git)</b>

# Suite Xperience - IT Architecture Explained

<p align="center">
<img src="images/SX_TechArchitecture.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br/>
Visualization of the IT Architecture for Suite Xperience <br/>
</p>

<h2>The Challenges This Architecture Solves</h2>
At the start of this business, the founders aimed to automate many of the repetitive tasks to create a more passive, hands-off operation that they could easily manage themselves. They sought to streamline various processes, including managing calendars across multiple online travel agencies (OTAs), automating guest communication, sending notifications to cleaning staff, optimizing pricing for their rental units, and setting up reminders for upcoming bookings. By automating these key tasks, the business could operate more efficiently, allowing the founders to focus on growth and long-term strategy while reducing the need for constant manual intervention.

<h2>The Solution</h2>
After extensive online research, I discovered Hospitable, a property management software designed for short-term rentals that offered all the automation features the founders were looking for. I linked their Airbnb and VRBO accounts to Hospitable, which enabled seamless calendar management, effectively preventing double bookings between the platforms.
<br/> <br/>
Within Hospitable, I customized and activated automated guest communication, integrated Hospitable with Pricelabs via an API to automatically manage the pricing of their units and set up SMS and email notifications for both the founders and their cleaners regarding upcoming bookings. One of the standout features of Hospitable allowed me to provide the cleaning staff with access to the reservation calendar for the unit they were responsible for. In implementing this, I adhered to the principle of least privilege, ensuring the cleaners could only view the information necessary to complete their tasks. I restricted their access to sensitive details such as financial information, calendars for other units, and any unnecessary data, enhancing both privacy and security while maintaining operational efficiency.
<br/> <br/>
Additionally, as a bonus feature, I connected their iCal calendars to their Hospitable calendar using a server link provided by Hospitable, allowing them to view their booking schedule on their mobile devices without needing to log into the Hospitable app. This added convenience streamlined their workflow even further.
