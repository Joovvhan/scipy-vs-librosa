# scipy-vs-librosa

##### The scipy.io.wavfile.read is twice faster than the librosa.core.load

![](/imgs/librosa_sr_none.png)

![](/imgs/scipy.png)

##### ~~To my surprise, when 'sr' is specified as the file sampling rate, the librosa is five times faster than the scipy.~~
##### The scipy is always faster than the librosa.

![](/imgs/librosa_sr_specified.png)

##### By default, librosa.core.load's parameter, 'sr' is set to 22500. NEVER interpolate wav files!

![](/imgs/librosa_sr_interpolate.png)
