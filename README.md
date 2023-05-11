# HospitalSystem
This project implements a queue management system for a hospital that has 20 different specializations and only 5 available spots for each specialization. The system allows patients to add themselves to the queue and be picked up by the doctor.

## Adding a Patient
To add a patient to the queue, follow these steps:

1- Enter the requested specialization (1-20).
2-Enter the patient's name and status (0 for regular or 1 for urgent).
3-If there are already 5 patients in the queue for that specialization, the system will apologize and not accept the patient.
4-If the patient is regular, they will be added to the end of the queue. If the patient is urgent, they will be added to the beginning of the queue.
## Printing Waiting Patients

To print the waiting patients for a particular specialization, the system will display the patients' names and their status. This information will only be displayed for specializations that have waiting patients.

## Doctor Pickup
To pick up a patient, follow these steps:

1- Enter the requested specialization.
2- If there are no patients in the queue for that specialization, the system will inform the doctor.
3- If there are waiting patients, the system will ask the patient to go with the doctor and remove them from the queue.
## Technology Used
This project was implemented using cpp.
