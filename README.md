# Neural-Analytic-and-Visualization-Tool
## Goal
Neural Analytic Algorithm (NAT-v) is a set of tools that is designed for "analytic" and "visualization". Beacuse we don't know what Matlab's operation or other nonopen-source tool, we build our toolbox.

## Environment
- Anaconda, Python 3.8.5

## Install
Python is a widely used language. So we build a set of python-function. 
Just copy and paste at the folder same as you python code.

For example, I want use 'car'

```python
from .car import car
.
.
.
```
Then, you have 'car'.


## Demo
- Common Average reference (CAR)
![](https://lh4.googleusercontent.com/imFx8xTZiOx-cmFbV50i8NubrDtSxEgZWxyxaWyyftO_CgNpQDpnYB4KIpmIe0gPFbw8OmgmemvTWX8JEuWYO8Nwg_ty2JnZyHp1zkYxa2qahND-rFehBspuwyLCJRes0H1s66uB)

- Independent Components Analysis (ICA)
![](https://i.imgur.com/mFE9lI0.png)

- Hilbert Huang Transform (HHT)
![](https://i.imgur.com/RflMVU1.png)

- Low-pass filter
![](https://lh5.googleusercontent.com/BRPQ4L1ZZJk7Y9w52JfCb4cd99K02oUCY-EqTBhyM7FlYU68AywtE2RfnciexIgl3X7TyaBmh3GMvcYWXsjCVf67eOz5j6GZQx_xDP9RKJc2RbyMBRqRX0sH72-jkW40TOW6UyyM)

- Topograph Draw

![](https://i.imgur.com/eNcGFJ9.png)

## Definition
output = car(intput)
- input and output is two dim numpy array, channel_number x Time_bin_number.

output = ica(input, n)
- input is two dim numpy array, channel_number x Time_bin_number.
- output is two dim numpy array, n x Time_bin_number.
- n is the number of independent signal channel at output. If no assigmant n = channel_number


