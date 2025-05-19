# Exercise-8-Basic-Web-Automation---Fill-a-Web-Form

## Aim
To create a UiPath workflow that automates the process of filling out a basic contact form on a website and submits the form using Web Automation techniques.

## Materials Required:
```
1.UiPath Studio (Community or Enterprise Edition).
2.Google Chrome or Microsoft Edge (with UiPath Extension Installed).
3.A sample contact form URL (e.g., https://www.seleniumeasy.com/test/input-form-demo.html or any dummy form).
4.Internet connection.
```

## Procedure:
```
Step 1: Launch the Browser:
         Open UiPath Studio and create a new project called WebFormAutomation.
         Drag and drop the Use Application/Browser activity.
         Indicate the browser window or enter the form URL manually in the Application Path:
~~~
https://form.jotform.com/242550815060449
~~~
Step 2: Fill Form Fields:
    Inside the Use Application/Browser, add multiple Type Into activities for each field.
~~~
Example:
Field	Type Into Value
First Name:	"M"
Last Name	:"Sushiendar"
Email: "msushiendar@gmail.com"
Message:"Form Filled"
~~~
   Use Click Before Typing and Activate options in Properties for accuracy.

Step 3: Select Dropdown (Optional):
        Use the Select Item activity to choose a state or country from a dropdown if present.
Step 4: Submit the Form:
        Use a Click activity to click the Submit or Send button on the form.
Step 5: Add Delay (Optional):
        Add a Delay activity if the form takes time to load or submit.
```

## WORKFLOW:
![Screenshot 2025-05-19 214529](https://github.com/user-attachments/assets/907a4262-7a4f-4fe1-9fa9-d3882762c745)
![Screenshot 2025-05-19 214543](https://github.com/user-attachments/assets/413d634a-494b-41a2-a3ab-1457c3ce573c)
![Screenshot 2025-05-19 214558](https://github.com/user-attachments/assets/7a807810-4d28-495d-8c0a-528cab25a33b)
![Screenshot 2025-05-19 214612](https://github.com/user-attachments/assets/95cb986a-b969-4798-a3bc-60f1354bb597)
![Screenshot 2025-05-19 214622](https://github.com/user-attachments/assets/0b428fd8-ed69-4200-9d33-8af28ac1585d)
![Screenshot 2025-05-19 214628](https://github.com/user-attachments/assets/37aa3e8c-2e48-4cfe-b277-82d8125d40ae)

## OUTPUT:
![Screenshot 2025-05-19 214443](https://github.com/user-attachments/assets/1e1b0198-0a09-4216-92df-faf5507c2170)


## Result:
UiPath successfully automates form-filling tasks in a browser and submits a web-based contact form using Web Automation techniques.
