urbansim
========

New lightweight version of UrbanSim, a tool for forecasting future growth in real estate markets

Concept
-------

...

Installation
---------------

Download and install Anaconda Python distribution:

http://www.continuum.io/downloads

Get repository:

```
>> git clone https://github.com/fscottfoti/urbansim.git
```

Set environment variables:

```
>> cd urbansim
>> export PYTHONPATH=$PWD
>> export DATA_HOME=$PWD
```

Download data:

```
>> curl -k -o data/mrcog.zip https://dl.dropboxusercontent.com/u/2815546/mrcog.zip
>> unzip -d data data/mrcog.zip
```

Run:

```
>> cd example
>> ./run.sh
```