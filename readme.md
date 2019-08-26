### **Name**

MilestonePlanner

### **Description**

MilestonePlanner is a java-based web application that helps a user to create milestones with start and completion date. On this application, a user can:

- add a milestone,
- remove a milestone,
- edit a milestone, and can also
- share a milestone with another user of his choice

### **Requirements**

To run this application successfully, you need the following tools:

- Tomcat 9.0.17
- IntelliJ IDE
- H2 Database
- Java SDK 11.0.3 (64-bit)

### **Server Configuration**

In IntelliJ,

- Click on add configuration which is next to the build icon
- Click the add (+) button 
- Choose tomcat server (local)
- Under the Server tab, choose application server which is Tomcat 9.0.17
- Click the Deployment tab (Next to server tab)
- Click the add (+) button 
- Click artifact 
- Choose Milestone-planner:war exploded
- Remove the text in the Application context 
- Click apply then ok

### **Usage**

1. Open your IntelliJ IDE
2. Click Open and then locate Milestone Planner.
3. Run your Tomcat 9.0.17 . This takes time. So, wait until it completes. Once it is done, the app will automatically be launched in the browser.
4. The user can then start to play around with the application.
5. A new user is required to sign up first. After signing up successfully, the web loads a login page. Once the user logins successfully, he is taken to his dashboard with empty milestones. This user can then choose to add a milestone.
6. This user can also choose to share his/her milestones. If so,the user clicks on the share button, which then displays a sharable link
7. To use the shareable link, copy it, log out, and sign in as another user. Then paste the link you copied in a specified slot called Insert link, and then click import. This takes you to a list of shared milestones.
8. Once the user has finished using the application, he can choose to terminate the session by clicking the logout button.

### **Support**

In case you find any bug, or issue in our codes, please create a pull request. We will be happy to chat more and apply the feedback.

### **Roadmap**

This is the first phase of our application. In the near future, we are planning to include more features especially security related. We take care of our users information; thus, their data privacy and confidentiality are our number one priority.  Now, a user can login using his email and any password either be strong or not. However, in the second phase, we want to make it a requirement for a user to create strong password. Next, we need to include also a two-factor authentication option using SMS or call.

### **Authors and acknowledgment**

This application was built by a team of three ALC Students: Yonas Chapi, Faouzi Jedidi, and Heritier Muhire.

We would like to appreciate the consistency support of our module leader, Katrin. She helps us with additional notes, guidance, and resources to complete this coursework. We also appreciate, Mr Tabot, our facilitator for consistency followup and guidance in the time we were working on this project.