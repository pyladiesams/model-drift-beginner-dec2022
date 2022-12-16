
# An introduction to model drift
### Level: Beginner
### Presentation: [Model Drift workshop presentation](workshop/model_drift_workshop.pdf)

## Workshop description
During this workshop you will learn how to:
* measure your model performance
* handle model drift
* perform test-based model monitoring

All this with the help of [evidently](https://github.com/evidentlyai/evidently)

## Requirements
* Python 3.6 or higher
* VS Code

Note: the workshop has been tested with Jupyter notebooks running in the browser and VS Code. The widgets **will not** display correctly if opened in PyCharm.

## Usage
* Clone the repository and navigate to its root
* Install the required libraries with pip: ```$ pip install -r requirements.txt```
*  Run ```$ jupyter nbextension install --sys-prefix --symlink --overwrite --py evidently``` (installs the Evidently 
nbextension)
* Run ```$ jupyter nbextension enable evidently --py --sys-prefix``` (activates it)

 Note: if you use Jupyter Lab, the reports might not display in the notebook. However, you can still save them as HTML files.
* Open VS Code settings, choose Workspace tab, update ```Jupyter: Notebook File Root``` with ```${workspaceFolder}```. If this step is skipped, workshop and solution notebooks will run from their folder instead of the root one. Additionaly you will not be able to save reports without ugly hacks.

Note for Windows users:

Unfortunately, building reports inside a Jupyter notebook is not yet possible for Windows. The reason is Windows requires administrator privileges to create symlink. In later versions Evidently will address this issue. You can still generate the HTML to view externally.

## Video record
Re-watch YouTube stream [here](https://youtu.be/gyvB44gQWQE)

## Credits
This workshop was set up by @pyladiesams and @EzheZhezhe
