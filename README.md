# Gentle-Aligner-Extension
GSoC '19 | Red Hen Lab 

Project aims to extend the existing Gentle Aligner to different langauges. This project involves integrating different language models in Gentle Aligner Tool.

Milestones [Next 4-6 weeks]

1. Running an ASR Kaldi recipe, generating an ASR model
2. Providing test data to the generated model to fetch timing information for the test audio data
3. Using the transcript to generate a new language model
4. Combining the language model with the previously used acoustic model and dictionary to obtain new FST.
5. Utilizing the new decoded graph in the Gentle tool to adapt it to the new language.
6. Repeating 1-5 on another language. 

Week 1: Running voxforge_ru recipe, generating ASR model. Figuring out how to extract timing information from the generated model. 

