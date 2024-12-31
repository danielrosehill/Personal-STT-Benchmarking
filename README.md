# Personal STT Benchmarking

## Purpose Statement

This project contains a couple of vocal samples I used in order to evaluate the efficacy of different automatic speech recognition (ASR) speech to text models attempting to compute word error rates (WERs).

I entitled this repository personal STT Benchmarking because it's reflective of the very personal nature of this type of evaluation. 

5 minutes of voice samples are clearly not enough to do anything like fine tuning or conducting robust analysis. But for the kind of first pass evaluation that many consumers might be interested in doing (to try to get a ballpark estimate for whether (off-the-shelf) model A or model B might have higher accuracy for speech to text considering the unique variabilities of their accent speaking pattern intonation) I thought that the structure the experiment might be useful. 
 
## Synthetic Transcript Generation

I used a large language model in order to generate synthetic data which was attempted to be representative of the type of data that might be captured by users in the course of using various speech to text tools. 

It took a few iterations at prompting and Assistant configuration in order to get something like representative data. I seem to have most success by using the "fly on the wall" metaphor - telling the model that its purpose was to generate simulated transcripts as if it were a fly on the wall transcribing voice commands and speech a user was dictating into voice to text tools.

I attempted to coax the large language models to generate synthetic data reflective of the type of use I make for voice to text commonly considering very routine things like creating calendar entries, task entries and creating some voice notes. Additionally, I included a couple of synthetic elements intended to model LLM prompts captured by dictation.   

Lest the couple of short voice samples and transcripts serve as useful material for anyone else evaluating different STTs ..... I'm happy to provide my voice as a data point!

## Author

Daniel Rosehill  
(public at danielrosehill dot com)

## Licensing

This repository is licensed under CC-BY-4.0 (Attribution 4.0 International) 
[License](https://creativecommons.org/licenses/by/4.0/)

### Summary of the License
The Creative Commons Attribution 4.0 International (CC BY 4.0) license allows others to:
- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

#### License Terms
- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **No additional restrictions**: You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For the full legal code, please visit the [Creative Commons website](https://creativecommons.org/licenses/by/4.0/legalcode).