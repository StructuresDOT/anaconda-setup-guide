# anaconda-setup-guide
Anaconda installation and setup guides for consultants working with DOT


1. Go to the following website: https://www.anaconda.com/

<br />
<br />

2. Click on “Get Additional Installers”:

![Installer download page](./imgs/Picture1.png)

<br />
<br />

3. Download the current version for windows (Python 3.10 64-Bit Graphical Installer):

![Anaconda installer page](./imgs/Picture2.png)

<br />
<br />

4.	Run the installation file and click “Next”:

![Setup welcome](./imgs/Picture3.png)

<br />
<br />

5.	Click “Agree” in the license agreement window:

![License agreement](./imgs/Picture4.png)

<br />
<br />

6.	In the Installation Type section choose the recommended settings and click next:

![Installation type](./imgs/Picture5.png)

<br />
<br />

7.	The default path is recommended, after specifying the installation path click Next:

![Install location](./imgs/Picture6.png)

<br />
<br />

8.	In the Advanced Installation Options accept the defaults and click install:

![Installation Options](./imgs/Picture7.png)

<br />
<br />

9.	Continue the next steps and finish the setup:

![Finish setup 1](./imgs/Picture8.png)

<br />
<br />

![Finish setup 2](./imgs/Picture9.png)

<br />
<br />

10.	In the windows search bar, search for “anaconda prompt” and launch the program.

![Anaconda prompt](./imgs/Picture10.png)

<br />
<br />

11.	In the prompt window type the following command to create a new anaconda environment (know more about anaconda environments and how to manage them here: https://conda.io/projects/conda/en/latest/user-guide/concepts/environments.html , https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment):
* ~ conda create --name FDOTCalcs --clone base.

![Clone base](./imgs/Picture11.png)

<br />
<br />

12.	After the cloning process was complete, switch to the newly created environment (FDOTCalcs) using the following command:	
* ~ conda activate FDOTCalcs

![Activate FDOTCalcs](./imgs/Picture12.png)

<br />
<br />

13.	Assuming the default installation path for Anaconda was accepted (step #7), place the “requirements.txt” file in the “C:\Users\Username” path, where Username is the username under which the Anaconda software was installed.

<br />
<br />

14.	Run the following command to install the required packages for FDOT calculation sheets in this newly created environment from the “requirements.txt” file:
* ~ pip install -r requirements.txt
<br />
<br />
![Pip install](./imgs/Picture13.png)

<br />
<br />

15.	After installation is successful, launch Jupyter lab program by typing the following command, make your browser Google Chrome as the default program when launching Jupyter Lab for the first time:
* ~ jupyter lab
<br />
<br />
![Jupyter lab](./imgs/Picture14.png) 
<br />
<br />
![Set chrome default browser](./imgs/Picture15.png)