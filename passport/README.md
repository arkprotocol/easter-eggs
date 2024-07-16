# Ark InterChain Passport

Merging png and wav into h264/mp4:

```sh
ffmpeg -loop 1 -framerate 30 -i ark_anthem_cover.png -i ark_anthem.wav -c:v libx264 -vf scale=720:720 -c:a aac -b:a 192k -pix_fmt yuv420p -shortest output_720p.mp4
```