# AWS-based-Dynamic-Web-Application-in-Amazon-S3-and-EC2
Dynamic web app featuring personal portfolio, department page &amp; interactive survey form. HTML/CSS/JS/Ajax/Bootstrap. Deployed on Amazon S3 &amp; EC2

## Project Overview
This project encompasses the development and deployment of a web application focusing on showcasing personal information, providing details about the Computer Science department, and facilitating a survey form for prospective students. It includes two main parts:

1. **Personal Web Page**:
   - A homepage containing a picture and a brief description of the individual.
   - Utilization of a W3.CSS template to enhance the design.
   - Hosted on Amazon S3.

2. **CS Department Page and Survey Form**:
   - A website providing information about the Computer Science department, including a survey form for feedback.
   - Deployed on an EC2 instance in AWS.
   - Integration of various features like Bootstrap navigation, cookies, greetings, data computation, form validation, Ajax, and JSON.

## Files Included
- `index.html`: Homepage HTML file.
- `ComputerScienceDepartment.html`: CS Department Information page HTML file.
- `Surveyform.html`: CS Department Survey Form HTML file.
- `IMG_0731.jpg`: Image used in the homepage.
- Additional image files used in the project.
- CSS files for styling.
- JavaScript files for dynamic functionality.
- Documentation files and setup instructions.

## Deployment Steps
### Part 1: Personal Web Page (Hosted on Amazon S3)
1. Followed AWS S3 setup documentation.
2. Created an S3 bucket named `sailohith.com`.
3. Uploaded the required files to the S3 bucket.
4. Enabled static website hosting on the S3 bucket.
5. Configured the index document to `index.html`.
6. Accessed the homepage using the S3 bucket URL.

### Part 2: CS Department Page and Survey Form (Deployed on EC2 Instance)
1. Created an EC2 instance on AWS.
2. Installed a web server (Apache) on the EC2 instance.
3. Created a keypair for SSH access.
4. Used PUTTY to access the EC2 instance via SSH.
5. Copied the HTML files and images to the EC2 instance.
6. Configured the web server to serve the HTML files.
7. Accessed the web pages using the EC2 instance's public IP.

## Additional Features Implemented
1. **Navigation Bar Enhancement**:
   - Redesigned the webpage with a Bootstrap navigation bar for better visual appeal and navigation.
   - Implemented tab functionality for easy switching between sections.

2. **Cookie and Greetings Implementation**:
   - Utilized cookies to store user information, including their name.
   - Displayed personalized greeting messages based on the time of day.
   - Provided an option to update the stored name.

3. **Survey Form Extension and Data Computation**:
   - Added additional input fields and dynamic computation for data analysis.
   - Validated user input and provided error handling.

4. **Form Validation Event Handling**:
   - Created event handlers for validating form inputs.
   - Implemented criteria validation and error messaging.
   - Included field clearance and reset button for better user experience.

5. **Ajax and JSON Integration**:
   - Implemented Ajax functionality to populate fields dynamically based on user input.
   - Retrieved JSON data for validation and error handling.

## URLs
- S3 Bucket: https://s3.amazonaws.com/sailohith.com/dynamic_web_Application/index.html
- 
## Additional Notes
- Incorporated George Mason University color scheme for consistency.
- Ensured all HTML5 pages meet specified criteria.
- Provided hyperlinks for easy navigation between pages.

## Developer Information
- **Name**: Sai Lohith Panthangi
