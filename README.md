## ClinicalPath

ClinicalPath is a freely available visualization system to improve the evaluation of electronic health records (EHRs) in clinical decision-making. 

The system is focused on patient's data analysis, presenting the test results and clinical history longitudinally and was developed in close collaboration with experts in the medical domain to ensure a right fit of the technical solutions and the real needs of the professionals.

## Video demonstration

Follows a video to demonstrate the ClinicalPath system main funcionalities.

https://user-images.githubusercontent.com/2184371/170728069-371fba9e-6e9f-493f-b8fe-08db5e9bcc9d.mp4


## Presentation at IEEE VIS 2022 Conference

Follows a video of the ClinicalPath presented by Claudio Linhares at the IEEE VIS 2022.

https://user-images.githubusercontent.com/2184371/197344405-e42f7985-8ff4-4241-b338-5fac9f745441.mp4


## Download

* You can download the latest version of ClinicalPath system [here](https://github.com/claudiodgl/ClinicalPath/blob/main/ClinicalPath_v2.0.zip). 
* The software is implemented in Java and requires the Java JRE version to execute, that can be obtained [here](https://java.com/en/download).

## Instalation steps

* First, validate that you have Java JRE installed.
* Then, extract the ClinicalPath zip files.
* To open the system, execute the file ClinicalPath.jar.

## Published paper

The system was first published in 2022 on the IEEE Transactions on Visualization and Computer Graphics (TVCG) journal.

* C. D. G. Linhares et al., "ClinicalPath: a Visualization tool to Improve the Evaluation of Electronic Health Records in Clinical Decision-Making," in IEEE Transactions on Visualization and Computer Graphics, doi: [https://doi.org/10.1109/TVCG.2022.3175626](https://doi.org/10.1109/TVCG.2022.3175626).

* ```sh
  @ARTICLE{9779066,
  author={Linhares, Claudio D. G. and Lima, Daniel M. and Ponciano, Jean R. and Olivatto, Mauro M. and Gutierrez, Marco A. and Poco, Jorge and Traina, Caetano and Traina, Agma Juci Machado},
  journal={IEEE Transactions on Visualization and Computer Graphics}, 
  title={ClinicalPath: a Visualization tool to Improve the Evaluation of Electronic Health Records in Clinical Decision-Making}, 
  year={2022},
  volume={},
  number={},
  pages={1-16},
  doi={10.1109/TVCG.2022.3175626}
  }

## Preprint paper

The article is freely available on arXiv in a preprint version: [https://doi.org/10.48550/arXiv.2205.13570](https://doi.org/10.48550/arXiv.2205.13570).

## Data set

The FAPESP COVID-19 Data Sharing/BR Repository (available [here](https://repositoriodatasharingfapesp.uspdigital.usp.br)) contains patient information related to COVID-19 from different institutions.

* The ClinicalPath provides nine anonymous patient information from the FAPESP repository (id list 103007, 387938, 1232020, 1262563, 1300236, 1395592, 1570650, 1591522, 1678020) to exemplify the tool.



## Visualization example

The test results and clinical history of the patient 1300236 in a longitudinally way:

![ClinicalPath](https://user-images.githubusercontent.com/2184371/170779095-3a16e55e-1d9d-4486-b33a-8f2cb47af37d.PNG)

* The time information represents when each test was performed, and is colored with the patient clinical history.
* The test results uses colors and symbols to represent the variation of results.
* Notice that we have a set of Red Series Hemogram tests, in each values varies from the reference value along time. 
* For instance, we can see an increase of the value for the test RDW, achieving very high values in the last days.
