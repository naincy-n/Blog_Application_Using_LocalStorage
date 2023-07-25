# Blog_Application_Using_LocalStorage
A blog application is a Content Management System designed specifically for bloggers that simplifies the process of creating and publishing blog content. This Project aims to create a Blog Application using Local Storage specifically for Personal Blogging.

# TOOLS USED-

• HTML & CSS

• Bootstrap - A CSS Framework

• JavaScript – LocalStorage

# PROCEDURE
In this Project we are implementing LocalStorage in a blog application for storing a blog using an HTML form. Here are the steps for implementation-

• STEP 1- Create an HTML form to capture blog content from the user. This form should include fields for blog title, Blog Image, category, and blog content.

• STEP 2- Create a JavaScript file to handle the form submission and LocalStorage implementation.

• STEP 3- In the JavaScript file, create a function that will execute when the form is submitted. This function should get the values entered in the form fields and store them in an object.

• STEP 4- Create a variable to store the object as a JSON string.

• STEP 5- Use the setItem method of the LocalStorage object to store the JSON string in LocalStorage. Use a unique key name to identify the blog post.

• STEP 6- Add an event listener to the form submission button that calls the function created in STEP 3.

• STEP 7- When the form is submitted, the function should execute, store the blog post in LocalStorage, and provide the user with a success message.

• STEP 8- To retrieve the blog post from LocalStorage, create a function that uses the getItem method to retrieve the JSON string, parse it into an object, and display the blog post on the page.

• STEP 9- Add an event listener to the page load event that calls the function created in STEP 8

# RESULT

HOMEPAGE

![image](https://github.com/naincy-n/Blog_Application_Using_LocalStorage/assets/78255083/af54ea8d-8182-455a-8e83-98e92fba594a)
![image](https://github.com/naincy-n/Blog_Application_Using_LocalStorage/assets/78255083/317f355f-fea4-4c04-8d34-3d9871f3f494)
![image](https://github.com/naincy-n/Blog_Application_Using_LocalStorage/assets/78255083/9e5969b3-b803-4d94-bf1c-d40ba6a6ef56)
![image](https://github.com/naincy-n/Blog_Application_Using_LocalStorage/assets/78255083/0ba3bd57-d5db-4d33-8fd4-041c403e1257)

MODAL

1.	On clicking “ADD NEW BLOG,” A Modal will appear on your screen as shown below.

![image](https://github.com/naincy-n/Blog_Application_Using_LocalStorage/assets/78255083/f96c5b99-722c-4707-b850-2eb505d83f40)

2.	Fill the details asked in the modal about your blog.

3.	Save Changes.

4.	Data is now saved in Local Storage

![image](https://github.com/naincy-n/Blog_Application_Using_LocalStorage/assets/78255083/d0c2d4e2-4bd7-41fd-ac9e-32d1cc581dbf)

5.	A New Blog will appear on your Home Page.

                                                                                  ~NAINCY NAIYAR
