# JupyterNotebook-KaliLinux
![image](https://user-images.githubusercontent.com/120317751/213877070-366d6c2d-0d13-434b-948f-78ab3b846d79.png)


<b>Introduction:</b>
<br>
The Jupyter Notebook is a web-based interactive computing platform. The notebook combines live code, equations, narrative text, visualizations.
<br>

<b>Installation Guide:</b>
<br>

Step 1: Install pip with below command

     pip install notebook
     
Step 2: Install Jupyter Notebook with this command

     sudo apt-get install jupyter-notebook
     
<br>

<b>KernelSpec Issue Not Found (Fix --> 7th April 2023)</b>

Install virtualenv :

       sudo apt-get install virtualenv
       
<br>

Install pip3:

       sudo apt-get install python3-pip
       
<br>

Check that the Linux system is now running Python in (target folder)/bin/ and not the system Python:

        which python
        
 
OUTPUT :   /usr/bin/python 

<BR>

Set up the python3 virtualenv environment:

        virtualenv -p python3 /usr/bin/python
        
<BR>

Check that pip3 is installed:

         which pip3
         

OUTPUT: /usr/bin/pip3

<br>

Install a package, and check that it is installed in (target folder)/lib:

         pip3 install requests
         
<br>

<b> Switch between Python versions </b>


If a server already has Python 3 but a given task or program requires Python 2, use this command:

        virtualenv --python=/usr/bin/python /usr/bin/pip3 

Example : (target directory) ---> /usr/bin/pip3

<br>

Check Below command:

          python 
          
Fixed:

![Screenshot from 2023-04-07 10-28-07](https://user-images.githubusercontent.com/120317751/230544025-10a8963d-9c7a-4760-9482-504c23226f0a.png)


     

