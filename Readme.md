How to install:
===============

1. Move to the aeroolib folder and execute:

    sudo python setup.py install
	
	This library was obtained from:
	https://launchpad.net/aeroolib
	
2. Copy all the other folders to the openerp/addons/ folder of the server and install them as usual. Do not forget the report_aeroo folder, because gap_analysis_aeroo_report depends on it.  
  report_aeroo was obtained from: 
  https://code.launchpad.net/~kndati/aeroo/openerp7

3. These modules where modified to use "itps" as the name of the main gap_analysis module folder, instead of "gap_analysis".
