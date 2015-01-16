### Files & Folders

- the testing stack resides in ./testing and includes everything to run PHPUnit tests (PHPUnit and all what's needed)
- in addition to PHPUnit, there is VisualPHPUnit for pretty prints in the browser and uses an folder ../tests which 
contains usually all test units


### Usage

1. Create test units in ../tests inside compelling folder names as 'Rpc' ...
2. Open in the browser /testing/VisualPHPUnit/ and select the folders and/or individual test units and click run, 
thats it

### Configuration 

1. VisualPHPUnit/app/config/bootstrap creates a 'default' configuration for VisualPHPUnit. It will try to override
this default configuration from VisualPHPUnit/app/config/custom.php (custom.php should not be in the VCS!). 
This configuration sets the location to the test units path. You may set your own minimal bootstrap in there is well.


