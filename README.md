# EnviroVoiceImpersonator-EVI
Stick it on objects and stuff! It’ll talk… or else

High Level Description:

Abstract: Essentially a hat for allowing physical objects to have language model capabilities.

What: Compact, low-cost, modular conversational dialogue language artifact/smart speaker that you can stick onto objects to imbue them with a personality, powered by foundation models.
Why: It'd be pretty funny!!! Also, you could have a way to mod the real world with AI really easily, you could use it for explaining sculptures, or giving actually useful information. Basically, you can make anything in the real world interactive, which is useful for a lot of actually functional things.
How: Cheap compute (Pi Zero W possibly), speaker microphone system, rechargeable battery (usb-c and also cabled solar panel accessory, modular attachment points, modular attachment accessories, speech transcription API, voice synthesis API, Wifi-enabled, LED, 1 button.

1st version: tiny smart speaker version for edge access inside of wifi networks

2nd version: larger compute, local computation, possibly lte or 5g on the device

Technical details:

Language Model/AI:
-character.ai unofficial API https://github.com/kramcat/CharacterAI
-inworld.ai for character personalities
-XRAgents possible

Audio:
-speech to text, need to know when to stop listening (whisper, realtime)
-text to speech (elevenlabs, azure, google voices)

-self suppression of own speech to stop feedback loops

Memory:
-efficient buffer usage for the ram

Input:
-one button to do custom behavior

Prototype:
-running on laptop and able to tie together all the API's, try to measure all the latency, and optimize for low latency, low memory usage.
