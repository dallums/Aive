# Aives

Please use the "face_detector_app.ipynb" for the analysis - I had silly env issues trying to make a cleaner single python script and this worked instead.

Cells are meant to be run in order. During the output of either video (face or human), press enter to stop and end the analysis. Sometimes it's buggy and you need to go Kernel -> Restart & Clear Output to kill the video popup.

Install packages manually in a venv, or used the anaconda3 kernel for the notebook for best results. The YouTube video needs to be downloaded as an mp4 in this case as well.

I use OpenCV, which seems pretty standard, and tune paramters based on some initial high level advice here: https://www.pyimagesearch.com/2015/11/16/hog-detectmultiscale-parameters-explained/
