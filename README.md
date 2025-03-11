# Simulation of Perovskite Solar Cells using SCAPS-1D

### Tandem Cells

SCAPS doesn't natively support the direct simulation of multi-junction (tandem) cells.  
But SCAPS allows scripts to split the tandem structure into sub-cells (top and bottom cells).  
The partial cells are connected in series electrically.  

**Tandem Instructions:**
* Define the top and bottom cells (.def files) individually.
* Save the .def files in the native `.def` folder.
* Navigate to the `Script set-up` in the action panel.
* Paste the script from `SCAPS Tandem Script.txt` with your defined top and bottom cell names.
* Click `OK` in the script editor panel.
* Click `Execute script` present besides `Script set-up`.
* Export the data to an excel file or visualize the graphs within the program.

**Note:**  
These instructions are made in accordance with SCAPS 3.3.11 or 3.3.12.  
Please check the latest user manual: https://scaps.elis.ugent.be/SCAPS%20manual%20most%20recent.pdf  
SCAPS Website: https://scaps.elis.ugent.be/