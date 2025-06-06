# mark2.3.0
- Based on mark2.2.0

## License
- This project is licensed under the PolyForm Noncommercial License 1.0.0.
- Commercial use is not permitted.
- See the [LICENSE](LICENSE) file for details.

## Results
- In mark2.3.0, the target data category is labeled as "construction" and consists of 30 hammer sounds and 20 drill sounds. However, both the mel spectrograms and raw waveforms—along with auditory inspection—clearly show that hammer and drill sounds are distinctly different. This inconsistency appears to have caused confusion during supervised training, likely contributing to the model’s low accuracy.  
- Based on these findings, I concluded that future experiments should separate the target classes: 'mark2.3.1' will include only 'construction_drill' sounds, while 'mark2.3.2' will contain only 'construction_hammer' sounds. This model differentiation is intended to provide clearer labels and allow the model to learn more accurately by avoiding class ambiguity.    

