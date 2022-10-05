# Dataset for the paper "Automatically Prepare Training Data for YOLO Using Robotic In-Hand Observation and Synthesis" 

This repository contains the datasets, models, test results and for the paper "Automatically Prepare Training Data for YOLO Using Robotic In-Hand Observation and Synthesis". We proposed combining robotic in-hand observation and data synthesis to enlarge the limited data set. We first used a robot with a depth sensor to collect images of objects held in the robot's hands and segment the object pictures. Then, we used a copy-paste method to synthesize the segmented objects with rack backgrounds. The collected images and the synthetic ones are combined to train a deep detection neural network. We conducted experiments to compare YOLOv5x detectors trained with images collected using the proposed method and several other methods. The results showed that combined observation and synthetic images led to comparable performance to manual data preparation. They provided a good guide on optimizing data configurations and parameter settings for training detectors. The proposed method required only a single process and was a low-cost way to produce the combined data.

## Changelog
[Oct 2022] Initial release of TubeDet
 
## Datasets and Weights
The datasets used in the paper (Table I of the paper).
| Dataset Names| Dataset links | Description|
| :----: | :----: | :----: |  
|SB| | | Synthesis data generated by pasting tube caps to racks
|SR| | | Synthesis data generated by pasting tube caps to random background
|RO| | | Robotic obbservation images (Tubes held in robotic hands)
|CL| | | Manually labeled traing images (Tubes in a rack on the table)
|Test| | Manually labeled testing images (Tubes in a rack on the table)


---

Table I
| Dataset Names| Weight Links |
| :----: | :----: |


Table II
| Dataset Names| Weight Links |
| :----: | :----: |

Table III
| Dataset Names|Weight Links |
| :----: | :----: |

Table IV
| Dataset Names|Weight Links |
| :----: | :----: |

Table V
| Dataset Names| Weight Links |
| :----: | :----: |

Table VI
| Dataset Names|Weight Links |
| :----: | :----: |
