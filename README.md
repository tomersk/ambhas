# ambhas
Ambhas python library

## Installing ambhas

Installing ambhas can be done by downloading source file (ambhas--<version>.tar.gz), and after unpacking issuing the command::

    python setup.py install

This requires the usual Distutils options available.

Or, download the ambhas--<version>.tar.gz file and issue the command::
    
   pip install /path/to/ambhas--<version>.tar.gz

Or, directly using the pip::

   pip install ambhas   
   

## Usage

Import required modules::

    import numpy as np
    from ambhas.errlib import rmse, correlation

Generate some random numbers::

    x = np.random.normal(size=100)
    y = np.random.normal(size=100)
    rmse(x,y)
    correlation(x,y)

# Author

Sat Kumar Tomer
satkumartomer at gmail dot com

## Changes

0.1.0 
* Initial version

0.1.1
* Minor corrections in setup.py files

0.2.0
* few packages added

0.3.0
* groundwater, sun_rise_set, soil texture module, etc. added

0.3.1
* manifest.in file edited

0.3.2
* extract_gis_data, richards, risat added

0.4.0 
* extract_gis_data, richards, risat added

1.0.0 
* Updated for Python3
* Removed copula from this and is available now only as a seperate library

# Any questions/comments

If you have any comment/suggestion/question, 
please feel free to write me at satkumartomer@gmail.com

You may go through https://github.com/tomersk/learn-python to see the examples.
