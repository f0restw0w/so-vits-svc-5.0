数据集准备

    raw
    ├───speaker0
    │   ├───xxx1-xxx1.wav
    │   ├───...
    │   └───Lxx-0xx8.wav
    └───speaker1
        ├───xx2-0xxx2.wav
        ├───...
        └───xxx7-xxx007.wav
    
    此外还需要编辑config.json
    
    "n_speakers": 10
    
    "spk":{
        "speaker0": 0,
        "speaker1": 1,
    }
