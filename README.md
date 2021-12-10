## LaneATT Reproductability Experiments
To reproduce the experiments, replace the files to the original file location and rename the file.
After replace the files, run the code according to the train part of the README.md file in the original LaneATT code.\
The original code can be found at https://github.com/lucastabelini/LaneATT

- laneatt_withoutanchor.py >> laneatt.py (LaneATT-main\lib\models)
- cross_entropy.py >> focal_loss.py (LaneATT-main\lib)
- laneatt_nopooling.py >> laneatt.py (LaneATT-main\lib\models)
- laneatt_noattention.py >> laneatt.py (LaneATT-main\lib\models)
- laneatt_vgg16.py >> laneatt.py (LaneATT-main\lib\models) laneatt_culane_vgg16.yml +>> (LaneATT-main\cfgs)
