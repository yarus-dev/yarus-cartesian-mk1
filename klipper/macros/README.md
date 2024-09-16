## Start g-code
```
SET_PRINT_STATS_INFO TOTAL_LAYER=[total_layer_count]
START_PRINT BED=[bed_temperature_initial_layer_single] EXTRUDER=[nozzle_temperature_initial_layer]
```
## End g-code
```g-code
END_PRINT
```
## Print by object
```
```

## 
```g-code
BEFORE_LAYER_CHANGE LAYER=[layer_num] HEIGHT=[layer_z]
```