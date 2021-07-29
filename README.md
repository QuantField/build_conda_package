# build_conda_package

* This build the orlssvm package, make sure that the orlssvm where all the main code is, is created within the repo. (I just changed it ).
* This is a very basic packaging for a local use.
copy the two files into a folder then run conda-build the_newly_created_folder, or cd into it and run conda-build . 
* if successful the tar.bz2 will be in the folder indicated in the message. 
To install the package locally:

conda install --use-local orlssvm

* it was installed successfully but there was error in some imports needs fixing paths.
