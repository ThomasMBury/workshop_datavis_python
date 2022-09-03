# Workshop: Interactive data visualisation in Python :snake:

## Instructor
Dr. Thomas Bury <br>
Postdoctoral fellow <br>
Department of Physiology, McGill University <br>
Contact: thomas.bury@mcgill.ca

## Summary				
Modern scientific methods give rise to vast quantities of data. Creating effective visualisations is essential for both presentation and exploration of the data. This is no easy task when the data contains dozens of variables and millions of entries. Traditional visualisations are static, that is, what the user sees is what the user gets. Interactive visualisations allow the user to perform tasks such as varying parameters, honing in subsections of the data, and switching between different plot types, all without touching the code! This faciliates rapid exploration of the data. Moreover, these visulisations can be easily shared with collaborators who only require a web browser to open the visualisation.	

This workshop will equip participants with the skills required to begin creating interactive visualisations in Python, using the [Plotly](https://plotly.com/python/) library. The format will be interactive, with alternation between demonstrations by the instructor and participants working through their own Jupyter notebook (provided in advance). Participants will come away having made several of their own visualisations of either a large public dataset, or their own dataset if they would like to bring one. Check out this [interactive visualisation](https://ecg-dashboard-medium.herokuapp.com/) of ECG data from Physionet for an example of what can be achieved with these tools.

## Objectives		
We will cover the following:
- Organisation of *pandas* DataFrames to facilitate rapid plotting.
- Creating basic interactive plots in *Plotly* (Bar, Line, Scatter, Histogram).
- Visualisation of multiple dimensions using multiple traces, grid plots and 3-dimensional graphs.
- Integration of sliders and drop-down boxes.
- (If time allows.) Combining interactive plots into a dashboard.

## Setup instructions

1. Install the Anaconda distribution available [here](https://www.anaconda.com/products/distribution). This comes with Python 3, JupyterLab and the Python packages *numpy* and *pandas*, which we will require for the workshop.

2. Install Python packages for *plotly* and *dash* by entering the following commands into your Terminal (Mac) or Command Prompt (PC):

   ```bash
   conda install plotly
   conda install dash
   conda install -c conda-forge -c plotly jupyter-dash

3. Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) if not already on your computer.

4. Make a [Github](https://github.com/) account if you don't already have one.

5. Go to the workshop [repository](https://github.com/ThomasMBury/workshop_datavis_python), and create a *fork* (button on top right). This creates your own version of the repository, in which you can make edits and complete the workshop notebooks.

6. *Clone* your repository to your computer. To do this, click the green button that says 'Code', and copy the link that appears in the box. Then go to your Terminal (or Command Prompt), navigate to a folder where you would like to store the repository and enter

   ```
   git clone paste-your-link-here
   ```
   where you paste your link as indicated. You should now see the directory *workshop_datavis_python* saved on your computer.

7. Open the Anaconda Navigator and launch JupyterLab. Navigate to where you saved the workshop repository and open *test.ipynb*. Check that you can run this notebook without any errors.

If you run into issues, please contact me at thomas.bury@mcgil.ca and I'll glady help out.



