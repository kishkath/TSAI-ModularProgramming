# TSAI-ModularProgramming
The version of modular programming for all the work needed for ERA Program of 'The School of AI'


Here we go, the way the code looks isn't great, the way the code helps someone to understand the things is **great**. As we follow the modular programming in many github repo's/documentary notes, there is really a need to develop our scripts in the same way. Here I make the way, to help you(I know no one really looks at it, but ya a satisfactory) to understand & run the repo's of this series
                                                          **ERA (Re-Imagined AI)**
* Procedure: (For Exact implementation, refer the notebook alloted to that directory)
    1. Clone the repo
         !git clone https://github.com/kishkath/ERA.git
    2. Install what required.
         !pip install torch-summary
        
    3. Change to directory. As all assignments are made with repo-structure, we really can clone what we really need. So, lets move to required one.
         import os
        os.chdir( "/kaggle/working/ERA/7 - InDepth Coding Session/")
   4. Import required
          #### Custom
          from utility.dataset import loader # input batch-size & transforms if u create else proivde 'custom'
          from utility.run import Performance,scores
          from utility.visualize import Plots,plot_metrics  
          from models.model1 import NetArch,return_summary
          from utility.utils import allot_device
 
          #### required pre-defined libraries

      5. Setup the device
          ####Setting up the device 
          device = allot_device(42)
          print(f"{device} is available")
      6. Load data
      7. visualize data
      8. analyze data
      9. Model Architecture
      10. Check the summary of model
      11. Train the model
      12. Evaluate the model
      13. Plot the metrics & analyze them and figure the insights to improve performance/whatsoever.
      14. Save.
      15. Tata bye bye!
