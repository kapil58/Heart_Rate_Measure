
# Heart Monitor Library by Kapil



#### This library allows you to detect an irregular heart rate, find times where the user's heart is at risk and perform calculations around user specific heart rate data (MHR & THR).

## C++ Usage

```cpp
#include <kapil.h> 

// Link Library

int receive();

// Only needed if functions called before full declaration of receive()

irregularHeartRateCheck(receive(), 56); 

// Function: Attempts to find an irregular heart rate if the user is 56. 
// Return Style: Boolean (0 = No, 1 = Yes)
// Requires: A receive() Function Like Below
// Variables: The number 56 can be changed to the user's real age

riskCheck(receive(), 56);

// Function: Finds if the user's heart is at risk
// Return Style: Boolean (0 = No, 1 = Yes)
// Requires: A receive() Function Like Below
// Variables: The number 56 can be changed to the user's real age

maxHeartRate(56);

// Function: Finds the maximum heart rate
// Return Style: Integer
// Requires: None
// Variables: The number 56 can be changed to the user's real age

minTargetHeartRate(56);

// Function: Finds the minimum target heart rate
// Return Style: Integer
// Requires: None
// Variables: The number 56 can be changed to the user's real age

maxTargetHeartRate(56);

// Function: Finds the maximum target heart rate
// Return Style: Integer
// Requires: None
// Variables: The number 56 can be changed to the user's real age

int receive(){

   heartRate = // Insert Specific Way to Read BPM (ONLY CHANGE THIS LINE)

   return heartRate

}

```
## Python Usage

### Main File

```python

import Kapil

kapil.irregularHeartRateCheck(56) 

// Function: Attempts to find an irregular heart rate if the user is 56. 
// Return Style: Boolean (True or False)
// Requires: The Receive.py File Be Adapted
// Variables: The number 56 can be changed to the user's real age

kapil.riskCheck(56)

// Function: Finds if the user's heart is at risk
// Return Style: Boolean (True or False)
// Requires: The Receive.py File Be Adapted
// Variables: The number 56 can be changed to the user's real age

kapil.maxHeartRate(56)

// Function: Finds the maximum heart rate
// Return Style: Integer
// Requires: None
// Variables: The number 56 can be changed to the user's real age

kapil.minTargetHeartRate(56)

// Function: Finds the minimum target heart rate
// Return Style: Integer
// Requires: None
// Variables: The number 56 can be changed to the user's real age

kapil.maxTargetHeartRate(56)

// Function: Finds the maximum target heart rate
// Return Style: Integer
// Requires: None
// Variables: The number 56 can be changed to the user's real age

```

### Recieve.py File

```python

def r():

  heartrate = # Place Specfic Code On How to Get Heart Rate For Your Certain Device
  
  return heartrate

```

