## Setting Up the Virtual Environment

To set up the virtual environment for this project, follow the steps below:

1. **Navigate to the Project Directory**  
   Ensure you are in the root directory of the project (where the `gpt` folder is located).

2. **Create a Virtual Environment**  
   Run one of the following commands to create a virtual environment named `cuda` in the project directory:

   - **If Python 3.11 is Installed**:  
     ```bash
     python -m venv cuda
     ```
   - **If Python 3.12 or Later is Installed**:  
     Download Python 3.11, set it as the default path, and run:  
     ```bash
     python3.11 -m venv cuda
     ```

3. **Verify the Virtual Environment**  
   Confirm that the `cuda` directory has been created and contains the necessary files, including the `Scripts` folder.

4. **Activate the Virtual Environment**  
   To activate the virtual environment, run:  
   ```bash
   cuda\Scripts\activate


5. **Open Notebook**
   To open notebook, in the current directory on Anaconda prompt, run:
   ```bash
   jupyter notebook