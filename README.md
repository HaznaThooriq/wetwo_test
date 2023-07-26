### Notes for This Project
1. For this project, I'm using Katalon version 8.5.5. Katalon uses Groovy, a language built on top of Java, and has to load many libraries for parsing test data, test objects, and logging. So, it may be a bit slower as compared to Java for long test cases with hundreds of steps.

![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/f0e252fa-cc5d-4e23-aef0-4246dc3204a0)
Image 1. Example of groovy language to code automation in manual mode

![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/031cd091-cd1d-4d05-b4ea-8f9c936f1551)
Image 2. Example of groovy language to code automation in script mode

2. Katalon was chosen because the programming language is very easy to understand. The script is simple and the dependencies for validating testing are very easy. it will also make it easier for other users if they want to run the automation testing script because it does not require adjustments to the computer environment (such as the version in each dependency).

3. In this project I used the page object design pattern, the page object design pattern has many advantages, one of which will reduce duplication of code/objects and will certainly make it easier for code maintenance.
![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/f3ae7742-ee9c-47a5-8857-cac0ea01db23)
Image 3. Page Object Model Structure

4. For the repository object in this project, I fully use xpath. For selecting the repository object itself, there are many examples such as using class, id, or other css selectors. For the wetwo app, I found that each elements can be accessed using class as css selector, but there is no specific id or data-testid for each component, so here I use the xpath of the html element hierarchy, maybe my suggestion is for the dev front end runchise to provide a unique id or data-testid for each component
![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/ebeef577-da99-44fb-8a46-f956826b1d2c)
Image 4. Xpath example

5. Previously for allow locations, because the location setting action does not include objects from automation testing, so the settings are from the project directly.
![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/e1e23dfe-57fa-4255-982d-d921eca5b420)
Image 5. Example to allow geolocation

### How to Run
1. The test case for this project is a case for validating the quantity of the product added to the cart on the Wetwo website.

2. To run the project, you can use the shortcut ctrl+shift+A or by clicking the runner icon and selecting the browser to run
![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/c3ab5b78-96c0-43ba-ab91-ea46f6c96306)
Image 6. How to Run

![image](https://github.com/HaznaThooriq/wetwo_test/assets/26196568/438f73c5-ae73-499d-b340-97c77eae2249)
Image 7. Example of running log reports





