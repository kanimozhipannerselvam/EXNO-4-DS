
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:

       ![320359396-c0fcc85b-1a64-42a1-b695-a77acc191a1c](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/a58fef1d-b294-43fb-86f4-2a6db99fb261)

![320359396-c0fcc85b-1a64-42a1-b695-a77acc191a1c](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/c45f3ae7-ea66-451d-af8c-32177f05ecc0)

![320359458-3c511b62-cf5b-4ed4-aafd-7e98ef34adb1](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/ba464db8-d6ae-4f4d-8087-18493d942836)

![320359513-4a33bbf5-aa3d-44e0-885f-862bbc8535b0](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/0a41b7bf-a50f-48a4-a89b-60f73a1d12af)

![320359551-49956ce8-30ef-49a5-9373-684c97e50dd1](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/b97979e0-9264-49fe-be83-e46efdf70014)

![320359618-00c4fce9-72b3-4825-9684-a530b9bb5b03](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/f3e0ebcc-a696-4651-bb6d-8c40fe155017)

![320359687-fedaf993-1b6f-4303-9411-5fce5446dc56](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/6c3e6b88-af64-4cbc-b790-0e60b9f7be8d)

![320359829-990e0bbe-fcd0-45a3-a3bc-9d99a496b847](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/d0bd8e59-f39c-41ba-96ef-6209b75c3949)

![320359891-069e2e11-8fdb-472c-b080-abc17afb3637](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/d3d644be-3ba7-4883-9e11-439c95ce036f)

![320359945-83cbfc9d-5fc7-49d9-abed-1de6f5e9794c](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/bbe66248-df84-46de-9641-5a0f6e1403bf)

![320360023-9ab2c4a5-332f-4b83-bf85-d4a3812b0e6c](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/1790d535-3b16-4a31-8449-2a5475108540)

![320360157-9d7ff7f7-b75b-4c24-9ba0-db197319be88](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/e2c5cb69-c7d4-4103-93f6-e4c6bd4b08e7)

![320360372-7d8cdcfe-5c4f-4adc-a7bd-325c2b1c7b16](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/ebfee1b1-f4ee-495a-8310-5a5b13526b0e)

![320360442-e1b84a1d-3857-4847-aec2-c0cbf396fd78](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/3a9ee141-c558-4b6a-89a5-3ef139f6492f)

![320360497-060bf5fd-17ec-4214-b050-141f75ea4947](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/2be6bfb8-0bcf-4e46-983e-c629b42080f9)

![320360600-dc510697-83ee-406b-82b4-64a64ac02067](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/08f72f8c-3931-4446-82c4-1ef1ff87c837)

![320360666-c3870d08-7ae6-4a25-a83f-17e242e86a76](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/ac1eddca-74bc-4514-83bb-679f3dc6d422)

# **Feature Selection**

![320360875-44e6c707-522d-46c2-8dc9-ead0ec8da4d7](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/bfd17dc5-da0e-4759-b0d2-36f5e9614eee)

![320360980-2d3622e5-a59e-493f-8e84-d7138ccfa65b](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/ed13d33c-e1f4-4c8f-b6a1-459642f52a91)

![320361039-e4b7b9ad-9450-451c-9e50-59ac46f9d5bd](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/3461e5b5-3e53-4ed2-9807-daf73b759a26)

![320364838-6a99cb65-069e-49aa-8100-7b56f3973fce](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/6e8e0e4d-53bb-460d-adf2-1d16f4d98e52)

![320364941-e39261c9-fcf4-4aaa-9abb-9ceb0b1d5bed](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/dc72a7be-7dfd-4b02-9390-6187a25f927c)

![320365473-01b6908a-22f6-4ffe-9a6a-a066ee406cad](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/9466eedd-edd4-4b2f-bbe8-9e8c8e0efed9)

![320366296-bd40332c-e997-4618-82e1-f33d78ee5af9](https://github.com/kanimozhipannerselvam/EXNO-4-DS/assets/119476060/55bda2f1-7440-4df4-bba1-035a7213282f)



       
# RESULT:
       Thus the program to read the given data and perform Feature Scaling and Feature Selection process and save the data to a file is been executed.
