Overview

Assign 1: Project setup and display Hello World
 -Create a project with valid name with proper naming convention
- Build and run the project trying both the commands as npm start and ng serve, ng serve -o
- Add one new component and try to make it root component by replacing the default selector in index.html
- Divide the parent component in 3 parts as Top Bar, Side Bar, Main section
- Create 3 more components and load them in above mentioned parts
- Display Welcome message in top bar section as a static message
- The component which you will be rendenring in main part should have following things:
 1. Heading - Display Hello [Your_Name] using interpolation
 2. Take one input box to take name and bind that name with ngModel with variable Your_Name
 3. Take Two Input textbox to take two numbers
 4. Button to take operations like Addition, Substraction, Division, multiplication which will have click event
 5. Clicking on them will display alert with the value

You can apply the CSS of your choice and try to use SCSS file


Assig. 2 Directive and Pipes

Please use proper layout, indentation and appropriate component and method names.

- Replace the default HTML with below:

- Display Hello [Your Name] using angular interpolation in h1 tag

- Create an input field and a button, bind id using property binding. On click of the button display contents of the field in a div.

- Display text 'Success' in green and italic and 'Error' in red and bold by toggling a button 'Toggle Error state'

- Display list of months using ngFor directive

- Declare a boolean value isAvailable, and based on it hide/show a div containing Available, Not Available text

- Create an input field, which allows user to enter value in meters and display the value in browser in centimeter using custom pipe

Assign. 3: Component Interaction and lifecycle hooks
Implement Component interaction with @Input and @Output decorator
Implement angular component life cycle hooks to display messages
Implement emitter


Assig. 4: Routing
Divide main component in 4 sections
Topbar
Sidebar
Main area
Footer
Display Welcome message on Topbar
Display Copyright information with current year in footer. Try to make use of date pipe to show year
Display links for navigation in sidebar


Assign. 5: CRUD Operation with JSON Server
Create a JSON Server and Implement CRUD operation using JSON Server APIs.

Make use of ngx-toastr package to display messages

Use bootstrap package for the UI

Make use of the title service to set page title



Assignment Final test
Develop an application in angular that contains following features:

- Login Page

- Welcome Page with some good layout / message / image of your choice

- Give navigation from Welcome page as - Bus Seat Booking page & Logout

- Implement CRUD Operations for Bus Seat Booking page

- Booking form with below fields:

- Bus No. - Dropdown list (implement with your choice)

- Seat No. - Dropdown list (implement with your choice)

- Boking Date - implement with Date picker

- Add Comuter Personal Details with valid fields which will cover all input controls

- Submit button

- If seat for that bus is already booked then display error toastr

Note:

- Use proper folder structure
- Follow proper naming conventions
- Code should be indented properly
- Form should have proper validations
- CRUD operations should be perform using json server 
- Display appropriate toastr messages using toaster
- Implement proper Routing and AuthGuard
- Try to make it more user friendly
- Add your additional thoughts for assignment


