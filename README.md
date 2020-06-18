# Getting started
Please find below some minimal knowledge to use the Colab jupyter notebook efficiently.

Notebooks contain cells. These cells can be of two type:
- 'Text' cells that contain information to guide users.
- 'Code' cells that can be run.

__Importantly, please always run code cells one by one from the top to the bottom of the page as every cell depends on the output of its previous cells. So please do not skip any code cell unless it is specifically indicated that you can.__ Skipping text cells is ok, but keep in mind that those cells are there for guidance.

## How to upload files to Google drive
- To access Google drive from a browser click [here](https://drive.google.com/) and enter your credentials (you may have to switch id, provided you use several accounts, by clicking on the letter within a colored circle top right of the page).

- Once loaded just drag and drop files/folders from your browser to the Google drive web interface (and wait for the upload to complete, this may take time...). Files stored in Google drive can easily be accessed from Colab (see below).

## How to mount Google drive in Colab
Data stored on google drive can easily be accessed from within Colab to be used for training neural networks and saving trained model and/or using neural network to segment images. To use drive you need a google account. I personnally recommend creating [create a second account](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp) dedicated to deep learning to avoid issues.

- Click on the files icon on the left of the Colab window.

![](https://github.com/baigouy/notebooks/raw/master/images/demo_mounting_drive0000.jpg)
- Wait some time and a Google drive icon should appear. Do click it.

![](https://github.com/baigouy/notebooks/raw/master/images/demo_mounting_drive0002.jpg)
- Press 'Connect to google drive'.

![](https://github.com/baigouy/notebooks/raw/master/images/demo_mounting_drive0003.jpg)
- The Google 'drive' folder is now visible. Browse it until you see a 'My Drive' folder (this is the root of the Google drive folder).

![](https://github.com/baigouy/notebooks/raw/master/images/demo_mounting_drive0004.jpg)
![](https://github.com/baigouy/notebooks/raw/master/images/demo_mounting_drive0007.jpg)

## How to run a 'code' cell
- Select the cell (by clicking on it).
- Press the play button (or brackets) located top left corner of the selected code cell to run it.

![](https://github.com/baigouy/notebooks/raw/master/images/running_a_cell20002.jpg)
![](https://github.com/baigouy/notebooks/raw/master/images/running_a_cell20000.jpg)
- Successful execution outputs a result (failed execution raises an error that is useful to debug).

![](https://github.com/baigouy/notebooks/raw/master/images/running_a_cell20001.jpg)

## Select a GPU runtime
Deep learning is computation intensive and is better achieved using GPU (graphic cards) than regular computer processors. To get a Colab virtual machine that uses a GPU:
- Press the 'Runtime' menu entry.

![](https://github.com/baigouy/notebooks/raw/master/images/setting_GPU_running_a_cell0004.jpg)
- Choose 'Change runtime type'.

![](https://github.com/baigouy/notebooks/raw/master/images/setting_GPU_running_a_cell0001.jpg)
- Select 'GPU'.

![](https://github.com/baigouy/notebooks/raw/master/images/setting_GPU_running_a_cell0005.jpg)
- Press 'Save' (the virtual machine will connect to a GPU empowered system).
 
![](https://github.com/baigouy/notebooks/raw/master/images/setting_GPU_running_a_cell0003.jpg)

## Colab tips

### Advantages:
- Colab is free.
- Colab gives free access to GPU (graphic cards) and even TPU.
- Colab can access Google drive (Google drive is the most efficient way to transfer data to Colab; the Colab upload tool being extremely slow).
- Colab offers free (temporary) storage on its virtual machines.

### Limitations
- Colab session cannot run longer than 12 hours. After 12 hours everything saved on your Google drive is still yours, the virtual machine is reset and data that was not saved on your personal drive is lost...
- You shouldn't run several Colab notebooks in parallel (you can get banned if you do so), keep in mind it's a free service.
- __You are limited by the size of your Google drive (trained models can use a lot of space and may easily fill you Google drive, making your mails non accessible, so the best is to [create a second account](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp) dedicated to deep learning).__
- Access to GPU or TPU is not guaranteed in the free version (if no GPU is available best is to quit and come back later).
- Colab will also disconnect the session if left idle for too long (even if a neural network is running and the 12h limit is not reached) this is why it is highly recommended to regularly press on the ![](https://github.com/baigouy/notebooks/raw/master/images/ram_disk_ico.jpg) icon during training (smart people may run a script in their browsers or use 3rd party software to automate that, but if you choose to do so you are doing this at your own risk).

__PS: using Colab pro (commercial version) alleviates time limitation and idle disconnect timeout__

## training a model

### link to a github or Colab page

## using a pretrained model for segmenting epithelia

### link to a github or Colab page




 

