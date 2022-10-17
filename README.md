README (Practice Mgmt Portal)


Practice Management Portal

Product Plan


Team Details:

Kanishk Shedsale (Role: Team Lead and Data Architect)
Siddharth (Role: Microservices )
Varun Ignatius Arulmani Selvam (Role: Microservices developer)
Sriram (Role: frontend dev )
Ajinkya (Role: Testing and Devops, BA)

Git URL:

        https://github.com/sriram-vt32/cs673-practice-management-portal-



Far vision:

The Practice management portal would mainly be intended as a gateway to access the patient records for the hospital staff. The records include the patient's health history, case notes, scheduling of appointments and progress reports. It will be mainly used by nurses, doctors, Hospital IT, lab technicians to analyze a patient’s medical history, progress, and provide them with some kind of treatment.

Near Vision:

The first Iteration of the product will allow users to perform the following tasks:

1)Access the Menu bar which is going to route to different functional pages like view case notes, view Progress Notes, view Medical History, and all sorts of reports.

2)View a Dashboard which is going to display overall details like number of patient visits, practitioner availability, and recent activities.


Stakeholders:

Providers (Professionals, and Institutions)
Hospital IT service providers
Lab Technician

Personas: (Need to add one for lab technician)


Andy, age 40, a doctor at a local hospital who is an MD, and has been practicing medicine for the last 8 years, and is familiar with computers and is optimistic about health tech. He was using physical paper until now and wants to move everything to an online portal which includes patient history, their case papers and their last visit details


Carolyn, age 35, a nurse, married with 2 children, working at the local hospital, she is a caregiver, counselor, nurturer and shoulder to cry on. Balancing work with childcare means that working overtime or due to last-minute schedule changes can be tough. At the end of each shift, it is easy to feel underappreciated, but making a difference in a patient’s life is rewarding enough to keep her coming back. In her work, Carolyn must quickly and efficiently shift priorities based on overall patient load, changes to individual patient acuity, staffing, and planned and unplanned procedures. She has a basic knowledge of the disease processes for the conditions of those in her care, as well as an understanding of the medications being given and the procedures being implemented. She stays aware of patients’ physiological, psychosocial and mental health needs. Carolyn is computer literate (Facebook, online shopping, surfing the web), but is not a computer expert and doesn’t understand system-level error messages.

Travis, 35 years old, an IT staff, Married, two children, Bachelor’s degree in computer science. As a member of the hospital information technology team, Travis has worked in a clinical environment for eight years and is the frontline point of contact for his hospital’s end users as well as the primary contact with the hospital’s IT vendors. He is responsible for day-to-day end user support, and he is a member of teams that support different short-term and long-term projects. He’s able to shift gears when interacting with end users who have various levels of knowledge and experience. Travis has advanced vendor training, customer service experience, project management experience and troubleshooting skills. Most people are happy to see him coming because he is a problem solver for the end users.

Danielle Brooks, a 40-year-old person has been working more than 5 years in xyz hospital as a lab technician. He is honestly tired of looking up patients records for their respective lab tests from admin department and waste’s more than 10-15 minutes for each patient for pulling up their record and making arrangements for it, Danielle was sincerely hoping the hospital could provide some assistance in this regard to process the patient faster in order to reduce the waiting time and improve customer’s mood who are frustrated by waiting times.


Scenarios: (For each persona):


Doctor checks patient’s medical history in order to perform operation:
Dr. Andy successfully completed a leg amputation surgery. Because of the urgency of the situation, a patient named "John" was brought to the emergency room following a horrible accident. Because Dr. Andy and his colleagues had access to John's previous medical information, they were able to treat the patient more successfully.


Nurse checks patient’s ongoing treatment information:
Michael, a patient with a covid19 was admitted in the local hospital 2 days ago, he still has mild symptoms such as coughing, sneezing, and high temperature. Pam is a nurse in the same hospital, who looks after him regularly until he gets well. But due to some personal reasons, Pam has taken a leave for next 3-4 days and the doctor tells Carolyn to look after Michael in absence of Pam. The next morning, Carolyn comes to check on him, and finds out that he still hasn’t shown any improvements since last couple of days, so she decides to pull his file online from the portal, where she looks up his name in the system and retrieves his ongoing course of antibiotics and decides to inform the doctor about it.


Nurse updates patient’s ongoing treatment information:
After checking on Michael, the doctor advises to change the antibiotics after the current course ends and tells Carolyn to update the information accordingly. She then updates his record with the start date for the new antibiotics, along with the duration and how often he should take it.



Lab technician accesses appointment details for a patient:
Thomas Brooke is a short-tempered patient who always can’t tolerate waiting times and often loses his composure because of it. On a busy Tuesday, Danielle’s lab waiting room was flooded with patients where Thomas was one of them who came to give a blood sample test. The rush of patients was well handled due to the software which Danielle Brooks used in which he was able to confirm the appointment by pulling the case records and performing the tests quickly. This helped improve the customer experience of the hospital.


 IT Technician checks the logs for the daily activities:                                Like every day, Travis, the IT Technician for the hospital, arrives at his desk and gets complaints from multiple doctors that they are not able to add any observations or notes to their patient’s profile. He immediately tries to replicate it with dummy data and spots a bug that is preventing the “Add Observation” feature to complete the task. He checks the logs and confirms the root cause to be that the database is offline or there is a data discrepancy due to which the application is not responding to any of the updates to it. He tries to address this issue and solve it in a considerate amount of time and reverts to the doctors that the issue is resolved, and they can add their observations successfully now.

IT Technician creates access credentials for a newly joined doctor:                There is a latest addition to the team of doctors, Dr. Das, at the hospital and he is to be briefed about the various features of the application that will make his work easier, help to keep it organized and recorded. Travis walks Dr. Das through the login to each feature available for the user profile : doctor. Travis also generates a new ID and password for Dr. Das, and he is to use these credentials throughout.
User stories: (2 for each scenario):


 As a doctor, I need access to all of my patients' records.
 As a doctor, I want a separate view that lab technicians and IT administrators do not have access to.
As a nurse, I should be able to retrieve ongoing treatments, health history, and progress reports for any patient.
As a nurse, I should be able to add, update or remove any ongoing treatments for a patient, after approval from the doctor.
As a lab technician I want to be able to pull up the records of the patient quick to verify and perform the required lab tests. (feature)
As a lab technician I want to be able to operate easily on the UI with a navigation pane to locate necessary file and be able to add or remove them and also be able to update them(feature)
As an IT Technician, I need to have access to the application logs to cater any problems faced.
As an IT Technician, I must have a separate user profile that can create user ID for any new professionals to ensure their access to the application.
As an IT Technician, I must be informed of any updates made to the application, to brief the end-users about the change in terms of their usage.


Product Backlog URL:

https://www.pivotaltracker.com/n/projects/2605482
