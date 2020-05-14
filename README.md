# opencv-text-detection
https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/ by Adrian Rosebrock

# Required
pip install --proxy=http://proxy:8080 --upgrade -U imutils
pip install --proxy=http://proxy:8080 --upgrade -U opencv-contrib-python

# RUN
python text_detection.py --image images/lebron_james.jpg --east frozen_east_text_detection.pb
