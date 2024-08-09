# QML-for-Conspicuity-Detection-in-Production
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 2
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Fraunhofer ITWM. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1AcctFeXjchtEhYzPUsHpP_b4HGlI4kq9/view?usp=sharing) to view the project description.
  - YouTube recording of the project description - [link](https://youtu.be/Ac1ihFcTRTc?si=i6AIVfQQh8ymYQYp)

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:
 - Full Name: Mah Noor
 - Womanium Program Enrollment ID: WQ24-lKsEGZqa9muencO



### Project Solution:
I performed first four tasks of the project. In **task 1**, we were required to get a familiarity with PennyLane. The modules that we had to do were: “Introduction to Quantum Computing”, “Single-Qubit
Gates” and “Circuits with Many Qubits”. In PennyLane, we have a define a device as a backend. We define the circuit as a function and this function should always return some measurement. We learned different types of measurements we can perform on quantum circuits.
For task 2, we have to operate the variational classifier for two different sets. The first one is the parity test and the second one is the recognition of the first two classes of flowers in the famous Iris dataset. I have included Jupyter notebooks for both examples in the folder **task_2**. The general workflow is the same in both examples. In the first step, we define some method to map our classical data onto the quantum states. Then we define our quantum circuit that includes parametrized layers. After that, we define loss, cost function, and optimizer to train the model. At the end, we will perform measurements. 
The **task 3** is related to Quanvolutional Neural Networks. It's a hybrid model. This model is used for processing images. For the circuit, we used an embedding layer, then a random circuit and finally the measurement. After that, we defined the convolution scheme. 
In **task 4**, we have to create a QML model that should be able to predict sine values correctly. I used 20 points for training the data and 20 for testing the data. I used angle embedding to encode the data. Then I defined the circuit. After that, I did some classical post-processing that involved cost and loss functions. I realized that changing the step size of the optimizer significantly improves the model. 

