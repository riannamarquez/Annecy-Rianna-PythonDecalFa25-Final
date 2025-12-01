We’ll analyze the data from a black hole merger, GW231123. Our data is downloaded from the O4a network on the Gravitational Wave Open Science Center (GWOSC) website. 

We first had to use the requests python package to download the file with web requests. We fetched the data within a specific GPS time. We then download the url, thus downloading the HDF5 file at the starting GPS time of the merger. 

After downloading the file, we have to use several python packages to read the file. Specifically, we downloaded numpy, matplotlib, matplotlib.pyplot, and h5py. After storing the fieldname and data as a variable, we can start exploring the data. We first store the strain data and look at the metadata in order to make a time vector. We plot the data as a time series. It’s hard to discern any details so we zoom in on a specific time series to look at a few seconds of data. 10,000 samples is about 2.4 seconds.

**Note that our code is labeled "GW Data NEW (Final PDF)" as a PDF in the Jupyter folder of this repository**
