# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
#Natural sampling
```
  1.Connect the trainer kit to the DC power supply (usually ±12V or ±15V as specified).
  2.Connect a sine wave signal (e.g., 1 kHz, 2V peak-to-peak) from the function generator to the message signal input of the sampling section on the trainer kit.
  3.Connect a sampling clock (square wave, e.g., 10 kHz) to the sampling control input (sometimes called "gate" or "clock").
  4.Use patch cords to complete all necessary connections from the signal generator to the trainer kit inputs and from the output of the sampler to the DSO.
  5.Observe the input message signal and sampling pulse on Channel 1 and Channel 2 of the DSO to verify proper timing.
  6.Observe the output of the sampler (natural sampled signal) on the DSO.
  7.You should see pulses that follow the amplitude of the input waveform but are present only when the sampling gate is active.
```
#Flattop sampling
```
  1.Keep the same message and sampling clock inputs as in natural sampling.
  2.Switch the trainer kit to flat-top sampling mode (if there is a toggle switch; otherwise, use the separate flat-top sampling section).
  3.Make necessary connections using patch cords to the flat-top sampling section of the kit.
  4.The difference here is that the sampled pulses will have flat tops, i.e., the amplitude will be constant during the pulse duration.
  5.Observe the flat-top sampled waveform on the DSO.
  6.Compare it with the natural sampled waveform.
  7.Note that in flat-top sampling, the samples appear as constant-height rectangles, unlike the sloped tops of natural sampling.
```
## CIRCUIT DIAGRAM

![diagram](https://github.com/user-attachments/assets/627bc5a1-2134-4fc5-a05f-f28d4ad609d0)

## MODEL GRAPH
![graph](https://github.com/user-attachments/assets/13419b45-9067-4d60-b7f8-1aaeaf02f460)

## TABLE
![table](https://github.com/user-attachments/assets/1cb0f2c0-5c5d-45cb-941c-e64c37597980)

## OUTPUT GRAPHS
#Natural Sampling
![natural output](https://github.com/user-attachments/assets/396b2286-08dd-41c5-ba2f-539881ff6e27)


#Flattop Sampling
![flattop sampling](https://github.com/user-attachments/assets/ef04f029-145f-41cc-8c75-29b23c9f19dd)


## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
