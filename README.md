# FrequencyExtractor

This max patch takes the incoming frequency components of an audio track or audio input and smoothes the data flow coming out of the analyzer~ object and sends the first 10 frequency components and their amplitudes over OSC to wekinator.  This amounts to 20 values of frequency/amplitude pairs.  You can control the amount of smoothing by changing the smoothing value.

This feature extractor could be used to train wekinator on environments, sonic compositions, sound FXs or sound design components to trigger the outputs of your liking.  I would see it being best suited for doing sonic categorization.  

This feature extractor is built in Max MSP and thus needs Max to run it.  Max is not free however, but you can download and run patches already built without having to purchase it.  You can download Max at the following link: https://cycling74.com/downloads/



