All files must be opened through Jupyter Lab, look up a tutorial on how to set that up, like here: https://www.youtube.com/watch?v=ClTWPoDHY_s

Also requires a few packages, such as pandas, and most notably: pyspedas

Can be installed through "pip install pyspedas" or to update "pip install --upgrade & pip install pyspedas --upgrade" (may need to change syntax based on system)

Should be compatible with all systems including Windows, Mac, & Linux

Fair warning if data time range is large, PC may take several hours to load data. Once the .npz file is created, the remaining processing and plotting files are a lot faster

There are two processing files: one with and one without multiprocessing. This may be limited to the type of CPU or system you are running on, both do the same analysis, one is just much faster
