# Proj2
Title: Proj2
Team Members: Anh Le, Moses Surumen, Roberto Romo
Demo Link: https://youtu.be/V0qkcIPQ4bY

Idea: An E-learning application where students can enroll in courses. A user/instructor can post the course content on the website, and provide links to videos and slides. The instructor can also upload files (images) in case demonstration is needed. Students can review each course by commenting on what they like best, or what they would like to see improved. 
An instructor who created the course can edit the course, or delete it from the website.

Models and Description:
User

•	Users have name, email, password, and can post many comments
•	Users can create courses, upload content (videos, assignments)
•	Users can enroll in courses that is not their own
•	Users grade assignments for their own course



Courses

•	Courses have a title, description, syllabus, assignments, videos
•	Courses are done on a basis of subscription; users can subscribe to be enrolled in the course


Assignments

•	Assignments have a name, due date, and description.
•	Assignments include respective video (lectures) and assignments/notes
•	Assignments are completed by enrolled users and posted by the user that is teaching the course
•	Assignments are graded by the user instructor


Comments

•	Comments have text and belong to a user
•	Users can comment on courses (post a review/feedback)
•	Comments are part of courses.



Features:

•	Users can log in, sign out, delete their account
•	Users can post video lectures and post corresponding assignments, lectures/notes
•	Users enroll in courses, view lectures and complete assignments
•	Users can grade assignments that they post for their course
•	Users can comment on the course, give feedback
•	A user can be both the instructor (create course, post webcasts and corresponding assignments) and the student (enroll in other courses)



Gems Used
	- Devise for user authentication
	- Ckeditor for course syllabus
	- Simple form for forms 
	- Paperclip to upload images to site
	- Pundit
  
  
  

Division of Labor:
•	Anh: Made Controllers, Grades, 
•	Moses: Front End, Styling, gems, Login in
•	Roberto: Made Assignments, Courses
