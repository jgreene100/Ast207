# Observational Astronomy Course Website

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](<https://jgreene100.github.io/Ast207/>)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jgreene100/Ast207/HEAD)

Course website: [https://jgreene100.github.io/Ast207/](https://jgreene100.github.io/Ast207/) (Password: `Ast207_Spring25`)

A course designed for Princeton majors and non-majors interested in understanding astronomical data. 

Maintained by Jenny Greene, Jared Siegel, Erin Flowers, and Jiaxuan Li. 


## Recommended Workflow for Students
To work on the Jupyter notebooks provided in this book and submit your completed work, please follow the steps below:

### 1. Open the Notebook in Google Colab
- Navigate to the desired notebook in this Jupyter Book.

- At the top of the notebook page, click on the rocket icon and then click the "Colab" button. This will launch the notebook in Google Colab, where you can interactively work on it. 

- Then Google Colab will ask you to authorize your GitHub account to access the notebook. Click on "Authorize" and follow the instructions to log in to your GitHub account. Then you will be able to open the notebook in Google Colab. The notebook is automatically saved to your Google Drive.

### 2. Save a Copy to Your Google Drive
- In Google Colab, go to the menu and select File → Save a Copy in Drive. This will create a personal copy of the notebook in your Google Drive, ensuring you can edit and save your work. We suggest you to make a folder for all the notebooks you will work on, and save your progress regularly.

- If you see a warning that "This notebook was not authored by Google," you can click on "Run Anyway" to proceed.

### 3. Work on the Notebook
- Complete the tasks, exercises, or questions in the notebook as instructed.

- Make sure all cells are executed, and your results are correctly displayed.

### 4. Download and Submit Your Work

- Once you’ve completed the notebook, download two versions of your work for submission:
    - IPYNB (Jupyter Notebook): Go to File → Download → Download .ipynb to get the notebook file.
    - PDF Version: Go to File → Print or File → Save as PDF to export your notebook as a PDF.

    Ensure all code cells, outputs, and any written explanations are visible in the PDF.

- Submit both the .ipynb file and the PDF file through Canvas.

> [!IMPORTANT]  
> Make sure your notebook runs **without errors** before submission. You can check this by opening the notebook in Google Colab and running all cells. If you encounter any errors, try to fix them before submitting your work.



<!-- ## How to build the book?
### Creating a Conda Environment
In order to compile this book, you will need to create a conda environment with the necessary dependencies.
The conda environment is provided as `environment.yml`. This environment is used for all testing by Github Actions and can be setup by:
1. `conda env create -f environment.yml`
2. `conda activate obsastro`

### Building the Jupyter Book
After `cd` into the `ObsAstGreene` folder, run the following command in your terminal:

```bash
jb build book/
```

If you would like to work with a clean build, you can empty the build folder by running:

```bash
jb clean book/
```

If Jupyter execution is cached, this command will not delete the cached folder. 

To remove the build folder (including `cached` executables), you can run:

```bash
jb clean --all book/
```

### Publishing this Jupyter Book

This repository is published automatically to `gh-pages` upon `push` to the `master` branch. -->


This repository is built based on [quantecon-mini-example](https://github.com/executablebooks/quantecon-mini-example) using [Jupyter book](https://jupyterbook.org/start/overview.html).