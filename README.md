# czz001

The input image data must have 3 channels. If the data source is 4 channels, run 4to3andPNG.py to reduce the channels

The image data must be PNG. If the data comes from other data formats, convert the file format through 4to3andPNG.py

configs.py is picture 2X ， configs2.py is picture 4X
(First, put your desired low-res files in <ZSSR_path>/test_data/.
Results will be generated to <ZSSR_path>/results/<name_date>/.
data must be *.png type)

python maml_zssr.py
