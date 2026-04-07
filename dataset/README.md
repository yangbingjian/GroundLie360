# GroundLie360 Dataset  
Video files can be downloaded [here(Baidu Disk)](https://pan.baidu.com/s/18gVXt0GSg1--SyNm6flpdw?pwd=vmj3) or [here(OneDrive)](https://1drv.ms/f/c/4900809cf598ca24/IgBhYxreDDVKS5aASa3ypGoaAe52eP_P2ORzX0yOEh62nCo?e=C7wzgZ).

If you want to extract video frames and align them with frame index in annotation file, use the following command.

```
ffmpeg -i input_video.mp4 -vsync vfr frame_%05d.png
```

