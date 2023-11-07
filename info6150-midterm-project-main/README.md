Midterm Project
Due Dates: There will be multiple submissions and due dates vary. See Due Dates &
Submissions Milestones section in this document for details.
Grading Note: For this mid-term project, we will use the 100-point grading system. You will be
graded on a 100-point scale, and your grade will be converted proportionally to a 20-point
scale and recorded in the gradebook. For example, a 70/100 grade will be 20 * (70 / 100) = 14
points in your gradebook.
Requirement
In the past homework assignments, we've built a two-page web app to introduce your hometown
or favorite city and built a form to collect the potential clients' inquiries.
In this midterm project, you will work on your own to build a web application for your travel
agency. You will build a front-end only multi-page web application to introduce your company,
and advertise your travel products.
Content: Your website will have a minimum of 6 pages.
● At least 1 home page named index.html. This page is the entry page of your web
application. You will need to tell your potential clients why they should choose you, what
are the top destinations you provide, and if there are any deals or discounts. For any
deals or top destinations, make sure to provide a link to another page of your website so
that they can click and get more details.
● Your company has expanded to provide at least 3 destinations. You will build one page
for each destination. Each page will have an introduction to the destination and one or
more several-day itineraries. Make the page look appealing by adding some images and
organize the pictures nicely.
● There will be a page for the reservation form just like you did in HW 5. When the user
clicks Submit, the page will need to show all the data they entered right below the
Submit button. Hint: You will need to use JavaScript to get information from DOM and
add new elements to the DOM.
● Make sure all the pages include some common components such as top / side nav bar,
footer, etc.
● If you copy the content from other websites, make sure to include citations.
Fully utilize Tailwinds CSS components to design your web app.
Tourism Websites References
In case you need some inspirations on how to properly design a good layout for travel related
content, here are some good travel websites for your reference:
● EF Ultimate Break
● Costco Travel
● Insight Vacations
Due Dates & Submissions Milestones
Milestone 1: Proposal Slides (Due 10/17 Tue 6pm on Canvas)
You will make a Google slide or PowerPoint to show what you will be building, and present it in
10/17 class. In the slides, you will show a sitemap of the web app, the timeline of your project, a
rough wireframes for each page, and the main features per page.
Submission: Upload the slide to Canvas prior to 10/17 Tue lecture.
Rubrics: 20' total for Milestone 1.
● (3') Sitemap
● (3') Timeline
● (5') Wireframes
● (5') Main features
● (4') Quality of slides and presentation
Milestone 2: Kanban Board (Due 10/24 Tue 6pm on Canvas)
Break down the features to smaller user stories. Hint: Each user story should only focus on one
thing. Set up the Kanban board on Trello. Fill each user story with a Kanban card, and attach
the wireframe to the card wherever appropriate. Present your trello board in 10/24 class.
Submission: Share the Trello board with yuzechen_neu, and upload the link to Canvas
by due date.
Rubrics: 30' total for Milestone 2.
● (5') Kanban board set up correctly on Trello.
● (10') Each feature is properly broken down to multiple user stories.
● (10') Created a Kanban card for each user story, with wireframes when appropriate.
● (5') Quality of the presentation.
Milestone 3: Status Check-in (Due 10/31 Tue 6pm on Canvas)
Once your trello board is set up, you can start immediately using the Simplified Git Workflow we
talked about in class when you write code. Detailed steps as follow:
● Step 1: Create a new private repository on GitHub called "info6150-midterm-project"
under your GitHub account.
● Step 2: Share your repository with my GitHub account: yuzechen-neu
● Step 3: On your workstation, create a new directory (folder) named
"info6150-midterm-project".
● Step 4: Add your first file README.md under the "info6150-midterm-project" directory.
● Step 5: Copy the files from your previous homework as needed.
● Step 6: Add, commit, and push what you have so far to the main (or master) branch.
○ git add .
○ git commit -m "add README and files from previous
homework"
○ git push -u origin main
● Step 7: Create a new branch called "feature/<very-short-description-of-user-story>",
such as "feature/add-index-page" or "feature/add-navbar-to-index-page"
○ On your main branch, create a new branch and check out (switch) to the new
branch
■ git checkout -b feature/XXX
○ Add files and codes
○ As you make small progress, make sure to Add, Commit, Push your codes.
Remember your initial push to a new branch will need to be: git push -u
origin feature/<very_short_description_of_user_story>
■ For subsequent pushes: git push
○ Once you are done with the user story, Create a Pull Request (PR) from your
feature branch to the main branch. Put the PR title as your feature description.
Comments are optional.
○ Review your own changes in the PR, and merge the PR to the main branch
when everything looks good.
○ Once PR is merged, the Git history tree on remote (Github) will be updated.
● Step 8: Now your local Git repo history tree is behind the remote history tree. You will
need to update your local tree by pulling from the remote repo.
○ Switch from your feature branch to the main branch. git checkout main
○ Pull the changes from remote (Github). git pull
● Go back to Step 7 to work on the next user story until every user story is done.
Submission: Share the Git repo with yuzechen-neu, and upload the Github repo URL to
Canvas by due date. The URL should look like this
https://github.com/yuzechen-neu/git-example-1.
Rubrics: 5' for Milestone 3. You will get a full score if you have made sufficient progress to make
sure your project is on track. The minimum standard is: 2 user stories done. Done means PR
closed with feature branch merged into main. Able to demo the completed user stories on the
main branch.
Milestone 4: Complete Project Submission (Due 11/7 Tue 6pm on Canvas)
● Make sure all of your PRs are merged into the main branch.
● Make sure the HTML, CSS, and JavaScript are valid and the Google Chrome browser
can open and render it correctly. If your code does NOT render in the Chrome
browser, your homework will NOT be graded, and you will have to re-submit the
correct one with the late penalty.
● In the main branch, update README.md to include what you have done for your project.
Add, commit, and push the change. Here's a good resource on what needs to be in a
README.md, and how to properly format it.
● Make a Google Slide or Powerpoint presentation on what you have done, the
overall timeline, features you've done, any difficulties you encountered & how you
overcame them, lessons learned, etc. Present it in the 11/7 lecture.
● Prepare for a live demo of your web app in the 11/7 lecture.
Submission: Once everything is done, submit your Github link (again), and the
presentation slides to Canvas. The submission time will be determined by the time you
pushed your last commit / merged a feature branch to the main branch, or the time you
submitted to Canvas, whichever is later.
Rubrics: 45' for Milestone 4.
● Content
○ (5') Include at least 6 pages. Home page includes sufficient information. Have
links to other pages on your web app. At least 3 pages for destinations.
○ (5') Your web app looks appealing, modern, and easy to navigate. (I understand
different people have different tastes, but for this one, I'll be the sole judge and
the grade is final.)
○ (5') Reservation form includes necessary fields. Once the user clicks Submit, the
page presents all the data entered right below the Submit button. The
presentation of submitted data is nicely formatted with Tailwinds CSS.
● Styles
○ (5') Utilize a variety of Tailwinds CSS components to build the website.
○ (5') There are unified layouts such as top nav bar and/or footer in every single
page of your web app.
● Git Workflow & User stories
○ (5') Every user story has a branch, and a PR.
○ (5') As you make small progress, you Add, Commit, Push your codes.
● Presentation & Demo
○ (5') Slides are complete
○ (5') Live Demo in class