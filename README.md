===============================================
python-cordova
===============================================

This is a very simple Python library to interface with the Cordova (Phonegap) command line tool.


Key concepts
===============================================
- Interact with the Cordova CLI directly from Python
- Enables building and archiving PhoneGap applications from your Python code


Installation in virtualenv 
===============================================
capy cordova folder to your python site-packages folder


Usage
===============================================

.. code-block:: python
   import cordova

   application = cordova.App(
       'You Application Name',
       'You Application path'  # Ex: /Users/<user>/Desktop/cordova/myapp
   )

   application.build('android') # or any installed platform
   application.archive('ios') # or any installed platform
   
   
   
