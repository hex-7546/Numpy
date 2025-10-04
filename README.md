# Numpy

## Importing numoy library
```
import numpy as np
import warnings
warnings.filterwarnings("ignore")
from IPython.display import Image
```
## Creating array
```
list1 = [10,20,30,40,50,60]
list1
```
<img width="181" height="29" alt="image" src="https://github.com/user-attachments/assets/76d32ab1-acc3-4a0d-ade1-4f24943edccf" />

## Displaying type of object
```
type(list1)
```
<img width="41" height="25" alt="image" src="https://github.com/user-attachments/assets/99da202b-8618-478d-9f7f-2a67c2ba69bb" />

## Converting list to Numpy array
```
#Convert list to Numpy Array
arr1 = np.array(list1)
arr1
```
<img width="228" height="28" alt="image" src="https://github.com/user-attachments/assets/61f10b81-9068-43f7-8f22-fa42dda8fd9b" />

## Memory address of array object
```
arr1.data
```
<img width="193" height="32" alt="image" src="https://github.com/user-attachments/assets/b54a9a11-48a9-4f4f-8ba2-a862a2495702" />

## Type of object
```
type(arr1)
```
<img width="102" height="24" alt="image" src="https://github.com/user-attachments/assets/7829762a-9d4c-418b-896c-b66d981c2b8d" />

## Datatype of array
```
arr1.dtype
```
<img width="111" height="27" alt="image" src="https://github.com/user-attachments/assets/99623f28-7e86-48be-923e-ccb44a4df509" />

## Converting integer array to float
```
arr1.astype(float)
```
<img width="272" height="27" alt="image" src="https://github.com/user-attachments/assets/15e2e846-929d-46e4-8e9b-9d9f8a917b58" />

## Generate numbers till 100 with spaces of 10
```
np.arange(0,100,10)
```
<img width="338" height="28" alt="image" src="https://github.com/user-attachments/assets/adc9dcaf-5ac9-4d45-8355-a6953f9e669d" />

## Repeat a number in the array
```
np.repeat(10, 5)
```
<img width="188" height="25" alt="image" src="https://github.com/user-attachments/assets/b04c3ca4-edbe-4974-9c0a-f243873df626" />

## Array of random numbers
```
np.random.randint(0,500,10)
```
<img width="407" height="30" alt="image" src="https://github.com/user-attachments/assets/380344df-66e7-4aba-8b2b-05be65c1b1c7" />

## Operations on Array
```
arr2 = np.arange(1,20)
arr2
```

<img width="525" height="44" alt="image" src="https://github.com/user-attachments/assets/94a59c16-8126-4549-91d1-3c531d0bbfa5" />


### Sum of all elements
```
arr2.sum()
```
<img width="106" height="28" alt="image" src="https://github.com/user-attachments/assets/781fed75-dd53-4a4a-af16-c13c3aa5d6e2" />

### Cumulative sum
```
np.cumsum(arr2)
```
<img width="503" height="45" alt="image" src="https://github.com/user-attachments/assets/5c30abd5-5bd0-4886-833c-f42d8c23f564" />

### Finding min number
```
arr2.min()
```
<img width="85" height="31" alt="image" src="https://github.com/user-attachments/assets/2c6e2306-f7f2-4300-bf54-893f47708267" />

### Finding max number
```
arr2.max()
```
<img width="90" height="34" alt="image" src="https://github.com/user-attachments/assets/695edb90-f565-4d08-ac43-dec712abd620" />

### Finding mean of all numbers in an array
```
arr.mean()
```
<img width="116" height="28" alt="image" src="https://github.com/user-attachments/assets/022788a9-7350-4635-be07-b22675800699" />

### Finding median of all numbers in an array
```
np.median(arr2)
```
<img width="119" height="32" alt="image" src="https://github.com/user-attachments/assets/caadcbff-f0ac-44c9-bf58-3a8e94d68fa4" />

### Finding variance 
```
np.var(arr2)
```
<img width="120" height="32" alt="image" src="https://github.com/user-attachments/assets/fa1a77f3-669f-41e9-85e4-b183a439950c" />

### Finding standard deviation
```
np.std(arr2)
```
<img width="209" height="32" alt="image" src="https://github.com/user-attachments/assets/b96ff353-a6f3-4b84-87bc-d5b72e392d12" />
