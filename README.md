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
4. Type `code .` to open the repository in Visual Studio Code
5. Hit ctrl + ` to open the terminal
6. Type mkdir Screenshots to add a screenshots folder to the project

## Guided Activity Part 2 Intro To React - Components

1. We are going to build a basic UI to display a blog post out out components.
2. In the terminal type `npm create vite .` to create a vite project in the current directory.
3. Name the project guidedactivity2.
4. Choose React as the Framework.
5. Choose JavaScript as the variant.
6. When the project has generated type `npm install`
7. Type `npm run dev` to launch the demo project
8. Take a screenshot of the template project running and save in screenshots
9. In the src folder replace ALL of the code in App.jsx with the following:
![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/ab8fb752-73af-4095-9613-9aa73ee86207)


10. Save App.jsx and notice the change in the browser. Add a screenshot of this output
11. Inside of src create a folder named components
12. Create a component named BlogHeader.jsx
13. In BlogHeader.jsx add the following code:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/278ba5a8-e62a-491a-b6d4-5e687529f708)

14. Go back to App.jsx and import the new component and render the component after the h1:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/3d32c402-eafc-415a-8143-eca015f8950b)
 
15. Now that we see our component is working lets try to pass some data to it with props
16. Modify BlogHeader.jsx to take a props parameter and display information from the props in the component:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/30974e6f-9262-4770-856f-bf3eaf74049a)


17. Modify App.jsx to pass data to the BlogHeader component:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/0b265051-d4b6-4f4e-b564-d380a67eb99b)


18. Data is now being moved from a parent component to a child component. Take a Screenshot of the output and add to screenshots
19. Repeat this process for a BlogBody component and a BlogFooter component.
20. Code for BlogBody:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/81427362-360a-42e9-bcce-569181b55ca6)


21. Code for BlogFooter:

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/28aa58f3-7ce3-4e67-a55a-f077b304d239)


22. Import BlogBody and BlogFooter into App.jsx and render them while passing some data to the props
23. Updated code for App.jsx. Notice how components can also use self-closing tags.

![image](https://github.com/EmeryCSI/CSI248F23_GuidedActivity2/assets/102991550/e665ccbf-2466-4db2-af16-cd0fb8da59c7)


24. Take a screenshot of the rendered webpage and save in screenshots directory.

## Guided Activity Part 3 Submission (You can also use GitHub desktop to submit)
25. Type `git add .` to stage all updated files.
26. Type `git commit -m "Guided Activity 2 Complete"`.
27. Type `git push`.



If you have any questions about this assignment please reach out to myself or our TA for this course. 



Feel free to message your instructor or the TA on Canvas if you have any questions.
