# CSE327-Software Engineering Project Summer 2020

###Lungs Disease Detection using ML

Prepared by

####Abdullah Al Mahfuj Shaan (1721275042)

####Shoumik Mahbub Ridoy (1721050642)

####Khan Afnan Rahad (1721578042)

North South University

21.08.2020

Table of Contents
Table of Contents	ii
Revision History	ii
1.	Introduction	1
1.1	Purpose	1
1.2	Document Conventions	1
1.3	Intended Audience and Reading Suggestions	1
1.4	Product Scope	1
1.5	References	1
2.	Overall Description	2
2.1	Product Perspective	2
2.2	Product Functions	2
2.3	User Classes and Characteristics	2
2.4	Operating Environment	2
2.5	Design and Implementation Constraints	2
2.6	User Documentation	2
2.7	Assumptions and Dependencies	3
3.	External Interface Requirements	3
3.1	User Interfaces	3
3.2	Hardware Interfaces	3
3.3	Software Interfaces	3
3.4	Communications Interfaces	3
4.	System Features	4
4.1	System Feature 1	4
4.2	System Feature 2	4
5.	Other Nonfunctional Requirements	4
5.1	Performance Requirements	4
5.2	Safety Requirements	5
5.3	Security Requirements	5
5.4	Software Quality Attributes	5
5.5	Business Rules	5
6.	Other Requirements	5
Appendix A: Glossary	5
Appendix B: Analysis Models	5
Appendix C: To Be Determined List	6


####Revision History
Name	Date	Reason For Changes	Version
Abdullah Al Mahfuj Shaan	21.08.2020	Written all the parts.	V1
Abdullah Al Mahfuj Shaan	5.10.2020	Revised Introduction and System Features	V2 


 
###1.	Introduction

####1.1	Purpose 

The purpose of this project is to detect lung function decline early, with a vision to have a prediction about the lungs disease that may follow up along with the declining function. After successful prediction; patients, doctors and their families can have a better understanding and prognosis after they are first diagnosed with the incurable disease. Improved severity detection would also positively impact treatment trial design and accelerate the clinical development of novel treatments.

####1.2	Document Conventions

The SRS was provided by the course instructor. Fonts that were used for this template is Times New Roman, font size 11, and line spacing 1.0.

####1.3	Intended Audience and Reading Suggestions

The SRS is intended towards people who are software developers, doctors, patients, tech companies that intend to create new and innovative models for the project. It is most understandable when one will read the SRS from top to bottom without skipping certain parts that might be very crucial in understanding the latter part of this SRS. It has been written in a very simple manner so that any people who is willing to get some idea about the project.

####1.4	Product Scope

The project has been developed mainly to help innovators, patients and doctors that will be able to use this and can have better understanding about the prognosis and severity detection of the disease. In treating idiopathic pulmonary fibrosis (IPF), fibrosing interstitial lung diseases (ILDs) and other respiratory diseases, including emphysematous conditions, the community allows for rapid development. Its mission is to bring radiologists, physicians and computer scientists from all over the world together to optimize therapies based on imaging. 

####1.5	References

 (https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/data, 2020)
 

Reference	Website

Project Idea	https://www.osicild.org/

Dependencies	https://docs.anaconda.com/anaconda/user-guide/tasks/install-packages/

Tensorflow	https://www.tensorflow.org/install/gpu




###2.	Overall Description

####2.1	Product Perspective

This is almost a new idea and project work, most of the work has been done in exploratory fields and no such work has been made before because this project is very new in this area. People are still working on the idea and very less progression has been made so far. The authors have tried their level best to have some sense of product output and they were very little successful. The authors are still working on finding better results. 

####2.2	Product Functions

	User Login

	User Inputs Image

	System uses its machine learning API to deduce a result.

	System outputs the result

	User finds the result, stores it in the database. 

	User has the option to print results.

	System stores the image files for further prediction for its dataset.

####2.3	User Classes and Characteristics

The project is based on medical purposes. Where patients will be aware of whether they are suffering from lung diseases or not? So, user classification will be based on the patient interface. 


####2.4	Operating Environment

The system is built specifically for Windows OS. To successfully run this project, one needs to have a high configuration computer as it uses machine learning in its backend. The system does not have a cloud compatibility right now, but the authors have their vision to work on cloud platform in future. So that anyone can access the system anywhere and have the benefits of the system.

####2.5	Design and Implementation Constraints

There are certain hardware limitations that are to be kept in mind while running the system. The project requires around 4 hours of training phase once it’s run using the local machine. Processor, GPU and RAM requirements are minimum core i5 9th generation or equivalent, at least 8GB of VRAM or more, 16GB or RAM or more.  Firstly, this project needs to be run on Anaconda, with Jupyter Notebook. Then the website needs to be launched. Programming standards are not necessary at the beginning, but if the company is willing to make further changes to the interface, they need to have excellent knowledge on scientific python and PHP, CSS and HTML for the website.

####2.6	User Documentation

User documentation is not available at this moment.

####2.7	Assumptions and Dependencies

	Hardware Requirements: Intel Core i5 9th generation or equivalent, 16GB of RAM or more, 8GB of VRAM

	Software Requirements: Anaconda Navigator, Jupyter Notebook

	Network: Stable internet connection for full potential usage.

###3.	External Interface Requirements

####3.1	User Interfaces

In the dashboard, the user will get the login/Signup interface. Users must have internet access to get into the main interface. There will be two panels in the application, one for the admin and another for Users. In the home screen, they will get the input bar where user input has to be .dicom format files. After getting the input file on the back-end our main code has processed the image. Then the processed image comes up with the accuracy and the possibility of lung disease.  

####3.2	Hardware Interfaces

The system does not have any hardware interface.


####3.3	Software Interfaces

The user will have to visit our website where he/she will have the option to either login as an existing customer or register as a new one. After the login, they will have the options to check their new reports or see their report results history. There will also be an option where while checking their reports, they will have the option to contribute their reports and results in order to the help the algorithm to achieve better accuracies.

####3.4	Communications Interfaces

Communication Interfaces are not required for this system.

###4.	System Features

This part contains the features of the system. 

####4.1	User Registration and Login


####4.1.1	Description and Priority

	This is very important for each and every user. The system will every time ask for registration/ login. So that users have access to their previous results and data.
  
####4.1.2	Stimulus/Response Sequences

	Insert username, password, upload images, get results, compare results.
  
####4.1.3	Functional Requirements

	
REQ-1:	Jupyter Notebook, Tensorflow

REQ-2:	Users can use this feature.

####4.2	Upload Files

####4.2.1	Description and Priority

	This is very important for each and every user. Because without uploading the correct format of the data, the system will not be able to predict results.
  
####4.2.2	Stimulus/Response Sequences

	Insert Images, Upload, Get Results. 
  
####4.2.3	Functional Requirements

	
REQ-1:	Jupyter Notebook, Tensorflow

REQ-2:	Users can use this feature.

###4.3	Results and Predictions

####4.3.1	Description and Priority

	This is the ultimate feature, because every user came here for their predictions from their data.
  
####4.3.2	Stimulus/Response Sequences

	Your predictions are, get help, predict again. Save data
  
####4.3.3	Functional Requirements

	
REQ-1:	Access to previous recorded results.

REQ-2:	Users can use this feature.


###5.	Other Nonfunctional Requirements

####5.1	Performance Requirements

	Access to a PC, Smartphone or Laptop

	Stable Internet Connection

####5.2	Safety Requirements

•	The system will not permit operation unless the user is registered

•	The system will not show the user the wrong accuracy.

•	The system will not detect any wrong data while using dicom format files.

•	The system will not use the user’s information. If they are not willing to give the information.


####5.3	Security Requirements

•	User login with confirming password (For double-checking).

•	Patients are not been able to access the other patient’s data.

•	Confirmation of any action that will result in permanently deleting or corrupting data.

•	If the patient gives permission to use his/her information then only the code admin can access the information. And he/she will be the contributor. 

####5.4	Software Quality Attributes

	Mean Time Between Failure: There might be complications sometimes, but most of the times the system will be running flawlessly.

	Availability: As this will be on a website anyone can access it anytime and see their results and predictions.

	Updates: Frequent updates might be made due to increasing accuracy also inserting new data to the website. 

####5.5	Business Rules

The project is developed entirely to help the people in this time of pandemic to get medical advice. It is a doctor free experience so anyone can enjoy the service at home without the need to go to a doctor to see the report.

###6.	Other Requirements

There are no other requirements for the system.

###Appendix A: Glossary
Machine Learning	The process of programming computers explicitly.
PHP	PHP is an HTML-embedded Web scripting language. This means PHP code can be inserted into the HTML of a Web page.
HTML	HTML (HyperText Markup Language) is the most basic building block of the Web.
Transfer Learning	Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.
DICOM	Digital Imaging and Communications in Medicine
Tensorflow	The core open source library to help you develop and train ML models.
IPF	Idiopathic pulmonary fibrosis
ILD	Interstitial lung diseases

###Appendix C: To Be Determined List

This system is mainly built for innovators, patients, doctors and their families. So far, we have added the essential functions that might help determine a positive result for the patients. The authors have planned to make some future updates too.

	Get real-time access to hospitals that are working to help the patients.

	Use transfer learning for the system.

	Better neural network design

These are some of the features that the authors want to implement in the upcoming days. 

