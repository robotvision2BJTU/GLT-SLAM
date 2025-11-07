# Gaussian Landmarks Tracking-Based Real-Time Splatting Reconstruction Model
<br>

# :memo: To Do
- Release code of GLT-SLAM！
- Release RGB-D dataset of BJTU！

# :sparkles: 3DGS Models Visualization for GLT-SLAM<br>
- Campus Schoolmotto Scene<br>

  <img src="assets/schoolmotto_3dgs 00_00_00-00_00_30.gif" width="400px">

- Campus Bench Scene<br>

  <img src="assets/Bench_3dgs 00_00_00-00_00_30.gif" width="400px">

# :white_check_mark: Real-Time Reconstructing Visualization for GLT-SLAM<br>
- Replica office0 Scene<br>

<img src="assets/Replica_office0.gif" width="820px">

- Replica room1 Scene<br>

<img src="assets/Replica_room1.gif" width="820px">

# :hammer_and_wrench: Datasets Download and Preparation
To evaluate the Localization and Mapping performance, you can **download** our BJTU dataset.

- BJTU Dataset.
<br> Waiting for permission, will be released soon.
```
./
├── 
├── ...
└── data_path/
    ├──sequences
        ├── balloon/          
        │   ├── depth/	
        |   |	├── depth000000.png
        |   |	├── depth000001.png
        |   |	└── ...
        │   └── rgb/ 
        |       ├── frame000000.png
        |       ├── frame000001.png
        |       └── ...
        ├── belltower/ 
        ├── Bench/ 
        │   ├── depth/	
        |   | 	├── depth000000.png
        |   | 	├── depth000001.png
        |   | 	└── ...
        |   └── rgb/
        |       ├── frame000000.png
        |       ├── frame000001.png
        |       └── ...
        ├── schoolmotto/
        ├── ...

```

## Acknowledgments
We thanks for the opensource codebases, [Photo-SLAM](https://github.com/HuajianUP/Photo-SLAM), [CartGS](https://github.com/DapengFeng/cartgs
), [SplaTAM](https://github.com/spla-tam/SplaTAM) and [Noisy-Replica](https://github.com/Xiaohao-Xu/SLAM-under-Perturbation).
