# Ultrasound_mobile_database
database of Doppler measurement via mobile ultrasound sensing

The database is accompanied to our published paper with the title "Generalization of Fitness Exercise Recognition from Doppler Measurements by Domain-Adaption and Few-Shot Learning".

The database contains two sets of environmental data, one under constrained laboratory environment and one under unconstrained individual environments. 
The wav file has been processed to remove the sensitive data, such as natural speech. The following processing steps were applied to the original wav file. 
The center frequency of 20 kHz is removed and the time signal is bandpassed in time to a frequency range of 19-21kHz, only containing the Doppler information caused by motion.
The sampling frequency is 44.1 kHz.

The wav file can be read with scipy.io.waveread.

Please also cite our work:

@article{fu2020performing,
  title={Performing Realistic Workout Activity Recognition on Consumer Smartphones},
  author={Fu, Biying and Kirchbuchner, Florian and Kuijper, Arjan},
  journal={Technologies},
  volume={8},
  number={4},
  pages={65},
  year={2020},
  publisher={Multidisciplinary Digital Publishing Institute}
}

Or:

@inproceedings{fu2020unconstrained,
  title={Unconstrained workout activity recognition on unmodified commercial off-the-shelf smartphones},
  author={Fu, Biying and Kirchbuchner, Florian and Kuijper, Arjan},
  booktitle={Proceedings of the 13th ACM International Conference on PErvasive Technologies Related to Assistive Environments},
  pages={1--10},
  year={2020}
}
