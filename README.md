# unitree_go1
Unitree Robot Dog - Unitree Go1 

### Requisites:
- [unitree_legged_sdk](https://github.com/unitreerobotics/unitree_legged_sdk)
- [UnitreecameraSDK](https://github.com/unitreerobotics/UnitreecameraSDK)

### Build unitree_legged_sdk
```bash
mkdir build
cd build
git clone https://github.com/JMild/unitree_go1.git
cmake ..
make
```

### Build UnitreeCameraSDK
```bash
cd UnitreecameraSDK;
mkdir build && cd build;
cmake ..; make
```

Get Camera Raw Frame:
```bash
cd UnitreeCameraSDK; 
./bin/example_getRawFrame 
```

### RUN
Run file example_walk
```bash
cd unitree_legged_sdk/build; 
sudo ./example_walk
```
Run file control_go1
```bash
cd unitree_legged_sdk/build; 
python3 control_go1.py
```
