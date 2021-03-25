# KazooKart
# Summary

## Project Requirements
This project was completed for the course CS-4430, Maching Learning & Intelligent Agents at Cedarville University (c). This is assigment is the Term Project for Spring 2021. In this project we were to choose an adequate project to last the rest of the semester. The project is to be done in Unity using ML-Agents ([release 12](https://github.com/Unity-Technologies/ml-agents/tree/release_12_docs)).

## Dependencies
* [ML-Agents Release 12](https://github.com/Unity-Technologies/ml-agents/tree/release_12_branch)

## Instructions to Open Project in Unity
1. Ensure ML-Agents Release 12 is cloned locally on your system
2. After cloning this repo, navigate to `./Kazoo Kart/Packages` and open both `manifest.json` and `packages=lock.json`
3. Within both files, locate the following line: `"file:T:/School/S21/Machine Learning/Project 3/ml-agents/com.unity.ml-agents"` (or something similar) and replace it with `"file:C:/local/path/to/ml-agents-release-12-repo/ml-agents/com.unity.ml-agents"`
4. Open Unity Hub
5. Click "Add"
6. Navigate to this Git folder and select folder `Kazoo Kart`
   * (e.g. "C:\Users\${USER}\path\to\git_folder\Kazoo Kart\")
7. Open newly added project in Unity Hub
   * It will take a few minutes to open as it pulls the dependencies and creates a project module

## Credits
This project makes ust of the [ML-Agents](https://github.com/Unity-Technologies/ml-agents) Git Repository. Additional dependencies include Python 3.7|3.8 and [pytorch](https://pytorch.org/).

# Design
Term Project for CS-4430, Machine Learning &amp; Intelligent Agents at Cedarville University (c).
Our Term Project, *Kazoo Kart*, takes an Agent (a Kazoo Kart) and trains it to follow a track and locate the finish line using Reinforcement Learning. The Agent is set up with spatial awareness observations as well as 3D RayCasting.