# GridFree: A pixel-level label tools to segment high-throughput images
#### Article link: https://academic.oup.com/plphys/advance-article/doi/10.1093/plphys/kiab226/6274909
Bibtex @article{10.1093/plphys/kiab226,
    author = {Hu, Yang and Zhang, Zhiwu},
    title = "{GridFree: A Python Package of Image Analysis for Interactive Grain Counting and Measuring}",
    journal = {Plant Physiology},
    year = {2021},
    month = {05},
    issn = {0032-0889},
    doi = {10.1093/plphys/kiab226},
    url = {https://doi.org/10.1093/plphys/kiab226},
    note = {kiab226},
    eprint = {https://academic.oup.com/plphys/advance-article-pdf/doi/10.1093/plphys/kiab226/37929045/kiab226.pdf},
}

## Implement Python version 3.6.5(Windows 10 64bit version is available, check the download link below)
* install Python 3.6.5, download link: https://www.python.org/downloads/release/python-365/
<!--![screenshot](https://raw.githubusercontent.com/12HuYang/FreeCADITS/master/Training_intro.png)-->
<!--![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/compare.png)
![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/normaldistribution.png)-->
<!--#### RUN ```pip3 install plantlabeller``` to install from terminal, if you cannot run ```pip3```, use ```python3 -m pip install plantlabeller```.
#### Linux user may need to use ```sudo pip3 install plantlabeller``` or ```sudo python3 -m pip install plantlabeller```.-->
#### MacOS
##### install
* execute ```python3.6 -m pip install -r requirements.txt``` to install required packages
<!--* execute ```brew install gdal``` to install required packages
* execute ```python3 -m pip install rasterio``` to install required packages-->
##### run the software
* execute ```./run``` on a terminal to run the software
#### Linux OS
#####  install
* execute ```python3.6 -m pip install -r requirements.txt``` to install required packages
<!--* execute ```sudo add-apt-repository ppa:ubuntugis/ppa```
* execute ```sudo apt-get update```
* execute ```sudo apt-get install python-numpy gdal-bin libgdal-dev```
* execute ```python3 -m pip install rasterio``` -->
##### run the software
* execute ```./run``` on a terminal to run the software
#### Windows OS 

##### Windows 10 64bit (Download and run ```tkinterGUI_nw.exe``` in dist folder)
* Download link: https://www.dropbox.com/s/nf6vsu1q5meb1ho/GridFree_winOS.zip?dl=0

##### install (if Windows 10 64bit doesn't work for you)
* run ```cmd``` go to the path you downloaded GridFree, you can execute ```cd``` space ```your download path```
* execute ```python -m pip install -r requirements.txt``` to install required packages
* execute ```python -m pip install opencv-python``` for opencv package
* execute ```python -m pip install scikit-image``` for package installation
* execute ```python -m pip install sklearn``` for package installation
* ![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/win-smallw-startdemo.gif)
* YouTube: https://youtu.be/fSgH1-35Hyw
<!--* Windows 32bit OS execute ```py -m pip install rasterio‑1.0.24+gdal24‑cp36‑cp36m‑win32.whl```
* Windows 64 bit OS execute ```py -m pip install rasterio‑1.0.24+gdal24‑cp36‑cp36m‑win_amd64.whl```-->
##### run the software
* execute ```python tkinterGUI_nw.py``` to run the software
<!--#### dup1OUTPUT.tif 
dup1OUTPUT.tif is a sample filed image, download it to GridFree folder:
https://drive.google.com/file/d/1hZzEpsqDWq7yrXRgDWwbDmQCY2iGni3Z/view?usp=sharing-->


<!---#### ***GDAL instllation instruction:***
1. RUN ```pip3 install GDAL==2.4.2```
   - if failed with error: > gdal-config not found
   - go to step 2.
2. RUN ```brew install gdal```, go to step 1
   - if failed with "gcc" go to step 3
3. RUN ```brew reinstall gcc```, go to step 1--->
#### If crashed
Modify matplotlibrc file ADD: ```backend: TkAgg```
<!--#### Reference
- [1] ImageJ https://imagej.nih.gov/ij/download.html
- [2] SeedCounter https://www.frontiersin.org/articles/10.3389/fpls.2016.01990/full
- [3] GrainScan https://plantmethods.biomedcentral.com/articles/10.1186/1746-4811-10-23-->
#### Area selection segment and delet demo
![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/areaselection.gif)
##### YouTube: https://youtu.be/oGYw1ZBcrhk

#### Wheat segment demo
![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/wheatdemo.gif)
##### YouTube: https://youtu.be/IxMBTT4fzr4

#### Chickpea segment demo
![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/480demo.gif)
##### YouTube: https://youtu.be/be12xOfF614

#### Corns segment demo
![screenshot](https://raw.githubusercontent.com/12HuYang/GridFree/master/corns_demo.gif)
##### YouTube: https://youtu.be/1ngHQsUFWH4


