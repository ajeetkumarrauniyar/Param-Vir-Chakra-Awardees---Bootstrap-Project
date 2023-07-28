# Thought Note: Assignment 3 (Bootstrap) - README

## Project Title: Param Vir Chakra Awardees - Bootstrap Project

Date Prepared: 15th July 2023

### Objective:
The main goal of this Bootstrap project is to build a website with four pages dedicated to showcasing the "Param Vir Chakra AWARDEES!" These awardees have been honoured with India's highest military decoration for displaying exceptional bravery in the Indian armed forces. The project encompasses the following tasks:

1. Develop a navigation bar using Bootstrap's nav pills or nav tabs.
2. Incorporate a Profiles dropdown option in the navigation bar, which will contain links redirecting users to different awardees' profiles.
3. Create the design for the profile details using Bootstrap cards, allowing for customization such as colours, borders, text over images, and more.
4. Ensure that the entire webpage is fully responsive, adapting seamlessly to various screen sizes and devices.

### Resources Used:
- Visual Studio Code as the code editor
- Google Chrome as the web browser
- Bootstrap CSS CDN for styling and responsiveness
- Font Awesome CDN for icons
- Custom CSS in the "style.css" file
- Dummy data/images for demonstration purposes from [https://www.gallantryawards.gov.in/awards](https://www.gallantryawards.gov.in/awards)

### Learning Outcomes:
1. Implemented a responsive navigation bar using Bootstrap's nav pills and nav tabs, making it easy for users to navigate the website.
2. Created a Profiles dropdown menu using Bootstrap's dropdown component to organize links to different profiles efficiently.
3. Designed and customized Bootstrap cards for displaying profile details, including text over images and distinct colours for visual appeal.
4. Ensured the website is fully responsive by using Bootstrap's responsive classes and media queries.

## Home Page (index.html)
The Home Page will contain information about the project and display a list of available profiles in a navigation bar with a dropdown menu. The header will include a logo and a responsive toggle button for small screens.

### Navigation Bar:
```markdown
# Uses Bootstrap's "navbar" class to create a responsive navigation bar at the top to remain consistent across all pages.
# Includes the project logo in the navbar.
# Added a responsive toggle button for smaller screens.
# Created nav pills or nav tabs for the "Home," "Profiles of Awardees," and "Logout" (disabled) options.
```

### Profiles Dropdown:
```markdown
# Added a dropdown option to the navigation bar for "Profiles of Awardees."
# Populated the dropdown with links to the profile pages of different awardees.
```

### Hero Section:
```markdown
# Created a hero section with a background image and a heading introducing Param Vir Chakra Awardees.
# Added a subheading with a brief description of the award's significance.
# Includes a blockquote with a motivating quote related to soldiers and bravery.
```

### Profile Cards:
```markdown
# Displays a section with card components to showcase awardees' profiles.
# Each card includes the awardee's image, name, award, and a brief description.
# Provides a short description of the awardee's achievements and bravery.
# The cards also have buttons for "View Profile" and "Know More," allowing users to access additional information.
```

### Footer:
```markdown
# The footer displays copyright information.
```

## Profile Pages (profile1.html, profile2.html, profile3.html & profile4.html)
The Profile Page contains detailed information about a specific awardee in a card format. The page also displays a table with essential details about the awardee.

### Navigation Bar (Same as Home Page):
```markdown
# Use the same navigation bar design as the Home Page to ensure consistency.
```

### Profile Card:
```markdown
# Created a card component with a rounded image of the awardee.
# The card is designed with custom styling, ensuring it stands out from the rest of the content.
# Displays the awardee's name, the award they received, and a brief description of their bravery.
```

### Details Table:
```markdown
# Created a table to display essential details about the awardee, such as their award date, service, rank, etc.
# Used the <th> and <td> tags to organize the table rows and data.
# Added relevant information in each cell, such as award dates, service number, unit, etc.
# The table on the website is designed to be responsive, ensuring that it adjusts its size to fit the data it contains. This responsiveness prevents the table from overflowing the browser screen horizontally, which, in turn, eliminates the need for a horizontal scroll bar. This feature significantly enhances the user-friendliness of the website as users can easily view the table's content without having to scroll sideways, providing a smoother and more pleasant browsing experience.
```

### Footer:
```markdown
# The copyright information on the footer remains in accordance with that of the homepage.
```

### Responsive Design:
```markdown
# Implemented Bootstrap's responsive classes and media queries to ensure the website looks good on various devices.
# Tested the website's responsiveness on different screen sizes to confirm proper layout adjustments.
```

### References:
- Utilizes the Bootstrap documentation (https://getbootstrap.com/docs/5.3/) for guidance on Bootstrap components and classes.
- Uses Font Awesome documentation (https://fontawesome.com/) for icons and their respective classes.
- Used Codeplay.com for styling the Toggler button.

### Declaration:
I hereby declare that this Bootstrap project for showcasing Param Vir Chakra awardees' profiles is my original work, and all resources used are appropriately credited. The project adheres to the guidelines and objectives specified in the Thought Note.
