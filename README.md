# C-WAVE-Loader
Utility library for C/C++ for loading WAV audio file.


## Functions

* load_wave_file
```cpp

// This function is used to fetch all information form given wave file and return formated struct.

// Params: path to file
	
wave_t * wav_file = load_wave_file("life.wav");


```
* close_wave_file
```cpp

// This function is used to free wave struct.
// Params: wave_file
	
close_wave_file(wave_file);


```

## Requirements

* C-File-Manager [https://github.com/Kagetane-Hiruko/C-File-Manager]