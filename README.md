# TreeMeaS (Tree Measurement Sampling Tool)
Android-Based APP for Horizontal Point Sampling (HPS), Borderline Factor, and Upper-Stem Diameter calculation.

## Objectives
1. HPS: Pitch-calibrated angle gauge APP.

2. Upper-Stem Diameter: Measure upper-stem diameter for better volume estimation.

### WHY DO WE NEED THIS? 
1. Forest mensuration usually face the slope problem when doing HPS, we can't get the correct gauge width when we are on a slope, especially in Taiwan.
2. Upper-stem diameter is a critical attribute of the forest. However, it is often neglected in Taiwan.
3. Borderline factor is useful for Critical Height Sampling.
4. Digital Suunto for height measurement.

### AS A RESULT
1. We need the pitch angle calibration for the HPS gauge.
2. Based on 1. and other geometric methods, we can get a transformation for upper-stem diameter to horizontal diameter.

### Technology
1. Android APP.
2. IMU in mobile phone for orientation.
3. Develop the pitch calibration mathematical formula for upper-stem diameter measurement.

## Function of each file
### 1. app/src/main/java/com/example/fragment/BarOverlay.kt
> #### Providing the bar(gauge) object for HPS. 
### 2. app/src/main/java/com/example/model/AngleModel.kt
> #### Providing the pitch calibration on HPS gauge and other pitch related functions.
### 3. app/src/main/java/com/example/TreeMeaS/BLF.kt
> #### Activity of Borderline Factor function.
### 4. app/src/main/java/com/example/TreeMeaS/HPS.kt
> #### Activity of Horizontal Point Sampling function.
### 5. app/src/main/java/com/example/TreeMeaS/USD.kt
> #### Activtity of Upper Stem Diamter function.
### 7. app/src/main/java/com/example/TreeMeaS/TreeMeaSApplication.kt
> #### Some variables in this project.
### 9. app/src/main/java/com/example/TreeMeaS/homepage.kt 
> #### Homepage for this application.
### 10. app/src/main/java/com/example/TreeMeaS/Copyright.kt
> #### Copyright file.
### 11. app/src/main/java/com/example/TreeMeaS/Info.kt
> #### Application usage introduction. (Not designed yet)
### 12. app/src/main/java/com/example/util/BitmapSnapshot.kt
> #### The combination of 2 bitmaps for Snapshot.
### 13. app/src/main/java/com/example/util/Orientation.kt
> #### Calculation formulas for orientation.
### 14. app/src/main/java/com/example/viewModel/BLFSensorViewModel.kt
> #### Sensor detection ViewModel in BLF.
### 15. app/src/main/java/com/example/viewModel/USDSensorViewModel.kt
> #### Sensor detection ViewModel in USD.
### 16. app/src/main/java/com/example/viewModel/CameraViewModel.kt
> #### Camera ViewModel for basic camera information, especially Field of View and Screen Width.
### 17. app/src/main/java/com/example/viewModel/SensorViewModel.kt
> #### Sensor detection ViewModel in HPS.
