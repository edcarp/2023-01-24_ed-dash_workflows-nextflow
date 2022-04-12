# Template repo for nextflow workshops

## Creating a new workshop webpage

To create a workshop webpage from this template click on the green "Use this template" button towards the top of this page. Make sure the owner is edcarp and the name of the repo follows the standard naming convention: YYYY-MM-DD_ed-dash_workflows-nextflow. The date should be the first day of the workshop. The repo should be public.

Once the date, times, instructors and helpers have been decided these need to be added to index.md file (in the meta data at the top of the file). 
In addition, the date and time of each day of the workshop needs to be added to the schedule found in at _includes/custom-schedule.md.

When the webpage has been created (not necessarily complete) the http link should be added to the workshop timeline table:   https://github.com/orgs/edcarp/projects/7. The webpage link to the newly created workshop can be found above in Settings -> Pages. This link should also be copied into the "About" section of the workshop repo above.

## Adding workshop date to the ed-dash webpage

A post on the Ed-DaSH webpage should be made once a workshop webpage has been created. To add a new post go to the _posts folder of the Ed-DaSH repo: https://github.com/edcarp/Ed-DaSH/tree/gh-pages/_posts. Click add file -> Create new file and name the file using following the naming convention: YYYY-MM-DD-workflows-nextflow. WARNING: do not put any underscores in the name. The date placed in the file name should *not* be the date of the workshop. It should be the date you want the post to be visible on the website (normally today's date). Also be aware that jekyll orders the posts according to this date so if you create multiple posts at the same time you may want to give them the dates of consecutive days (today, yesterday and the day before that...) to ensure they appear in the right order on the webpage.

Next, copy the entries from a previous post into the new one (see example below, you will need to enter edit mode by clicking on the pencil in the top right of this readme file to copy the table) to ensure you have all the required information. Then fill in the entries according to this new workshop (the dates here should be the actual dates of the workshop).

Finally, open the webpage and check the new post appears! Bear in mind it can take 5-10 minutes for the website to update once something has been changed.

## Example post

---
title: "Introduction to Conda" 

when: "1st March 2022"

start_date: 2022-03-01

end_date: 2022-03-01

website: https://edcarp.github.io/2022-03-01_ed-dash_intro-to-conda/

registration: https://www.epay.ed.ac.uk/conferences-and-events/college-of-medicine-and-veterinary-medicine/school-of-molecular-genetic-and-population-health-sciences/igmm/introduction-to-conda

categories: jekyll update

type: workshop_announcement
---
