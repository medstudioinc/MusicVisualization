This project ports some music visulization shaders from WebGL([Shadertoy.com](https://www.shadertoy.com/)) to Android OpenGL ES. It captures the audio's fft & waveform data by system's [`Visualizer`](https://developer.android.com/reference/android/media/audiofx/Visualizer.html), and then pass them to a 2-lines height texture that can be used in a shader program ([more detail](https://forum.openframeworks.cc/t/passing-fft-audio-data-into-a-shader-as-a-texture2d-object-shadertoy/13756)).

![Preview](image/p1.png) ![Preview](image/p2.png) ![Preview](image/p3.png) ![Preview](image/p4.png) ![Preview](image/p5.png) etc

Download apk to try: [Releases page](https://github.com/nekocode/MusicVisualization/releases)
