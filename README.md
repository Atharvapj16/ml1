# This my first  

# It will make project structure which can be used for any project
``` python template.py```

# It will create env and install our all requirements.txt
``` bash init_setup.sh```

# It will activate env
``` source activate ./env```

```pip list ```



# In order to link our custom package(local package) in our created environment ./env we can used various method

# <A> By installing setup.py directly

``` python setup.py install```

# <B> Another way is u can mention (-e .) in ur requirements.txt and then installing requirements.txt
``` pip install requirements.txt```