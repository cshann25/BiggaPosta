# BiggaPosta
This tool can be used to automatically post text, pictures, or videos to Facebook ONLY

Introduction

The BiggPosta(FBO) App is a desktop application designed to help small business owners or 
anyone with a need to post content to Facebook automatically on a schedule. The program uses 
Facebook API to post to Facebook and saves users time and money by automatically posting 
random media from a local folder filled with the company's pictures or video ads at a set time 
chosen by the user.
The program has a user-friendly Graphical User Interface (GUI) that allows the user to enter 
their Facebook developer account information, the caption, and media folder location. The user 
can set up their times and days to post and customize their post by selecting a custom caption and 
hashtags.
The program consists of four main tabs, including Home, FB Token Posts, Auto-Posts, and Logs. 
The Home tab shows the user's data, including the media folder location, app id being used, app 
secret being used, the user token being used, the page id being used, and the caption that will be 
posted with the random media.
The FB Token Posts tab allows the user to enter their Facebook developer account information, 
the caption, and media folder location. This information is saved in the file user_data.txt and 
used by the Auto-Post tab to post at the scheduled times.
The Auto-Posts tab allows the user to set up their times and days to post, and clicking the 
schedule button saves and sets the schedule. There is a rest schedule button that clears the 
schedule and the schedule.json file, allowing the user to save a new schedule by setting the days 
and times and then clicking schedule.
The Logs tab simply shows all activity on the program. The program has a set of different 
components that work together, including the GUI, Facebook API, threading, and the schedule 
package. The code is well organized and structured, making it easy to understand and maintain.
System Architecture 
The program is designed to run on a local machine and uses Facebook API to post content on a 
Facebook page automatically at scheduled times. The system architecture of the program is 
divided into several components, including the User Interface, Facebook API, Schedule, and 
Logging. The User Interface component is the front-end of the program and allows the user to 
configure the program settings, schedule posting times, and view logs. The Facebook API 
component handles the authentication and authorization of the program and interacts with 
Facebook Graph API to post content on the user's behalf. The Schedule component allows the 
user to schedule posting times and runs in the background to post content at the specified times. 
The Logging component records all program activity and stores it in a log file for future 
reference.
Overall, the program architecture is designed to be modular and easy to maintain, with each
component responsible for a specific task. The use of Facebook API and Schedule components 
allows the program to automate the process of posting content on Facebook, reducing the 
workload for small business owners and anyone who needs to post content on a regular basis.

User Interface 

The User Interface section of the technical documentation provides a detailed description of the 
graphical user interface (GUI) of the program. It outlines the different components of the user 
interface, including the four tabs: Home, FB Token Posts, Auto-Posts, and Logs.
The section also explains how the user interacts with the program through the GUI to input their 
Facebook developer account information, set up the posting schedule, and customize the caption 
and hashtags to be used in the posts. It also describes the customization options available to the 
user, including the ability to schedule posts for seven days a week, three times a day, and post 
random JPEG, PNG, or MP4 files.
The User Interface section is important because it helps users understand how to interact with the 
program and customize it to suit their needs. It also helps developers understand how the 
different components of the user interface are connected and how they work together to create a 
seamless user experience.

Code Structure 

The Code Structure section of the technical documentation provides a detailed overview of the 
different functions and classes in the program, as well as the code flow and organization. The 
main program code is divided into several files, with each file containing specific functionality. 
The main file is "app.py", which initializes the main UI and connects to the different tabs. The 
"auto_post.py" file contains the functionality for scheduling and posting random media to 
Facebook. The "fb_token_posts.py" file contains the functionality for setting and saving the 
Facebook API credentials, media folder location, and caption. The "home_tab.py" file contains 
the functionality for displaying the user's saved Facebook API credentials, media folder location, 
and caption. The "logs.py" file contains the functionality for displaying the program logs.
The program follows a modular design pattern, with each file containing specific functionality. 
The main program file initializes the main UI and connects to the different tabs. The different 
tabs are encapsulated into their own files, which contain the functionality for their respective 
tabs. This design pattern makes it easy to maintain and update the program.
The program also utilizes several third-party libraries and modules, such as PyQt5, requests, 
logging, and schedule. These libraries and modules provide additional functionality and simplify 
the development process.

Dependencies 

The Dependencies section lists the third-party libraries and modules used in the program, along 
with instructions on how to install them. The program uses several modules and packages, 
including os, sys, glob, json, random, requests, threading, logging, schedule, and several PyQt5 
classes and widgets.
Each dependency is listed with its name, version, and purpose. The installation process is 
explained in detail, with instructions on how to install the dependencies using pip or another 
package manager.
It is important to ensure that all dependencies are installed correctly and up-to-date in order to 
ensure the proper functioning of the program.
Installation and Configuration 
The installation and configuration process for the program involves downloading the program 
files, extracting them into a folder, and running the executable file. The user is required to have a 
Facebook developer account and provide the necessary credentials in the program to enable it to 
post to Facebook on their behalf. Additionally, the user is required to specify the location of the 
media files they want the program to post randomly, and set up a posting schedule.
The user is advised to run the program as an administrator to ensure it has the necessary 
permissions to carry out its functions. The system requirements for running the program are 
outlined, including the supported operating systems and hardware specifications.
Instructions for installing and configuring the dependencies required to run the program are 
provided, including the installation of Python, PyQt5, and other third-party libraries. These 
instructions are provided in the form of commands to be executed in the command line interface 
or terminal.
After successful installation and configuration, the user can start the program and begin using its 
features to automate their Facebook posts.

Testing 

The program was tested extensively for a period of three months by having it post to a business 
Facebook account. The testing process included various scenarios such as checking the
scheduled posts, checking the content of the posts, and verifying that the program posted at the 
correct time and on the correct days. All scenarios were successful, and no major issues were 
identified during the testing period.
To document the testing process, each scenario was logged in a test plan document. The 
document included a description of each scenario, the expected results, the actual results, and 
any issues or observations made during testing. This document was used to track the progress of 
the testing process and ensure that all scenarios were completed successfully.
Overall, the program was tested thoroughly, and all scenarios were successful, indicating that the 
program is stable and reliable for use.
Maintenance and Support 
The Maintenance and Support section describes the approach that will be taken to maintain and 
support the program after it is deployed. It includes plans for bug fixes, updates, and ongoing 
support for users. The summary of the Maintenance and Support section may include the 
following:
  • The program will be regularly maintained and updated to fix bugs, improve performance, 
    and add new features as needed.
  • Users can report bugs and request new features by emailing the developer at 
    cshann25@live.com.
  • The developer will provide ongoing technical support to users who experience issues 
    with the program.
  • The program will be periodically reviewed to ensure that it continues to meet the needs of 
    users and remains up-to-date with changes to the Facebook API.
  • The developer will monitor user feedback and usage statistics to identify areas for 
    improvement and to guide future development efforts.

Conclusion 

The BiggPosta(FBO) app is a valuable tool for small business owners or anyone who needs to 
automatically post content to Facebook on a schedule. It offers a user-friendly interface, 
customizable posting schedule, and the ability to post random media from a local folder.
The system architecture consists of several components, including the GUI, Facebook API, 
schedule module, logging module, and file I/O operations. The program is organized into several 
classes and functions, making it easy to understand and modify.
The installation process is straightforward, with the program provided in an executable format 
along with the required files and folders. However, the user must run the program as an 
administrator.
Testing of the program was conducted over a period of three months, during which the program 
successfully posted content to a business Facebook account. Several scenarios were tested to 
ensure that the program met its requirements and performed as expected.
Known issues and limitations are documented for future reference, including the need to run the 
program as an administrator and the limitations of the Facebook API.
Overall, the BiggPosta(FBO) app is a valuable tool for small business owners or anyone who 
needs to automatically post content to Facebook on a schedule, and its well-documented code 
and testing process make it a reliable choice for users
