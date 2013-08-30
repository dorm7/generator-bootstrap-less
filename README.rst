
================================
Generator Django Bootstrap Less 
================================




A Generator for Yeoman to work with the Less version of Bootstrap and move data to sibling static folder

Install
-------
   
   .. code-block:: bash
   
    sudo npm i  -g git+https://github.com/dorm7/generator-django-bootstrap-less
    mkdir yourapp/f2e
    yo django-bootstrap-less

Usage
-----

   * grunt server   # do launch dev server
   * grunt build    #will move data to ../static/build
   * grunt django   #will compress less files to django static folder



TODO
----

   live-reload is not work while using grunt django
