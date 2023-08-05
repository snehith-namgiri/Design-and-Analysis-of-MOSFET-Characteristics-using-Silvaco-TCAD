# Design and Analysis of MOSFET Characteristics using Silvaco TCAD
- In this project, I have developed a MOSFET in TCAD Silvaco and analyzed various parameters of the MOSFET. I have analyzed its drain current which is based on the doping concentrations of all the electrodes.
- I have divided the whole MOSFET into three regions which are defined with the materials like Silicon, Silicon Oxide and Air respectively. 
- The doping concentrations for source and drain electrodes is 1e16 and for gate  the concentration is 1e18.
- The threshold voltage obtained for this device is 0.919294408281977 V.
<img width="989" alt="image" src="https://user-images.githubusercontent.com/99958597/233799456-52ba2809-bc9e-4285-b132-e01efc9ad723.png">

![image](https://user-images.githubusercontent.com/99958597/233800764-3c6c22cb-e12d-407f-b0a6-e2fbaa159631.png)


# Design Flow
**1. Structure Specifications:**
- In this step, we need to define the Mesh, Regions of the device, Electrodes, and the doping type and concentration of the device. 

**2. Material Model Specification:**
- This is the second step of the design flow, where we need to define the materials that we want to use for the making the device like in my case I have used three materials namely Silicon, Silicon Oxide and Air. Then we need to specifiy the models that we have to use, then contact and interfaces. 

**3. Numerial Method Selection:**
- This is the most important step in the whole design process, where we need to define the mathematical models that we want to use for the solving the mathematical equations. 

**4. Solution Specifications:**
- This is the pre final step of the design flow, here we will specify the result specifications like reference gate voltage, step size for the drain current graph and few other parameters. We also use the SAVE statements in the code to save the output files. 

**5. Result Analysis:**
- This is the last step of the design flow in Silvaco, here we will extract all the output files of the project through a sub tool called TonyPlot. 

# Results and Analysis: 

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/99958597/233800377-df2e10a4-b689-43a0-8782-cd93f3c4e775.png">

- The above image represents the meshing of the device. 

<img width="986" alt="image" src="https://user-images.githubusercontent.com/99958597/233800446-c07e9fed-c861-408c-8adb-35de9f3156f2.png">

- This image shows the electrodes placement. 

<img width="960" alt="image" src="https://user-images.githubusercontent.com/99958597/233800467-5877aeb4-e1dd-407b-be30-3e85651c9e12.png">

- The above image shows the graph of the Net doping concentraions of the device. 

<img width="1010" alt="Untitled" src="https://user-images.githubusercontent.com/99958597/233800701-99fb9035-d19a-41b4-9c19-4323d2d5aba5.png">

- This is the final result that was obtained. This is graph which is extracted from the tonyplot represents the Drain Current graph. This graph also gives a detailed picture of subthreshold region and threshold voltage. 


# Tools Used: 
- TCAD Silvaco
