Installation
=============


Step 1: Install the Software
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
If you have OSX you can run a simple installer by downloading the following DMG then double click to install it as an application. 


`download the OpenEIT Installer for OSX <https://drive.google.com/file/d/1HyXHlD_yWJ59-XPO1OVrtmmT3S0sozim/view?usp=sharing>`_


If you are not running OSX or wish to tinker with the code, you will need to install the python modules by following the direction in the readme here: 
`<https://github.com/OpenEIT/OpenEIT>`_

You will need to use git to clone the above repository, then run::

    pip -r requirements.txt

To run the app go to the root directory and then type::

    python app.py 

This will start a server which can be viewed in any web browser, making it very cross-compatible with any operating system. 

Congratulations! You should see the software running and it will look like this. 

Step 2: Device Set Up
^^^^^^^^^^^^^^^^^^^^^^

Press the 'ON' button on your EIT device. Make sure that you've charged the battery first. You can also put some water in tank, just enough so that the electrodes are under water. 


Step 3: Gather Data and Experiment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
You should see the bluetooth device appear in the dropdown menu in the software and hit connect. If there is any problem, restart both the device and the software to refresh. 

Once you are connected you can do electical impedance image reconstructions. Just go to the reconstruction tab and then move an object around the tank. You should see the outline of the image being reconstructed. You can try different numbers of electrodes, baselining the image to change the scale, or any of the other sections. 


Congratulations! 
^^^^^^^^^^^^^^^^

You have done your first biomedical imaging experiment! This is the same method used in multi-million dollar CATSCANS, except without any harmful radiation, and can be used to see difference over time of any conductive body. Let's try some more tutorials next to get a few ideas of what you can do with it. 

As you go further you are welcome to edit the code, and improve upon what is already here. You can find issues listed in the github respository, or submit pull requests with your updates. We love hearing feedback about interesting experiments and applications people are investigating, so please feel free to email: jean@mindseyebiomedical.com