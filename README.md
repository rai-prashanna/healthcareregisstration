# HealthCareRegistration 
Using Apache Camel to implement communication between heterogeneous systems for registration and diagnostics of patients. 
Diagnostics centers like this usually provide services that include taking blood or urine tests or making EMR or x-ray examinations. 
Sometimes, they can also provide a so-called “second opinion,” based on test results and the patient’s medical history.

The result of your work will be an application that integrates laboratory information systems and an electronic healthcare record system (EHR), 
which contain information about a patient’s medical history, and a practice management system, which keeps track of appointments, insurance checks, 
finance, and so on. Additionally, you will develop API and integration channels for the new patient portal, which helps patients to make appointments quickly, 
to get reminders, and to check the results of their examinations. The portal will be integrated with the EHR system and with the practice management system.

Portals like this can help a lot in everyday life, when people have less and less time to wait in call center queues, and almost any kind of registration-related 
activities can be done more quickly using a computer or mobile device connected to the internet.

TODO tasks:

* [] Read a message in a standard healthcare industry format from a TCP channel and send it to a message queue.
* [] Read a message from a queue, process it, and save to a database.
* [] Set up transaction management for these operations.
* [] Transform HL7 messages to messages in JSON format.
* [] Create a REST API.
* [] Process files.
* [] Employ Enterprise Integration Patterns to interconnect different systems of the diagnostic centers.
* [] Deploy your applications to Kubernetes (MiniKube).




