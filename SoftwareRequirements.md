## Vision

1. What is the vision of this product?
  - To create a canvas competitor that cleanly displays data for each course, removes redundant data on all of its pages, and loads faster than canvas
2. What pain point does this project solve?
  - Our project will offer users an efficient learning tool which improves on the weaknesses of canvas, it will be more efficent, reduce UI clutter and offer an easier to digest experience for students.
3. Why should we care about your product?
  - With the expanding presence of online learning, our application hopes to create a user friendly experience that will help facilitate the educational process. Allowing teachers to focus more on teaching rather than the application itself  



## Scope

1. Describe the individual features that your product will do.
      - The ability to create a new acount and have that acount can be a teacher or a user
      - Teachers can add students to courses
      - Assignments will be viewable once the student logs in
      - Assignments will be gradeable with a point based system

2. What will your product not do
      - Our application will not have an admin user
      - Our application will not allow teachers to create assignments
      - Our application will not have any instant messaging capabilities

## MVP

1. What will your MVP functionality be?
    - Our MVP will The ability to create a new acount and have that acount can be a teacher or a user, teachers can add students to courses, assignments will be viewable once the student logs in, assignments will be gradeable with a point based system
2. What are your stretch goals?
    -Allow teachers to create assignments
    
## Functional Requirements
   - The ability to create a new acount and have that acount can be a teacher or a user
   - Teachers can add students to courses
   - Assignments will be viewable once the student logs in
   - Assignments will be gradeable with a point based system

## Data Flow
  
  - The user (student or teacher) first logs in to the service. After logging in they are directed to their courses view. Once a course is clicked on, assignments are displayed and the user has multiple options: view grades, view details about an assignment, or view all users associated with the course. Student users will be able to make submissions on assignment detail pages and teachers will be able to assign grades to submissions. Additionally teachers can edit assignments and view all student grades.

## NonFunctional Requirements 

  - Security
This app will be using Spring Security and Cognito to provide authentication and access control to restricted pages. This will ensure that identity-based pages like gradebook views are restricted to teachers and administrators.

  - Usability
The client app will be simple, modular, and easy to use. There will be different views for students and teachers. Students will be able to view due dates, assignment info, and their own grades. Teachers will be able to view all of this plus additional data like the gradebook.

  - Testability
We will have some smoke testing of routes using a unit testing library of some kind. We also plan to integrate Swagger for route/API design.
      
      
