# Business-Analysis-Sample
This is requirements of an educational web site and me and my teammates business analysis training graduation project. It contains requirements, images, use-case scenarios, and uml diagrams to present to web developers and testers. The planning stages of the web site were carried out using the Agile - Scrum methodology. JIRA was used to write and plan requirements, Figma used to make the mockup of the site and draw.io platform was used to create UML diagrams. 
Firstly, in order to avoid system complexity, we created our sprints as "System Login, Home Page, Top Menu and Plugins, Profile Information" based on four different main elements that make up the website. Then, we created the analysis and management planning of the process by distributing 24 different system components to the relevant sprints. Finally, the elements of the relevant components were planned down to the smallest detail by holding repeated meetings with the web developer and software testing teams in order to prevent errors in the system, and requirements were created based on the results.
Here, I thought of giving you a brief information about the contents of "My Personal Information", not the entire system, but a small part of the system for which I created the requirements on my own.

![my_personal_information](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/fd7b31ee-b86b-47b4-86de-8582b136b70d)

Here, the structure and elements of the "My Personal Information" sub-page, which is the first content of the "Profile Information" page, are shown. There are one profile photo area, seven alphanumeric fields, one date field, three drop-down lists and one save button.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/db80c97e-ee6b-4638-ae3f-a878299110ca)

Here you see the normal state of the phone number field, which is one of the most complex elements of the content.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/d52d3caa-90e4-4a5d-81ec-44da0f413692)

When you click on the empty rectangle to select the phone number area code, a pop-up window appears above the rectangle like this.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/a07baa80-958d-4115-9e39-b02bd7bb5532)

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/a98f0a06-11c0-407a-b47f-8d66f9b931c8)

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/a7f435eb-63e6-4b34-a672-269a468f638b)

The warning text changes depending on the selected area code. Notice that there are ten asterisks representing ten numbers.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/993951e9-3540-46d5-91a9-dd413d9bd67d)

The presence of an asterisk seems to make it much easier to notice that the phone number is missing. Also the frame is still red.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/7ad0d960-c928-49e9-b885-166a00d0b101)

Here is a representative image of the phone number field completely and correctly filled out.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/bba3faa7-c16e-4ab6-ba0c-38b0c489ab43)

Here is the use case diagram of the "Profile Information" page. It is shown here that in order to save personal information, the user must first open the home page. In addition, subpages are shown as extensions of the upper page.

![image](https://github.com/ProfUgur/Business-Analysis-Sample/assets/148859613/712aba3b-0506-4fe0-96b6-39a111b4000e)

Shown here is the “My Personal Information” subpage activity diagram. It can be seen that the elements in the system are generally independent of each other. Additionally, it is understood that no order is observed when entering personal information. This ensures that each element does not affect the other in terms of errors, reduces the complexity in the system, and facilitates coding and testing. As a result, time, labor and costs are saved.

That's all I want to say. If you want to get more information about all the contents, you can download and review the file.
Thanks.
