# Renton Technical College CSI-248
<br />    

<div align="center">  
    <img src="logo.jpg" alt="Logo">
    <h3 align="center">Guided Activity 2</h3>
</div>

This repository is a part of CSI-248 at Renton Technical College.

## Guided Activity 2 - Setup

1. Clone the repository to your local machine. (Do not use OneDrive for assignments in this course!)
2. Make note of the folder where you cloned the repository.
3. After you have cloned this repository navigate to your local repository using the cd command.
4. Type `code .` to open the repository in Visual Studio Code.
5. Hit ctrl + ` to open the terminal.
6. Type `mkdir Screenshots` to add a screenshots folder to the project. ![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/d8807732-a737-4b76-912c-fffe9c53aee7)


## Guided Activity Part 2 Intro To React - Components

1. We are going to build a basic UI to display a blog post out out components.
2. In the terminal type `npm create vite .` to create a vite project in the current directory.
3. Name the project guidedactivity2.
4. Choose React as the Framework.
5. Choose JavaScript as the variant.![Guided Activity Intro to React - Step 5](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/1d0fc89f-7136-4007-9a40-069df6305efd)

6. When the project has generated type `cd guidedactivity2`.
7. Type  `npm install`.
8. Type `npm run dev` to launch the demo project. ![Guided Activity Intro to React - Step 8](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/00eda21d-3660-4f34-9e01-aac6baad1076)

9. Click the local host link to launch the project. ![Guided Activity Intro to React - Step 9](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/12e7ba1c-bb61-400d-937c-6a5979f6e0cc)

10. Take a screenshot of the template project running and save in screenshots. ![Guided Activity Intro to React - Step 10](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/01882bb2-6ab9-459d-acfb-d158a9db59c9)

11. In the src folder replace ALL of the code in App.jsx with the following:
![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/ab8fb752-73af-4095-9613-9aa73ee86207)


12. Save App.jsx and notice the change in the browser. Add a screenshot of this output. ![Guided Activity Intro to React - Step 12](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/4d3b8049-0698-4ac3-9dc0-7a6b0f01627d)

13. Inside of src create a folder named components.
14. Create a component named BlogHeader.jsx ![Guided Activity Intro to React - Step 14](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/34bdbe07-4b94-495a-8531-f71a8ea2068c)

15. In BlogHeader.jsx add the following code:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/278ba5a8-e62a-491a-b6d4-5e687529f708)

14. Go back to App.jsx and import the new component and render the component after the h1:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/3d32c402-eafc-415a-8143-eca015f8950b)
 
15. Now that we see our component is working lets try to pass some data to it with props
16. Modify BlogHeader.jsx to take a props parameter and display information from the props in the component:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/30974e6f-9262-4770-856f-bf3eaf74049a)


17. Modify App.jsx to pass data to the BlogHeader component:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/0b265051-d4b6-4f4e-b564-d380a67eb99b)


18. Data is now being moved from a parent component to a child component. Take a Screenshot of the output and add to screenshots. ![Guided Activity Intro to React - Step 18](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/15d05bbd-fa25-4f97-84ec-adc907802618)

19. Repeat this process for a BlogBody component and a BlogFooter component.
20. Code for BlogBody:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/81427362-360a-42e9-bcce-569181b55ca6)


21. Code for BlogFooter:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/28aa58f3-7ce3-4e67-a55a-f077b304d239)


22. Import BlogBody and BlogFooter into App.jsx and render them while passing some data to the props
23. Updated code for App.jsx. Notice how components can also use self-closing tags.

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/e665ccbf-2466-4db2-af16-cd0fb8da59c7)


24. Take a screenshot of the rendered webpage and save in screenshots directory. ![Guided Activity Intro to React - Step 24](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/90283966/8732d365-c6c9-485b-9f46-1019258e9300)


## Guided Activity Part 3 Submission (You can also use GitHub desktop to submit)
25. Type `git add .` to stage all updated files.
26. Type `git commit -m "Guided Activity 2 Complete"`.
27. Type `git push`.



If you have any questions about this assignment please reach out to myself or our TA for this course. 



Feel free to message your instructor or the TA on Canvas if you have any questions.
