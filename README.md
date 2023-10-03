# EnviroVoiceImpersonator-EVI
Stick it on objects and stuff! It’ll talk… or else

High Level Description:

What: Compact, low-cost, modular conversational dialogue language artifact/smart speaker that you can stick onto objects to imbue them with a personality, powered by foundation models.
Why: It'd be pretty funny!!! Also, you could have a way to mod the real world with AI really easily, you could use it for explaining sculptures, or giving actually useful information. Basically, you can make anything in the real world interactive, which is useful for a lot of actually functional things.
How: Cheap compute (Pi Zero W possibly), speaker microphone system, rechargeable battery (usb-c and also cabled solar panel accessory, modular attachment points, modular attachment accessories, speech transcription API, voice synthesis API, Wifi-enabled, LED, 1 button.

1st version: tiny smart speaker version for edge access inside of wifi networks

2nd version: larger compute, local computation, possibly lte or 5g on the device

Technical details:

Audio:
-speech to text, need to know when to stop listening
-text to speech (whisper, realtime)
-self suppression of own speech to stop feedback loops

Memory:
-efficient buffer usage for the ram

Input:

Prototype:
-running on laptop and able to tie together all the API's, try to measure all the latency, and optimize for low latency, low memory usage.
