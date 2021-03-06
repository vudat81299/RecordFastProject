# RecordFastProject iOS

<h3 align="center">
  <img width="200px" src="https://user-images.githubusercontent.com/55421234/110569031-80b6da80-8186-11eb-8a8a-5eef2a5e22a2.gif">
  <img width="200px" src="https://cdn.dribbble.com/users/45617/screenshots/12910101/media/c170a9a4d64ad4dff24bac58529d26bb.png">
</h3>

# When use?
+ **For iOS developer reference purpose only. (learning how to make a recorder app, and config the output)**
+ This project help you record superfast by my custom and support text you will record show on screen with .csv file.
+ Using to making data to train model.

# Feature
+ Record into .wav extension by default (custom output extension in source).
+ Some specification are set for Audio format in this project **(you can config output type as anything you want - add, remove, fix value of any specification for a Audio format in source)**:
> + AVFormatIDKey: Int(kAudioFormatLinearPCM)
> + AVSampleRateKey: 16000
> + AVNumberOfChannelsKey: 1
> + AVEncoderAudioQualityKey: AVAudioQuality.max.rawValue
> + AVLinearPCMBitDepthKey: 32
+ Record with low latency.
+ Show text to read. Change content in .csv file.
+ Auto increment name output file.
+ Just for fast record so cannot play recorded file, access the file manager on iphone to play your record.

# How fast?
> + Tested **record and save 10 .wav file** with **12-15 word** per file in just **1 minute**.
> + No crash, low latency.

# Prerequisite
> + A iOS developer to understand and custom this.

# How to build?
1. Clone project and open.
2. Switch to your account development in xcode. 
3. Add content to record in csv file.
4. Build and run.

# Where output saved?
> + Output is saved in document folder of this app in file manager on iPhone.
> # How to take data?
> + Method 1: Connect to a MacOS PC.
> + Method 2: Access file manager on iPhone and upload to anywhere you want.

# Config output quality
> + This project record and extract .wav file.
> + Depend on your required output, config quality or type of output in code. **You control your output**, remmember that!
