# Women's wellness warriors

### [Live Site](https://alcl2000.github.io/womenswellnesswarriors/)

Our app, 'Dot.' created for the CodeInstitute Women's Wellness hybrid hackathon

## Project Goals

- Dot. is an app designed to make period tracking easy and display information in an accessible format
- Enhance users' understanding of their menstrual health by providing educational resources and insights into common symptoms, cycle patterns, and wellness practices.
- Promote inclusivity and accessibility by designing the app to be user-friendly for individuals of all ages, genders, and backgrounds, with consideration for diverse cultural perspectives and experiences.
- Provide accurate predictions and insights into users' menstrual cycles, enabling them to plan and prepare for their periods and associated symptoms.

### User stories 
 - As a user, I want to be able to easily log my menstrual cycle start and end dates, so I can accurately track my period over time.
  - Need effectively met through the "Dot" quiz and calender
- As a user, I want the app to provide insights and predictions about my cycle based on the data I input, so I can plan activities and events accordingly.
 - Need met with the addition of advice and symptom reminders on the side of the dot page, for users to gain a greater understanding of their cycle
- As a user, I want access to educational resources about menstrual health and wellness, so I can learn more about my body and how to care for it during my cycle.
 - Need met with the addition of advice columns on the side
- As a user, I want the app to offer customizable settings for cycle length and fertility tracking, so it can adapt to my individual needs and preferences.
 - User is able to change the length of their period and cycle if it falls outside of median parameters

## Design

- Colour Palette 
![Colour Palette](docs/dot_color_palette.png)
![Text Choices, the font Libre Calson font](docs/font-choices-1.png)
![Font Choices, the font Monsterrat](docs/font-choices-2.png)
###  Wireframes
![Home page wireframe](docs/dothome.png)
![About us wireframe](docs/dotaboutus.png)
![Calender Wireframe](docs/dotcalender.png)
![Form wireframe](docs/dotquiz.png)

### Features


### Future Features

Due to time constraints, not all of our planned features could make into the final app. Had we had more time, these features could have been added to improve the app

#### Circle tracker 
- A circular tracker would have been implemented alongside the existing calender to make viewing the various phases of the menstrual cycle easier and more intuitive

### Bugs 

- Background colour
    - The background colour was too vivid and made text difficult to read
    - The chosen image selected for our background did not stretch efficiently and did not tesselate, a different image was chosen
- Git troubles
    - The repository was not initialised with a .gitignore file which meant that when necessary add ins were installed, all of the node packages were installed with them
-Circular tracker not tracking date 
    - The circular trackers we chose had no function to implement date tracking and as such could not effectively track a user's place in their cycle
- Links
    - Links in the navbar were configured incorrectly, and were rewrtitten to ensure no 404 errors
- Footer
    - The footer floats on several pages due to our use of flex boxes 

### Deployment

#### Deployment to github pages
To launch a website on GitHub Pages, follow these steps:

- Create a Repository:
    -   Go to GitHub and sign in to your account.
    - Click on the "+" sign in the top-right corner and select "New repository."
    - Name your repository using the following convention: <username>.github.io. Replace <username> with your GitHub username.
    - Choose whether the repository will be public or private. For GitHub Pages, it needs to be public.
- Add Your Website Files:
    - Upload or push your website files to the repository. This typically includes HTML, CSS, JavaScript, images, etc.
    - If you're using a static site generator like Jekyll, make sure to commit the generated files to your repository.
- Configure GitHub Pages:
    - Go to your repository on GitHub.
    - Click on the "Settings" tab.
    - Scroll down to the "GitHub Pages" section.
    - Under "Source," select the branch that contains your website files

#### Forking/Cloning a repository
- Navigate to the Repository:
    - Go to the GitHub repository you want to fork by entering its URL in your browser or searching for it on GitHub.
- Locate the Fork Button:
    - On the top-right corner of the repository page, you'll find a "Fork" button. Click on it.
- Choose the Destination:
    - A dialog will appear asking where you want to fork the repository. Select your own GitHub account or an organization where you have permission to fork repositories.
- Fork the Repository:
    - Click on the "Fork" button. GitHub will now create a copy of the repository in your account or the chosen organization.
- Wait for the Forking Process:
    - Depending on the size of the repository and the current GitHub load, the forking process may take a few moments. Once completed, you'll be redirected to your forked repository.
- Start Working:
    - You now have your own copy (fork) of the repository. You can clone it to your local machine, make changes, commit those changes, and push them back to your forked repository. You can also open pull requests to contribute changes back to the original repository.



### Tools Used

[Sweet Alert](https://sweetalert2.github.io/)  
[Bootstrap](https://getbootstrap.com/)  
[Google Fonts](https://fonts.google.com/)  
[FullCalendar](https://fullcalendar.io/)
[Circular Dial](https://codepen.io/robertkoons/pen/NByBMg)
[ChatGPT](https://chat.openai.com/) (for creation of the logo and various issue consulting)
[Github Pages]()
