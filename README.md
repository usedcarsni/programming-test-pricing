# Programming Task - Pricing
This task is designed to give us an understanding about your workflow and how you would currently approach a PHP project. We aren’t looking for one ‘ideal’ solution – approach it how you feel most comfortable.

You may use any frameworks and packages and technology to help support your solution, but the core business logic should be written yourself.

You will be submitting your project via GitHub. Please configure your project appropriately, making frequent, commented commits.

> Hint: Make sure your GitHub repository is set as private!

### Overview

Our website allows car owners to privately list one-off adverts for a car that they are selling. Adverts are charged depending on a number of conditions. We require a small PHP (micro)service to calculate the cost of privately listing a vehicle on the website for sale. Note that a listing expires after 2 weeks.

### How the system should work

-	If the vehicle to be listed is valued at under £1000, the listing is completely free.
-	If the vehicle is valued between £1000 and £5000, the listing is £7.99
-	If the vehicle is valued over £5000, the listing is £14.99
-	If the same vehicle is being listed by the same customer within 30 days of the listing expiring, they receive a 15% discount on the new listing.
-	If a different vehicle is listed by the same customer at any time, the listing price is standard.
-	The system should reject any invalid requests with an appropriate error code and message.

### API Requests

We have provided examples of the request JSON that your service should expect. Your solution will be tested against each of these.

### Additional Guidelines

-	Prices should be rounded to the nearest penny.
-	Please provide a short ‘readme’ document in your solution to indicate how to set up, configure and use your project.
-	An ideal solution would be easily extendable if further rules were required in the future. Please allude to this in your code and documentation.
-	Basic performance should be considered, but do not worry about adding a caching layer.
-	Unit tests are not a requirement of this task but would be welcomed if included.

### Submission

-	All submissions should be made via a private repository on Github, granting access to darren@usedcarsni.com
-	Once access had been granted, please email darren@usedcarsni.com to confirm.



