# Assignment 2 by Antonio Pili 34467512

# This is the Link to my Domain

link: www.urfootball.space

# Video Explainer Link

link: 

## WordPress Integration

This is the essential code I used to put WordPress on top of my Amazon EC2 web server.

I used an Amazon EC2 Ubuntu instance as my base and placed the WordPress website on top of it.

### WordPress Installation

- Install Apache2, MariaDB, MySQL, and more
  1. Install Apache2, because this gives you access to a web server by going to the terminal and inputting "sudo apt install apache2"
  2. Updated my Ubuntu Instance
  3. Installed MariaDB for the data service, input in the terminal is "sudo apt install mariadb-server mariadb-client -y".
  4. I obtained MariaDB, and I need a root password. "sudo mysqp_secure_installation" is the input to create a root password.
  5. Installed php because WordPress runs on it, the code being "sudo apt install php php-mysql php-gd php-client php-common -y"
  6. Opened a new tab and look up "Download WordPress.org" Hover your mouse over the download button, right-click, and click on "copy link address"
