jeizinen-template
=================

a starting template to use jeizinen-meteor UI prototyper

To get started

1. Install meteor.js
2. Install meteorite
3. run these commands in your terminal

        # create meteor app
        meteor create myapp 
        cd myapp
        
        # get rid of standard meteor starting files
        rm myapp.html myapp.css myapp.js
        
        # get zip
        curl -L  https://github.com/RolandStuder/jeizinen-template/archive/master.zip -o temp.zip
        unzip temp.zip  && mv jeizinen-template-master/* . && rm -rf temp.zip jeizinen-template-master
