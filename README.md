# Gentle-Aligner-Extension
GSoC '19 | Red Hen Lab 

Project aims to extend the existing Gentle Aligner to different langauges. This project involves integrating different language models in Gentle Aligner Tool.

Milestones [Next 4-6 weeks]

Running an ASR Kaldi recipe, generating an ASR model
Providing test data to the generated model to fetch timing information for the test audio data
Using the transcript to generate a new language model
Combining the language model with the previously used acoustic model and dictionary to obtain new FST.
Utilizing the new decoded graph in the Gentle tool to adapt it to the new language.
Repeating 1-5 on another language.
Week 1: Running voxforge_ru recipe, generating ASR model. Figuring out how to extarct timing information from the generated model.

Tools:

Kaldi, Python libraries, C++

