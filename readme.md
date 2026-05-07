# Quiz 8

## Part 1: Imaging Technique Inspiration

### Imaging Technique
**Audio-reactive immersive fluid visualization**

### Discussion
My inspiration comes from teamLab’s *Universe of Water Particles on a Rock where People Gather* and *Black Waves: Immersive Mass*. The first work uses real-time particle simulation so visitors can alter water flow by touching or entering the space. The second creates an immersive sense of life through continuous black waves and line-based motion. I want to apply this logic of fluid lines, real-time transformation, and embodied immersion in my project. This direction is beneficial because it turns interaction into expressive visual narrative and can integrate well with my team’s other mechanics.

### Screenshots / Images
![teamLab Universe of Water Particles](https://image.team-lab.cn/unsafe/plain/s3%3A%2F%2Fimagewave-sites-prd-imageproxy-bucket%2F6qQfS6bKtpqMrKJtLUoUk9)

![teamLab Black Waves Immersive Mass](https://image.team-lab.cn/unsafe/plain/s3%3A%2F%2Fimagewave-sites-prd-imageproxy-bucket%2Fdgha6em5eWLFeLDLNzg3A)

### Example Sources
- [teamLab: Universe of Water Particles on a Rock where People Gather](https://art.team-lab.cn/en/ew/iwa-waterparticles/)
- [teamLab: Black Waves: Immersive Mass](https://art.team-lab.cn/en/w/blackwaves_immersive_mass/)

---

## Part 2: Coding Technique Exploration

### Coding Technique
**`p5.FFT` frequency analysis**

### Discussion
I will use `p5.FFT` to analyse audio by frequency bands and map that data to visual behavior. Low frequencies can drive large wave movement, while higher frequencies can control fine line flicker and particle detail. This directly supports the layered fluid motion in my teamLab references. Because FFT returns structured spectrum data every frame, the visuals can react to sound in real time while remaining controllable and readable. This makes FFT a strong single technique for implementing my Audio mechanic.

### Screenshot / Image
![p5.js FFT audio visualization example](assets/images/fft-in-action.png)

### Example Implementation Link
- [The Coding Train - Frequency Analysis with FFT](https://thecodingtrain.com/tracks/sound/sound/11-sound-visualization-frequency-analysis)

### Example Code Link
- [Coding Train source code](https://github.com/CodingTrain/website/tree/main/CodingChallenges)
