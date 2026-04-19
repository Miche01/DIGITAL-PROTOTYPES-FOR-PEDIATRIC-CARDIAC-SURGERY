# DIGITAL PROTOTYPES FOR PEDIATRIC CARDIAC SURGERY 🫀
Human Modelling in Engineering | Politecnico di Milano Academic Year: 2023-2024

<br>

<table border="0">
 <tr>
    <td><img src="DIGITAL-PROTOTYPES-FOR-PEDATRIC-CARDIAC-SURGERY/Images/DORV+miocardio+hollow dietro.jpg"></td>
    <td><img src="percorso/della/tua/foto2.jpg" width="100%" alt="Heart Model 2"></td>
 </tr>
</table>

<br>
## 📌 **Project Overview**

Pediatric cardiac surgeries are exceptionally challenging due to the small size of the organs and the complexity of congenital heart diseases (CHD). This project focuses on designing two digital 3D prototypes of pediatric hearts with specific malformations to be used in Hands-on Surgical Training (HOST). By creating patient-specific models from CT scans, surgeons can practice procedures on replicas that closely resemble the actual anatomy of the child.

🏥 **Clinical Context**

The project replicates two major pathologies:
* Transposition of the Great Arteries (TGA): A condition where the aorta is connected to the right ventricle and the pulmonary artery to the left ventricle.
* Double Outlet Right Ventricle (DORV): A rare defect where both the aorta and the pulmonary artery arise abnormally from the right ventricle.

🎯 **Aim** 

Design a complete heart simulator made of the models of two pediatric pathological hearts put in an environment that replicates the rib cage. This ensemble is thought to be used for surgical simulation allowing surgeons to practice the surgical procedures for TGA and DORV pathologies.

## 🛠️ **Technical Workflow**

The development process utilized advanced medical imaging and 3D modeling software:
1. Segmentation & Modeling
   * Software: Mimics Innovation Suite (Materialise).
   * Process: CT scans acquired in London were used to isolate cardiac chambers and great vessels.
   * Anatomy: Models include the myocardium, segmented using specific Hounsfield Unit (HU) thresholds (e.g., 65 HU - 3071 HU).
3. Post-Processing
   * Software: 3-Matic.
   * Refinement: Applied Adaptive Mesh (0.1 mm edge length), Wrap (3 mm gap closing), and Smooth functions to enhance surface quality.
   * Finalization: The hearts were hollowed to a total wall thickness of 0.7 mm and vessels were trimmed to allow for surgical access simulation.
4. Modular Simulator Design
   * Components: A simulated rib cage (with a sternal gap for surgical access) and a support platform.
   * Connectors: Designed from scratch in Solidworks 2023 to fit the specific vessel openings (Superior Vena Cava and Pulmonary Arteries) of each pathological model.
   
## 📊 Results

The project successfully produced two complete digital simulators:
- TGA Simulator: Features a hollowed heart model with corrected myocardium and specific mounting connectors.
- DORV Simulator: Includes the complex ventricular anatomy and a modular attachment system for the rib cage environment.

🚀 **Future Developments**

- Incorporation of internal structures such as cardiac valves and chordae tendineae.
- Testing of biocompatible materials (e.g., silicone molding) to better mimic the mechanical properties of real tissue.
- Integration with Augmented Reality (AR) for immersive surgical simulations.


 ## 💻 Software
* **Mimics Innovation Suite**
* **3-Matic**
* **Solidworks**

## 👥**Authors**
**Miuccio Michela Paola Benedetta**  
**Rizzo Chiara**  
Institution: Politecnico di Milano - School of Industrial and Information Engineering 
