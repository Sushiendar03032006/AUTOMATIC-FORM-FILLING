# Exercise-8-Basic-Web-Automation---Fill-a-Web-Form

## Aim
To create a UiPath workflow that automates the process of filling out a basic contact form on a website and submits the form using Web Automation techniques.

## Materials Required
UiPath Studio (Community or Enterprise Edition)

Google Chrome or Microsoft Edge (with UiPath Extension Installed)

A sample contact form URL (e.g., https://www.seleniumeasy.com/test/input-form-demo.html or any dummy form)

Internet connection

## Procedure
Step 1: Launch the Browser
Open UiPath Studio and create a new project called WebFormAutomation.

Drag and drop the Use Application/Browser activity.

Indicate the browser window or enter the form URL manually in the Application Path:
~~~
https://www.seleniumeasy.com/test/input-form-demo.html
~~~
Step 2: Fill Form Fields
Inside the Use Application/Browser, add multiple Type Into activities for each field.

Example:

Field	Type Into Value
First Name	"John"
Last Name	"Doe"
Email	"john.doe@example.com"
Phone	"9876543210"
Address	"123 Sample Street"
City	"Chennai"
Zip Code	"600001"

Use Click Before Typing and Activate options in Properties for accuracy.

Step 3: Select Dropdown (Optional)
Use the Select Item activity to choose a state or country from a dropdown if present.
Step 4: Submit the Form
Use a Click activity to click the Submit or Send button on the form.
Step 5: Add Delay (Optional)
Add a Delay activity if the form takes time to load or submit.

## OUTPUT:
The bot will:
Open the web page
Fill out all fields with pre-defined data
Click the submit button

![Screenshot 2025-05-12 083934](https://github.com/user-attachments/assets/8c3f2030-105f-4ba8-9a0f-ecdeaeb2fe53)

![Screenshot 2025-05-12 084006](https://github.com/user-attachments/assets/4f53a675-55cb-4485-af21-9c36d20b53a3)

![Screenshot 2025-05-12 084016](https://github.com/user-attachments/assets/69cbe10d-4167-4f6a-a53f-8613bb2cc60e)

![Screenshot 2025-05-12 084046](https://github.com/user-attachments/assets/9e782ea9-d763-41be-8312-93dc307d62a8)

## Result:
UiPath successfully automates form-filling tasks in a browser and submits a web-based contact form using Web Automation techniques.
