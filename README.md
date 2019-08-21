# rpa_tendersearch_bot-1.1
UiPath Robot which is searching updates on the platform with tenders  and collects new updates to the Google Sheets

<h3>What is it?</h3>

`Robotic Process Automation is the technology that allows configuring computer software or a “robot” to emulate and integrate the actions of a human interacting within digital systems to execute a business process. RPA robots utilize the user interface to capture data and manipulate applications just like humans do. They interpret, trigger responses and communicate with other systems to perform on a vast variety of repetitive tasks. Only substantially better: an RPA software robot never sleeps, makes zero mistakes and costs a lot less than an employee.`


<h3>The Latest Version</h3>

`Script version 1.1`


<h3>For installation</h3>

`This script is using Google API for sending and receiving data from Google Drive.`


**Enable Google API**

* Create a project on Google Cloud <https://cloud.google.com/resource-manager/docs/creating-managing-projects>.

* Start Google Drive API in Google Cloud Platform Marketplace <https://console.cloud.google.com/marketplace/details/google/drive.googleapis.com>.

* Create credentials to the project <https://console.cloud.google.com/apis/credentials>. After that, you have got <Client ID> and <Client Secret>.


**Preparing The Script**

* After downloading repository run UiPath Studio and choose the project folder. For more information see the official website of UiPath <https://www.uipath.com/>.

* Rename file `pass.csv.sample` at InActions folder to `pass.csv`.

* In `pass.csv` insert required fields. Note: in this version script works only with <zakupki.gov.ru>.

* Script is ready to run.


<h3>Licensing</h3>

`MIT`


<h3>Overview</h3>

* Process mapping in UiPath Studio

![](https://raw.githubusercontent.com/petrenkosv/rpa_tendersearch_bot-1.1/master/.gifs/process-structure.gif)


* Robot is searching data

![](https://raw.githubusercontent.com/petrenkosv/rpa_tendersearch_bot-1.1/master/.gifs/tender-search.gif)



<h3>Contacts</h3>

* If you want to be informed about new releases of this project, push the <star> button above this page.

* If you have a concrete bug report for this script, please see the Issues section for bug reporting at <https://github.com/petrenkosv/rpa_tendersearch_bot-1.0/issues>.
