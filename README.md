# peaceful
Prototype computer vision model used to determine whether a baby is sleeping upright given a camera image (baby safety feature for Nest cameras), uses transfer learning for CV

<img width="163" alt="Screenshot 2023-11-07 061319" src="https://github.com/danieltien13/peaceful/assets/69093784/507739b4-2572-4de8-9ee1-e8d374c755f8">
Able to achieve accuracy of 96% (ideally switch to precision/recall) on the validation set. 

To run the notebook:

`jupyter lab`

In order to generate images from a video:

`sudo ffmpeg -i /home/dtien/video_data/baby_data_1.mp4 -vf fps=1 /home/dtien/video_data/frames/frame%06d.jpg`
