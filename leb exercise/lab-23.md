Create a DFD for a hospital management system.

                    +------------------+
                    |   Patients       |
                    +--------+---------+
                             |
                             v
                  +-----------------------+
                  |  Patient Registration |
                  +-----------------------+
                             |
                             v
                     +---------------+
                     | Patient       |        +-----------------+
                     | Database      |<------>| Admin           |
                     +---------------+        +-----------------+
                             |                           |
                             v                           v
                    +---------------------+    +-----------------------+
                    | Appointment          |    | Billing and Payment   |
                    | Scheduling           |<---| Process               |
                    +---------------------+    +-----------------------+
                             |
                             v
                     +---------------+
                     | Appointment   |    
                     | Database      |
                     +---------------+
                             |
                             v
                    +---------------------+
                    | Medical Consultation |
                    +---------------------+
                             |
                             v
                     +---------------+
                     | Medical Record |
                     | Database       |
                     +---------------+

            Explanation of the DFD Components:
            Entities:

            Patients: Patients provide personal and medical information to be registered and managed by the system.
            Doctors: Doctors input medical records and prescriptions during patient consultations.
            Admin: Administrative staff manage patient records, appointments, and billing.
            Processes:

            Patient Registration: Captures patient details and stores them in the Patient Database.
            Appointment Scheduling: Patients schedule appointments, which are recorded in the Appointment Database.
            Medical Consultation: Doctors update the Medical Record Database with patient diagnoses, prescriptions, and treatments.
            Billing and Payment: This process calculates the costs based on services provided and updates the Billing Database.
            Data Stores:

            Patient Database: Stores patient personal and medical information.
            Appointment Database: Stores patient appointments and doctor schedules.
            Medical Record Database: Stores patient medical history, diagnoses, treatments, and prescriptions.
            Billing Database: Stores billing records and payment details.
            Flow of Data:
            Patients provide data to the Patient Registration process.
            The Patient Registration process feeds the data into the Patient Database.
            Appointments are scheduled by patients in the Appointment Scheduling process, and this information is stored in the Appointment Database.
            Doctors input medical information during the Medical Consultation process, which is stored in the Medical Record Database.
            The Billing and Payment process handles payment details and updates the Billing Database.