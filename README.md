# 🧪 AmbuLAB

![alt text](http://github.com/amuchina/AmbuLAB/blob/main/ambulab.png?raw=true)

## AmbuLAB Clinic Management System

### Overview
AmbuLAB is a comprehensive clinic management system designed for private healthcare facilities. This project aims to streamline and enhance the administrative and operational processes within the clinical environment. Our software is built with modern technologies promising stability and security while providing elegant and user-friendly interfaces.

AmbuLAB's software features a graphical interface where users need to register, creating their own accounts to access available functionalities. Users can easily register on AmbuLAB through the dedicated registration page, requiring input of their name, surname, date of birth, tax code, email, the choice of a username, and a password. Once registered, users access their dashboard by logging in on the appropriate page.

**Functionalities Analysis**

Within the dashboard, functionalities vary based on the user's account type. If the accessing user is an admin, they can:
- View the notification center
- Modify their settings and preferences (limited to graphical settings of the dashboard)
- Edit their profile (modify personal data)
- Access the employees table (e.g., to manually create the corporate account of a new employee) and the patients table (end customers) to modify, delete, or add accounts
- Manually modify, delete, or add new types of exams
- View daily and monthly statistics (including through charts) related to the polyclinic's activity
- View information about AmbuLAB

Otherwise, if the user is an ordinary client, they can:
- View the notification center
- Modify their settings and preferences (limited to graphical settings of the dashboard)
- Edit or delete their profile (modify personal data)
- Book medical visits or various types of exams, accessing a dedicated page where they provide the exam name, desired date, location, and the preferred doctor
- Cancel medical visits within 24 hours from the exam start date
- View past exams
- View information about AmbuLAB

**Technologies Used**

The technologies chosen by the AmbuLAB team were selected based on their reliability, security, stability, and ease of use. AmbuLAB is designed and developed as a full-stack web application, structured into three different development sections: front-end, back-end, and database.

The front-end encompasses everything related to the graphical interface, design, and user experience. To ensure user comfort, we chose to use Vue.js for the front-end, a JavaScript framework allowing the creation of reusable components written in HTML (with some exceptions) but rendered by the framework as JS code. This approach facilitates the creation of web pages, as such frameworks (mostly based on JS) allow the implementation of libraries and native JS/TS code to make rendering logical and conditional. Furthermore, the styling of AmbuLAB's front-end pages is achieved with Bootstrap and Nuxt, simple and flexible CSS frameworks to avoid writing hundreds of lines of CSS using ready-made and responsive classes.

Subsequently, the database structure is built using MySQL, a tool chosen for its stability and efficiency.

For the back-end development of AmbuLAB (i.e., everything related to the logic behind the interface running on the server), we decided to use Laravel, a PHP framework known for its security and stability, which, thanks to an MVC structure (Model, View, Controller), controls all the operations required for the server to execute so that users can perform various operations such as login, signup, API requests, etc. Our application also utilizes Inertia.js alongside Laravel, a middleware facilitating conditional render requests and data authentication/fetch without the need to build an API from scratch, saving a lot of time and effort.

The project's workflow is managed using the most commonly used version control technology, Git, which, configured in the project's working directory, allows for safer and more controllable local work for each implementation (fixes, features, and more). Moreover, it is connected to a remote repository on GitHub, enabling all project members to synchronize without manually adding others' changes or waiting to collaborate in person, making parallel productivity and division among the three sections of the application, in addition to making the project open-source.

Finally, regarding the IDEs used, we decided to use the JetBrains suite for web development, namely WebStorm for the front-end, DataGrip as a DBMS, and PhpStorm for the back-end. Additionally, we used Figma design for creating mockups for AmbuLAB's UI and Lucidchart for creating the ER model.

**Example Mockup**

An example mockup, in this case, of the home page (Note: the final product may differ in colors and graphical dependencies from those displayed).

**Team Roles**

Our project group consists of:

- Matteo Gilardi: Responsible for designing and testing the front-end component of the application (Vue.js, Nuxt, Bootstrap, WebStorm)
- Giovanni Desio: Responsible for designing and testing the back-end component of the application, CRUD requests (create, read, update, delete), project workflow management (Git configuration, GitHub repository, working directory management), and UI/UX graphical design (mockups) of the interface (Laravel, Inertia.js, Composer, Git, GitHub, Figma design, PhpStorm)
- Davide Pasini: Responsible for data management; creating the ER model, relational model, and database design (LucidChart, MySQL, DataGrip)
- Giuseppe De Pietro: Kind provider of JetBrains educational IDE licenses, whose availability we appreciate.

A project by Giovanni Desio, Davide Pasini, Matteo Gilardi.

### Getting Started

### Prerequisites for running the project
- [Node.js](https://nodejs.org/) installed

//continue
