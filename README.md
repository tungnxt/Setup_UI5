# Setup IDE for SAP UI5

> Written by Tungnx37
> 
> 20/11/2024
> 
### Objectives
- After completing this lesson, you will be able to:
  * Setup enviroment for BAS or Visual Studio code - SAP UI5
  * Understand part of BAS 
### Contents
[I. Documentations ](#iDocumentations) 

[II. Setup IDE ](#iiSetUpEnviroment)  

- [2.1. BAS or Visual Studio Code](#BAS-or-Visual-Studio-Code)

- [2.2. Setup SAP BAS - SAP Business Application Studio ](#Setup-SAP-BAS---SAP-Business-Application-Studio)
 
- [2.3. Setup Visual Studio Code](#Setup-Visual-Studio-Code)

- [2.4. Final](#Final)


<a name = "iDocumentations"></a>
# I. Documentations
<a name="Documentations"></a>
- SAP documentaions for BAS: https://help.sap.com/docs/bas/sap-business-application-studio/getting-started
- App Dev using BAS by UI5: https://sapui5.hana.ondemand.com/sdk/#/topic/6bbad66475d040f39df6fbbaabe6f40f
  
  *Take a note: This is most important web will help developers when using SAP UI5: https://sapui5.hana.ondemand.com/sdk/#/*
- Introduction by SAP about BAS: https://learning.sap.com/learning-journeys/develop-full-stack-applications-using-productivity-tools-in-sap-business-application-studio/introducing-sap-business-application-studio-bas-_fc1cf45a-fbd9-4399-8954-653cef7f7763

  *Lets take a tour about BAS link above*
- Here the guide-end-to end for dev a fiori app with back-end using RAP(Abap On Cluod) and front-ends using Fiori Element: https://learning.sap.com/learning-journeys/getting-started-with-creating-an-sap-fiori-elements-app-based-on-an-odata-v4-rap-service/using-sap-fiori-tools-to-boost-your-app-development

  *Note that: Fiori Elements not fiori free style but you guys can check it out to understand what is fiori element*



 <a name ="iiSetUpEnviroment"></a>  
# II. Setup IDE 
 <a name="Setup enviroment"></a>  

##  BAS or Visual Studio Code

#### Understand SAP BAS
- What is SAP BAS ( SAP Business Application Studio )  ?
  * SAP BAS is based on Code-OSS, an open source used for building Visual Studio Code.
  * SAP BAS is a new SAP Business Technology Platform (SAP BTP) service that offers a modern development environment.
  * At the heart of SAP Business Application Studio are the dev spaces. The dev spaces are comparable to isolated virtual machines in the cloud containing tailored tools and preinstalled runtimes per business scenario, such as SAP Fiori, SAP S/4HANA extensions, Workflow, Mobile and more.
  
-> In summary, BAS is an IDE provided by SAP, suitable for developing applications within the SAP ecosystem. In BAS, SAP pre-installs the necessary tools for each type of Dev Space, and SAP also offers options to select additional tools when needed.

- Trial Plan Restrictions
![image](https://github.com/user-attachments/assets/d4046ca5-29d3-4348-9876-62796cdc1eec)

#### SAP BAS vs Visual Studio code
- Note that: If you use VS Code for development, you will need to manually install various tools, and possibly Cloud Foundry if you need to deploy your application. This process requires a certain level of understanding of Fiori app development. Therefore, it is recommended to use SAP Business Application Studio (BAS) instead, as it simplifies these tasks by providing built-in tools and configurations specifically designed for developing and deploying SAP applications.
![image](https://github.com/user-attachments/assets/2f6e9f48-01db-46a1-bab3-83fe123e894e)


##  Setup SAP BAS - SAP Business Application Studio

### Set Up SAP Business Application Studio for Development
- Prerequisites: have an SAP BTP Trial account
- Link SAP Guide: https://developers.sap.com/tutorials/appstudio-onboarding.html

  *Here is the link with an interface that is a bit old, but the steps are still the same.*
- NOTE: In step 6 maybe can't log in BAS because of role -> check 2 img below for solve this problem
  * ![image](https://github.com/user-attachments/assets/36b35e69-043d-4795-82b3-df3ba65fc729)
  * ![image](https://github.com/user-attachments/assets/149075b1-a540-42c7-ab19-c6f56a98ea8a)
### Create a Dev Space for SAP Fiori Apps
- Prerequisites: Done Set Up SAP Business Application Studio for Development
- Link SAP Guide: https://developers.sap.com/tutorials/appstudio-devspace-fiori-create.html

    *Here is the link with an interface that is a bit old, but the steps are still the same.*
- NOTE: In step 1, image 5, these are the tools provided by SAP as optional. Depending on the purpose, can choose the appropriate tools to use for the Dev Space. For learning purposes, it is recommended to select all the tools.

##  Setup Visual Studio Code
- Tomorrow release

##  Final
- Tomorrow release
