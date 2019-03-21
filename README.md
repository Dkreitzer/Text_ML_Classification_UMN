# Machine-Learning Text Classification Notebook (MLTCN)
<p align="center">
<img src="Sandbox/img/classification_process.png" width="500" height="190" title="screenshot">
</p>

The MLTCN was created to enable users with little to no programming expertise to classify text documents using unsupervised machine learning.

<p align="left">
<img src="Sandbox/img/colab_favicon_256px.png" width="75" height="75" title="screenshot">
</p>

One of the first challenges we wanted to overcome was accessibility – how could we make this easy for our target audience to use the code? We started exploring online notebook options and chose to utilize <a href="https://colab.research.google.com">Google Colab</a>.

Colab Benefits:
- Anyone with a google account can open an ipynb file from GitHub or their Google Drive in seconds – without having to load any software on their computer.
- Some of the libraries we utilize can be temperamental (they don’t always comingle well with other libraries) – but with Colab the user doesn’t have to download, configure, or trouble shoot any library settings.
- Files can be saved directly to Google Drive and GitHub accounts, making it incredibly easy to share notebooks and outputs.<br>
Currently the notebook is configured specifically for Colab, but it can be downloaded and run on local notebooks (i.e. Jupyter Notebook).
<br>

### How to use MLTCN Colab:

#### Setup:
1.	Fork the MLTCN repo into your own Github Account or save the repo in your Google Drive.
2.	Open Doc_Classification_colab.ipynb in colab’s environment.
  - Github: click the link and it will open automatically.
  <p align="center">
<img src="Sandbox/img/open_colab_github.png" width="300" height="136" title="screenshot">
</p>

  - Google Drive: Open the file and select 'open with colabratory' button.
  
<p align="center">
<img src="Sandbox/img/open_colab_googleDrive.png" width="300" height="136" title="screenshot">
</p>

3. Modify path to cloan Github Repo
<p align="center">
<img src="Sandbox/img/custom_Ghub_Repo.png" width="400" height="75" title="screenshot">
</p>

#### File Structure

Important: The file structure below needs to remain the same for the program to automatically pull and save files properly. Do not delete, move, or rename any of the following folders unless you are changing the file path within the cells:

root/ <br>
root/Model<br>
root/Model/Model1<br>
root/Train<br>
root/Analyze<br>
root/Predicting<br>
root/History<br>
<br>

<p align="center">
<img src="Sandbox/img/Text_Files_to_History.png" width="400" height="311" title="screenshot">
</p>

<br>

### Processes
The notebook has been configured so you can:
1. Add text files to train a model
2. Predict text files and generate visuals
3. Load CSV file (previously predicted data) to generate visuals

#### Train a new model:
1. Add text files to the Train folder (root/Train)
2. Verify or adjust Grid Search settings

<p align="center">
<img src="Sandbox/img/Grid_search_settings.png" width="400" height="100" title="screenshot">
</p>
3. Verify or adjust Model Parameters

<p align="center">
<img src="Sandbox/img/Model_Parameters.png" width="400" height="100" title="screenshot">
</p>
4. Select where to save the new model

<p align="center">
<img src="Sandbox/img/save_model.png" width="325" height="145" title="screenshot">
</p>

5. Execute Cells:
    - 1 - 1.4 (Imports & Installs)
    - 2 - 2.2 (Download Files)
    - 3 - 3.6 (Vectorization)
    - 4 - 4.6 (Model Training)

#### Analyze Text Files:
1. Add text files to the Analyze folder (root/Analyze)
2. Select which model you want to use (from models you have saved either locally or in your GitHub repo)
3. Choose where to save master.csv results
4. Execute Cells:
    - 1 - 1.4 (Imports & Installs)
    - 2 - 2.2 (Download Files)
    - 3 - 3.6 (Vectorization)
    - 5 - 5.4 (Load Model)
    - 6 - 6.3 (Predictions)
    - 7 - 7.3 (Predict Text Files)

#### Visualizations







