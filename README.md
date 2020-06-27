# job-board-app

## Description:

Final group assignment for [Software Design](https://fas.calendar.utoronto.ca/course/csc207h1).

Job board app that allows users to post jobs, apply for jobs and recommend applicants for jobs. Applicants can upload cover letters and CVs in text format. All program states are saved through serialization. All HR users are associated with a firm. HR users may create jobs. Applicant users may then apply to jobs. Applicants are required to go through a customized sequence of interviews (e.g. group, phone and in person). Interviewer users may then reccomend or not reccomend applicants. The system sends Applicants update messages on their jobs.

In order to facilitate testing, the current date is prompted upon each login. Jobs automatically expire 30 days after being posted.

# Program Images

![login image](https://github.com/alecmmm/job-board-app/blob/master/images/login.PNG "Login")

![open jobs image](https://github.com/alecmmm/job-board-app/blob/master/images/jobs.PNG "Open jobs")

![job application image](https://github.com/alecmmm/job-board-app/blob/master/images/application.PNG "Job application with CV being edited")

## Initialization:

Run from your favourite IDE.

Upon opening, you will be promted to import the default test setup. It is suggested to do this so that test users do not have to be set up. After running, you may override the default test setup, in order to save the program state.

See description of default program state to try out the program:

It's suggested that you first try logging in with lily's username and papssword, as an Applicant.

* Firm 1: Firm ABC
  * HR User:
    * username: kevin
    * password: pass
  * Jobs: 
    * Clown
    * Acrobat
 * Firm 2: CIA
   * HR User: 
     * username: john
     * password: pass
   * Jobs:
     * Hacker
     * Spy
  * Applicant:
    * username: lily
    * password: pass
  * Interviewer:
    * username: holden
    * Firm: CIA
  * Referrer:
    * username: bill
    * Firm: CIA


