# keyword spotting work stream
Encoding / Decoding 


## split across two datasets

> a. SHD  
> b. GSC

# A. SHD

### the hierarchy of the dataset

```
root
|-spikes
   |-times[]
   |-units[]
|-labels[]
|-extra
   |-speaker[]
   |-keys[]
   |-meta_info
      |-gender[]
      |-age[]
      |-body_height[]
```

Each datum consists of two lists that contain the firing times and the unit id of which neuron has fired at the corresponding firing time.

