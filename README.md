Graph Convolutional Networks for Event Causality Identification with Rich Document-level Structures
==========

This repo contains our PyTorch implementation for the paper [Graph Convolutional Networks for Event Causality Identification with Rich Document-level Structures](https://aclanthology.org/2021.naacl-main.273.pdf). 


## event-causality

1. Create and activate a new environment:
```
conda create -n evcausality python=3.6 && conda activate evcausality
```
2. Install required libs:
```
pip install -r requirements.txt
```
3. Preprocess data for EventStoryLine:
```
python prepare_data.py
```
4. Train the model:
```
python train.py
```

## Citation

```
@inproceedings{tran21graph,
    title = "Graph Convolutional Networks for Event Causality Identification with Rich Document-level Structures",
    author = "Tran, Minh Phu  and
      Nguyen, Thien Huu",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.273",
    doi = "10.18653/v1/2021.naacl-main.273",
    pages = "3480--3490",
}
```

## License

All work contained in this package is licensed under the Apache License, Version 2.0.