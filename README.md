# Vehicle Detection Fraud

Personal project analyzing data on vehicle insurance claim fraud.

## Data:

-   `fraud_oracle.csv` dataset from: <https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection?resource=download>, originally from Oracle Database.

## Definition of Variables

-   **Month**: The month in which the insurance claim was made.
-   **WeekOfMonth**: The week of the month in which the insurance claim was made.
-   **DayOfWeek**: The day of the week on which the insurance claim was made.
-   **Make**: The manufacturer of the vehicle involved in the claim.
-   **AccidentArea**: The area where the accident occurred (e.g., urban, rural).
-   **DayOfWeekClaimed**: The day of the week on which the insurance claim was processed.
-   **MonthClaimed**: The month in which the insurance claim was processed.
-   **WeekOfMonthClaimed**: The week of the month in which the insurance claim was processed.
-   **Sex**: The gender of the policyholder.
-   **MaritalStatus**: The material status of the policyholder.
-   **Age**: The age of the policyholder.
-   **Fault**: Indicates whether the policyholder was at fault in the accident.
-   **PolicyType**: The type of insurance policy (e.g., comprehensive, third-party).
-   **VehicleCategory**: The category of the vehicle (e.g., sedan, SUV).
-   **VehiclePrice**: The price of vehicle.
-   **FraudFound_P (changed name to FraudFoundP)**: Indicates whether fraud was detected in the insurance claim.
-   **PolicyNumber**: The unique identifier for the insurance policy.
-   **RepNumber**: The unique identifier for the insurance representative handling the claim.
-   **Deductible**: The amount that the policy holder must pay out of pocket before the insurance company pays the remaining costs.
-   **DriverRating**: The rating of the driver, often based on driving history or other factors.
-   **Days_Policy_Accident (changed name to DaysPolicyAccident)**: The number of days since the policy was issued until the accident occurred.
-   **Days_Policy_Claim (changed name to DaysPolicyClaim)**: The number of days since the policy was issued until the claim was made.
-   **PastNumberOfClaims**: The number of claims previously made by the policyholder.
-   **AgeOfVehicle**: The age of the vehicle involved in the claim.
-   **AgeOfPolicyHolder**: The age of the policyholder.
-   **PoliceReportFiled**: Indicates whether a police report was filed for the accident.
-   **WitnessPresent**: Indicates whether a witness was present at the scene of the accident.
-   **AgentType**: The type of insurance agent handling the policy (e.g., internal, external)
-   **NumberOfSuppliments (changed name to NumberOfSupplements)**: The number of supplementary documents or claims related to the main claim, categorized into ranges.
-   **AddressChange_Claim (changed name to AddressChangeClaim)**: Indicates whether the address of the policyholder was changed at the time of the claim, categorized into ranges.
-   **NumberOfCars**: The number of cars insured under the policy, categorized into ranges.
-   **Year**: The year in which the claim was made or processed.
-   **BasePolicy**: The base policy type (e.g., Liability, Collision, All Perils).
