# czz001

Meta-Learning for Zero-Shot Remote Sensing Image Super-Resolution

Official implementation for paper by: zhangzhao cha

Paper: (https://www.mdpi.com/2227-7390/11/7/1653)

The input image data must have 3 channels. If the data source is 4 channels, run 4to3andPNG.py to reduce the channels

The image data must be PNG. If the data comes from other data formats, convert the file format through 4to3andPNG.py

configs.py is picture 2X ， configs2.py is picture 4X

(First, put your desired low-res files in <ZSSR_path>/test_data/.
Results will be generated to <ZSSR_path>/results/<name_date>/.
data must be *.png type)

python maml_zssr.py

If you find our work useful in your research or publication, please cite our work:

MDPI and ACS Style
Cha, Z.; Xu, D.; Tang, Y.; Jiang, Z. Meta-Learning for Zero-Shot Remote Sensing Image Super-Resolution. Mathematics 2023, 11, 1653. https://doi.org/10.3390/math11071653

AMA Style
Cha Z, Xu D, Tang Y, Jiang Z. Meta-Learning for Zero-Shot Remote Sensing Image Super-Resolution. Mathematics. 2023; 11(7):1653. https://doi.org/10.3390/math11071653

Chicago/Turabian Style
Cha, Zhangzhao, Dongmei Xu, Yi Tang, and Zuo Jiang. 2023. "Meta-Learning for Zero-Shot Remote Sensing Image Super-Resolution" Mathematics 11, no. 7: 1653. https://doi.org/10.3390/math11071653
