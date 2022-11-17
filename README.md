### Hi there 👋
### This is the support code for the "Temporal Understanding of Gaze Communication with GazeTransformer".


Gaze plays a crucial role in daily social interactions as it allows humans to communicate intentions effectively. 
We address the problem of temporal understanding of gaze
communication in social videos in two stages. First, we develop GazeTransformer, an end-to-end module that predicts
atomic-level behaviours in a frame. Second, we develop
a temporal module that predicts event-level behaviours in
a video using the inferred atomic-level behaviours. Comared to existing methods, GazeTransformer does not 
require human head and object locations as input. Instead, it identifies these locations in a parallel and end-to-end
manner. In addition, it can infer more atomic-level behaviours that cannot be handled by previous approaches.
We achieve state-of-the-art performance on both atomic- and event-level prediction on the VACATION+ dataset.
## Dataset (VACATION+) ##

The VACATION+ folder contains the annotations of the modified VACATION dataset.

Please [contact the authors of the original VACATION dataset](https://github.com/LifengFan/Human-Gaze-Communication) to access the corresponding video.

You will need to fill out a Google form to request access.

## Training (in progress) ##

## Evaluation (in progress) ##

## Demo ##
We aim to simultaneously predict head and object locations and infer their corresponding gaze relationships in an end-to-end manner.

Unlike previous end-to-end models that can only infer attended targets or handle Mutual gaze relationships, our GazeTransformer can predict Single, Share and Mutual atomic-level behaviours (see below).

![Alt Text](sample_output/64.gif)

Sample results of our model can be found in the [sample_output](sample_output) folder.

The dotted rectangles represent ground truth human and object locations, while solid rectangles represent model predictions.

Correctly classified atomic-level labels are in green, while incorrectly classified labels are in red and above their corresponding ground truth labels.

<!--
**gazetransformer/gazetransformer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
