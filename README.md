# hdh
scripts to install and run HDH for editing developer-Hub docs at Harness

### hdh_setup ###
A bash script designed to: 
  * Check if brew is installed.  If not install it.
  * Install node and git (if needed)
  * Do a git clone on the Developer-Hub repo 
  * Go into the Developer-Hub repo ($HOME/git/harness/developer-hub)
  * Install yarn
  * Give you a message that it is finished.

This script need only be run one time.  However if it's run more than one it is sufficiently idempotent to cause no harm.  Just run it one time using ./hdh_setup and follow the prompts.

### doclaunch ###
A bash script designed to:
  * CD into the git repo on your system ($HOME/git/harness/developer-hub)
  * Start up the docs env 
  * Launch your systems default browser at http://localhost:3000
  * If it detects that the env in already running (a yarn process) it will ask if you want to shutdown the mini webserver in yarn.

Place this into your path for launch anytime you need it.  


    
  
    
