# MedicalWarehouseManager
A C++ project simulating a medical supply distribution system, featuring object-oriented design, efficient resource management using the Rule of Five, and dynamic data structures. The program handles beneficiaries, volunteers, and supply requests in real time, leveraging queues, vectors, and enums for streamlined simulation and operations.

-  Clone the Repository
-  The project includes a Makefile for automated compilation.
-  Run the Program: An executable called medical_warehouse will be created, run it. Should appear: "Medical services are now open!"
-  Project Structure
          - src/: Contains all the C++ source files (.cpp) for implementation.
          - include/: Includes the header files (.h) defining the classes and methods.
          - bin/: Stores the compiled executable.
          - configFileExample.txt: An example configuration file to initialize the system.

- Example Commands:
- register CityHospital hospital 5 200 (Registered beneficiary: CityHospital (hospital) with maxRequests: 200)
- request 5 (Request added for beneficiary ID: 5 (Status: Pending))
- step 3 (Advanced simulation by 3 steps.)
- beneficiaryStatus 5 (Beneficiary ID: 5
                       Request ID: 1, Status: Collecting
                       Request ID: 2, Status: On the Way
                       Requests Left: 198)
- close (Request ID: 1, Beneficiary ID: 5, Status: DONE
         Request ID: 2, Beneficiary ID: 5, Status: ON THE WAY)
