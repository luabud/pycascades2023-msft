# Revolutiozine your data processing workflow with Data Wrangler! 

Data Wrangler offers an interactive UI that writes the data processing code for you using the [Pandas](https://pypi.org/project/pandas/) package.

## Set up 
- Download [VS Code Insiders](https://code.visualstudio.com/insiders/)
- Install the [Data Wrangler extension](TBD)
- Install the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- Open the `titanic` folder in VS Code (**File** > **Open Folder...**)
- Create a new conda environment by running the **Python: Create Enviroment** command under the Command Palette (`Ctrl+Shift+P`/`Cmd+Shift+P`)
   - Select `venv` and then the latest Python version available on your machine 
- Follow the steps in the Data Wrangler walkthrough 
   - If it doesn't automatically show up on install, run the **Data Wrangler: Open Walkthrough** command 
- Open the `Titanic.csv` file in the Data Wrangler, either from the walkthrough, or from the **Data Wrangler: Open File** command
- Open the Data Wrangler view by clicking the icon on the activity bar. 
- You're all set up!  

## Exploration
- Play around with the UI to process your data:
    - To remove a column, right-click on the column heading and delete it
    - To remove rows with missing values or substitute them with a computed default value, click on the desired column and select **Fill missing values** under the **Find and replace** section on the Data Wrangler view in the side panel.
    - To reformat a categorical column by one-hot encoding it to make it suitable for machine learning algorithms, click on the column and select **One-hot encode** under the **Formulas** section on the Data Wrangler view in the side panel.
    - To create a new derived column from existing columns, click on **New column by example** on the Data Wrangler view.
      - Select a target column and give a name to your new column. 
      - Enter an example of how you want the data in the derived column to look like in the Data Wrangler editor. 
      - See the values being magically fileld in based on your example. 
      - If you find an error in the results, you can correct it with a new example, and Data Wrangler will try to produce a better result. You can also modify the generated code yourself.
    
Data Wrangler will generate the Python code to do all the operations you perform through the UI. To see get the code for each step, expand the **Cleaning Steps** tab on the Data Wranger view and preview the code for each step, or for all of them. 

# Power up your data exploration and visualization workflow with GitHub Copilot! 
## Set up 
- Get started with a free trial of the [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) extension.
- Install the [Jupyter notebooks extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).
-  Create a new Jupyter notebook with **File** > **New File...**, and select Jupyter Notebook
-  Select the kernel by clicking on the **Select Kernel** button on the top right of your notebook. Select the same virtual environment you created for trying out Data Wrangler.
- Save the notebook (`Ctrl+S` or `Cmd+S`)  
## Exploration
-  Explore Copilot functionality by typing comments and seeing the suggested code. For example, you can start with `# read the Titanic-Dataset.csv` and see what Copilot suggests!
-  Then try something like `# create a plot with the distribution of survivors by age`
-  Play around with more visualizations you'd like to create!
