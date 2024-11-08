# Tic Tac Toe Game (Ticcity Taccity Toe)

## Contents
- Summary
- Issue
- Decision
- Status
- Details
- Assumptions
- Constraints
- Positions
- Argument
- Implications
- Notes

---

### Summary
Issue  
We want to determine the architecture decisions for our Tic Tac Toe game, taking into consideration the project timeline and the team's skillset.  

Decision  
Decided to use React Native for the development framework, a stack navigation strategy, Fingerprint scanning for easy log in, and encrypted local storage for data persistence such as SQL lite. Target devices and CSS framework were already pre-determined to be Android and Bootstrap, respectively.  

Status  
Decided. The group is open to revisiting the decisions if added information arrives.  

### Details

#### Assumptions
- The group has knowledge of React Native and JavaScript.
- The group prioritizes UI/UX functionalities.

#### Constraints
- Skills of the group members limit the availability of the frameworks to be chosen.
- Timeline limitations must be met due to existing deadlines.

#### Positions
**Development Framework**  
- React Native allows for flexibility and performance of the app, aligning to the group’s skill set.

**Navigation strategy**  
- React Navigation using stack navigation for transitioning between screens, providing effective navigational flow.

**Hardware**  
- Fingerprint scanning enhances the login function of accessing the app, providing better usability for the user.

**Database Storage**  
- SQL lite as a lightweight database to securely store our users’ credentials.

### Argument
- React Native allows for rapid development and deployment to adhere to our timelines. Also, the group already has previous experience with the framework ensuring smooth implementation.
- Stack Navigation allows for simplicity within the system. Ensuring easy onboarding and usability throughout the application.
- Fingerprint Scanning allows users with said feature on their mobile device quickly and easily login to the app without having to enter their credentials every time they would like to access the mobile application.
- SQL lite guarantees user security due to the nature of their credentials being used to log into the app, as well negating such a large database such as MySQL when we only need a small local one for user data.

### Implications
These choices are suspected to lead to faster deployment and enhanced user experience while using our application. While also allowing the group to provide future enhancements and scalability.

### Notes
Group meetings will be held to ensure members stay informed of progress and have knowledge of the expectations set by the group.
