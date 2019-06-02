# CocoToSTPhoto
 - COCO DataSet instances to STPhoto
  - Copyright (c) 2019 [InfoLab](http://infolab.kunsan.ac.kr) ([Donggun LEE](http://duration.digimoon.net))
   - https://pypi.org/project/cocotostphoto/


# HOW TO USE
```bash
python CocoToSTPhoto.py "d:/instances" "c:/annotation/stphoto.json" "d:/images"
python CocoToSTPhoto.py "d:/instances/instances_val2018.json" "c:/annotation/stphoto.json", "d:/images"
                               #input file or folder                   output file          image folder
```


# HOW TO INSTALL
- requirement
  ```bash
  # python 3.6 -- tensorflow
  pip install tensorflow==1.9.0 exifread>=2.1.2 piexif>=1.1.2 pillow>=6.0.0 matplotlib>=3.1.0 scikit-image>=0.15.0 IPython>=7.5.0 keras>=2.2.4 cython>=0.29.7 deepgeo

  # python 3.6 -- tensorflow-gpu
  pip install tensorflow-gpu==1.9.0 exifread>=2.1.2 piexif>=1.1.2 pillow>=6.0.0 matplotlib>=3.1.0 scikit-image>=0.15.0 IPython>=7.5.0 keras>=2.2.4 cython>=0.29.7 deepgeo
  ```
- install
  ```bash
  pip install cocotostphoto
  ```
