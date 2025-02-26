# AutoMediQu
Automatic queuing model for hospitals 
The prescriptions are handwritten by the doctor and the different tests units and pharmaceutical units process the test and medicines request by the patient only when the patient has taken the receipt to the unit, this creates unnecessary rush and crowd at the hospitals. The model seeks a solution to this problem using LSTMs and Gated Recurrent Networks to identify the raw pen strokes and convert the data into a digital form which the computer can understand and then it integrated with the hospital database as each patient has a unique ID the ID is enqueued in the respective testing units and the pharmaceutical unit enqueues the patient' medicine list along with the packaged items so the patient will only need to collect the medicines. This can in turn help the hospitals to manage large crowds.
## Technologies Integrated in the model
### Machine learning models:
As the doctor writes the prescription the data is identified the pen strokes is the input data, it is preprocesses then every prescription will have a patient id which is unique for all patients and the patients are registered in the database so that the registration wont happen every time they visit the hospital, that ID is used at all the counters for virtually enquing the patient for any medical test and pharmaceuticals.
![Screenshot (2)](https://github.com/user-attachments/assets/d52927ba-8819-49e4-b11c-dd594bd39285)

