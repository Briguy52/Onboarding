RoboSub CS Onboarding
====================

In your web browser...
* Make an account at GitHub.com
* Send your GitHub username to Austin McKee, he will give you access to the organization and the appropriate repositories

On your native operating system...
* Install VMWare from the Duke OIT Website
* Install Ubuntu 14.04 LTS

On your newly created virtual machine...
* Update dependencies ```sudo apt-get update```
* Install git ```sudo apt-get install git```
  - git config --global user.name "Your github username"
  - git config --global user.email youremail@example.com
* Install Python 3 if not already installed
* Install eclipse (use ubuntu software center)
* Install pydev
* Install kivy
  - ```sudo add-apt-repository ppa:kivy-team/kivy```
  - ```sudo apt-get update```
  - ```sudo apt-get install python3-kivy```
* Clone this repository
  - ```git clone https://github.com/DukeRobotics/TurtleSimulator.git```
* Add this project to eclipse as a PyDev project
* Run ```gui.py``` from eclipse to verify that your installation is working properly (if eclipse doesn't recognize the kivy package, close and reopen eclipse)

If you have any trouble with any of this don't hesitate to call Austin McKee at **(423) 972-3753** at *anytime*. He's always happy to answer any questions you have day or night.
