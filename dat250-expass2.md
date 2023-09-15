# Expass 2
## Technical problems that you encountered during installation and use of Java Persistence Architecture (JPA) and how you resolved
- I did not encounter any issues during the installation of JPA, however, I encountered some problems during the implementation of this task. In the beginnning I did not realiase that the methods getOwnedCards() and getOwners() needed to return HasSets(), but I quickly solved this.
- I also misunderstood the use of @getter and @setter, and instead implemented all getters and setters myself, when I realized my mistake i corrected this.

## A link to your code for experiment 2 above. Make sure the included test case passes!
- https://github.com/thomasthunes/dat250-jpa-tutorial

## An explanation of how you inspected the database tables and what tables were created. For the latter, you may provide screenshots.
- I struggled with this step and after investigating the web, I found that this would be difficult because the provided template is a short-lived locally embedded h2 database. Instead I changed the hibernate.show_sql value to true, and copied the sql statements made by hibernate, I then converted the syntax to mySQL syntax and pasted it into https://dbdiagram.io, Which gave me the following database structure:

![Screenshot of database schema](./dbPic.png?raw=true)
Screenshot 2023-09-15 190514.png
## Any pending issues with this assignment that you did not manage to solve
No.
