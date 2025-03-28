# Autogenous

- Listen: [https://d197y4nq5zdq2y.cloudfront.net/autogenous.mp3](https://d197y4nq5zdq2y.cloudfront.net/autogenous.mp3)
- All my music: https://syntrice.com/music/

## About

“Autogenous” is a stereo electroacoustic composition primarily centred around two 
algorithmic composition techniques: Markov chains and Euclidean rhythms. From 
the writings of McAlpine, Mirando and Hoggar, Markov chains are a type of 
stochastic algorithm: they are “discrete probability systems” which relate future 
events to the outcome of “one or more past events” (1999, 20–22). As the prime 
example of a “stochastic” composer, Iannis Xenakis uses Markov chains to control 
complex structures in several of his works, including Analoqique A and B (1958
1959), and his 1959 work “Syrmos” (Ames 1989, 176; Harley 2004, 37).

“Autogenous” takes a much simpler approach: a first-order Markov chain is 
used solely to determine the progression of major and minor seventh chords via four 
different root transformations. These transformations are based upon neo
riemannian and octatonic theories outlined by Cohn and Hyer (Cohn 2012; Hyer 
1995), and are summarised as follows: minor-third up, minor-third-down, perfect
fifth up, perfect-fifth down. The minor-third transformations move to a chord within 
the same octatonic collection, while the perfect-fifth operations move between 
collections via dominant motion: these relationships are summarised in Figure 1. 
Furthermore, each transformation may move to either a major or minor seventh 
chord, and an additional transformation simply flips the modality of the chord. As the 
piece is written and playable using Supercollider 3.13.0, the probability of each 
transformation occurring is controllable; the listener is encouraged to adjust these 
values to produce varied harmonic structures. However, for the accompanied 
recording, the probabilities used are summarised in Table 1.

![image](https://github.com/user-attachments/assets/2b843d28-2e8d-48c3-a781-6e1f0801d80a)

Figure 1: a matrix indicating the possible root transformations from a chord of C

While the harmonic progression of the piece is determined algorithmically, the 
textural structure is composed much more freely. The piece first begins with 
ambiguous metricity before the material gradually coheres into a constant 7/8 meter: 
the texture rhythmic texture is then built upon throughout, before dissipating in the 
conclusion. The contrast between the algorithmic harmonic structure and free
composed texture highlights the importance of balancing control and randomness: a 
principle that is a defining characteristic of John Cage’s chance compositions (Jensen 
2009). His “Music of Changes” (1951) is one of the most notable examples of this type 
of composition. 

Table 1: the probability matrix used in the recording of the work

| Transformation                               | Probability |
|----------------------------------------------|-------------|
| Minor 3rd up, to major 7th chord            | 23.33%      |
| Minor 3rd up, to minor 7th chord            | 23.33%      |
| Minor 3rd down, to major 7th chord          | 3.33%       |
| Minor 3rd down, to minor 7th chord          | 3.33%       |
| Perfect 5th up, to major 7th chord          | 16.67%      |
| Perfect 5th up, to minor 7th chord          | 16.67%      |
| Perfect 5th down, to major 7th chord        | 3.33%       |
| Perfect 5th down, to minor 7th chord        | 3.33%       |
| Parallel major/minor                        | 6.67%       |

There is however an additional formulaic tool used throughout the piece: the 
percussive elements are predominantly derived from Bjorklund’s algorithm, which is 
in turn based on the Euclidean algorithm (Toussaint 2005, 47–48). As observed by 
Toussaint, this algorithm works by distributing k number of events over n number of 
time steps. By using this algorithm to produce rhythm, and adjusting the phase 
between different percussion voices, a dynamic rhythmic texture is created 
throughout the piece.

## Running the Code

Instructions for running the piece can be found within the source code.

## Licence

Copyright © Samuel Maughan 2025. All Rights Reserved.
