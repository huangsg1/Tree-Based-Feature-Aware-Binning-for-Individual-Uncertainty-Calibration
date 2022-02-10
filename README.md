# MBCT: Tree-Based Feature-Aware Binning for Individual Uncertainty Calibration 
## Dataset
- CACTRDC
  - We dumped the impression and click logs from Alibaba Group's commercially deployed online display advertising system, and we call this dataset CACTRDC, which is the acronym for Computation Advertising Click-Through PredictionDataset for Calibration.
  - Download Link: https://drive.google.com/file/d/1xucH0ZRdbP10A6siRolGOiLqxyieOWJF/view?usp=sharing
    - In our work, we split this csv file into calibration training (the first 11110227 lines) and test set. 
    
- Porto Seguro (https://www.kaggle.com/c/porto-seguro-safe-driver-prediction)
  - For Porto Seguro, the selected seven features are ps_ind_05_cat, ps_ind_17_bin, and ps_car_01_cat, ps_car_06_cat, ps_car_07_cat, and ps_car_09_cat. 

- Avazu (https://www.kaggle.com/c/avazu-ctr-prediction)
  - For Avazu, the selected seven features are banner_pos, site_id, site_category, device_type, C16, C19, and C20.
  - In our work, we split dataset into training and test set according to sampling time.
  - Downlod Link: https://drive.google.com/file/d/1lEHhE_kqb8RVee5JylZQiyrSi2dVBzNV/view?usp=sharing
