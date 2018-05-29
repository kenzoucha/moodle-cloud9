# moodle-cloud9
A script(s) to use for setting up a Moodle development environment on Cloud9 ( https://c9.io ) with Moodle 3.5

Instructions
===
1. Setup an account on https://c9.io (free account is ok)
2. Make a note of your username ... we are going to need that.
3. From the new account make a new workspace (note the workspace name, we'll need that too. just alphanumerics and hyphens please. no underscores)
  * Workspace Type: "Hosted workspace"
  * Clone from Git URL: "https://github.com/justinhunt/moodle-cloud9.git"
  * Template: "PHP,Apache .."
4. From the bash window of the new workspace, type ./setup.sh
This will upgrade PHP to PHP 7 and install necessary dependencies. Then it will install Moodle.
5. When prompted for your username, enter it
6. When prompted for your workspace name, enter it
7. When its finished running, click the "Run Project" button at top
8. Navigate to the URL that the setup script finished with, and finish the install
9. Remove "setup.sh" and "config.php" and "scripts" directory from the workspace directory. 
10. Happy Moodle Coding!