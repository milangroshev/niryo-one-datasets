# Niryo One robot Dataset
## Digital Twin Scalability Dataset
Details for the dataset collecton can be found in the two published papers that are mentioned below.

Dataset from a Digital Twin comprising a Niryo One robot manipulator

 - Micro dataset: new robot instance is added every 60 seconds. (dataset available [here](./dataset/micro-dataset/)).
 - Small dataset: new robot instance is added every 300 seconds. (dataset available [here](./dataset/small-dataset/)).
 - Big dataset:   new robot instance is added every 3600 seconds. (dataset available [here](./dataset/big-dataset/)).
   - labeled version is available of the big dataset that is used to train Random Forest classifier.  

### Citations
If you find this dataset useful in your research, we would appreciate citations to the following papers:

 1) Digital Twin service used to collect the dataset:
```
@INPROCEEDINGS{9367549,
  author={L. {Girletti} and M. {Groshev} and C. {Guimarães} and C. J. {Bernardos} and A. {de la Oliva}},
  title={An Intelligent Edge-based Digital Twin for Robotics},
  booktitle={2020 IEEE Globecom Workshops (GC Wkshps},
  year={2020},
  volume={},  
  number={},  
  pages={1-6},  
  doi={10.1109/GCWkshps50303.2020.9367549}
}
```

 2) SLA management via scaling making use of this dataset:
```
@INPROCEEDINGS{Bara2105:Demo,
  author="Jorge Baranda and Josep Mangues-Bafalluy and Engin Zeydan and Claudio E.
  Casetti and Carla Fabiana Chiasserini and Marco Malinverno and Corrado
  Puligheddu and Milan Groshev and Carlos {Guimarães} and Konstantin Tomakh
  and Denys Kucherenko and Oleksii Kolodiazhnyi",
  title="Demo: {AIML-as-a-Service} for {SLA} management of a Digital Twin Virtual
  Network Service",
  booktitle="IEEE INFOCOM 2021 Demo (IEEE INFOCOM Demo 2021)",
  address=virtual,
  days=10,
  month=may,
  year=2021,
}
```
## Digital Twin Remote Control Dataset
Details for the dataset collecton can be found in the published papers that are mentioned below.

Dataset from a Digital Twin comprising a Niryo One robot manipulator performing 4 different actions. 
Details about the actions can be found in the movements-for-paper-dataset.mp4 video that is available [here](./digital-twin-remote-control/).

### Citations
If you find this dataset useful in your research, we would appreciate citation to the following paper:

```
@ARTICLE{9530501,
  author={Groshev, Milan and Guimarães, Carlos and Martín-Pérez, Jorge and de la Oliva, Antonio},
  journal={IEEE Communications Magazine}, 
  title={Toward Intelligent Cyber-Physical Systems: Digital Twin Meets Artificial Intelligence}, 
  year={2021},
  volume={59},
  number={8},
  pages={14-20},
  doi={10.1109/MCOM.001.2001237}}

  ```

