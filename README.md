# Basic Statistics Notes
### **Trimean**
**Dataset:** 10, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 50

**Solution:**

**1. Sort the dataset**
- As the dataset is already sorted, this step can be skipped.
10, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 50

**2. Find the median**
- The median is the value in the center, if the dataset is even, the mean of the two center values will be the median.
- In this case the median is 30.

10, 12, 15, 18, 21, 24, 27, **30**, 33, 36, 39, 42, 45, 48, 50

**3. Find the Q1 & Q3**

- Q1 is found by getting the median of each quartile.

Q1: 10, 12, 15, **18**, 21, 24, 27

Q3: 33, 36, 39, **42**, 45, 48, 50

**4. Calculate the trimean**

![](image-1.png)

Answer: 30

### **Geometric Mean**

**Growth Rate Dataset:**

- Year 1: +5%
- Year 2: +10%
- Year 3: -3%
- Year 4: +6%

**Solution:**

**1. Convert to growth factors**

- Year 1 = 1.05
- Year 2 = 1.10
- Year 3 = 0.97
- Year 4 = 1.06

**2. Calculate product of growth factors**

1.05 x 1.10 x 0.97 x 1.06 = 1.181841

**3. Calculate geometric mean**

![](image-2.png)

Answer = 1.0426

**4. Convert to percentage**

1.0426 - 1 = 0.0426

Percentage = 4.26%

### **Trimmed Mean**

**Dataset:**
65, 70, 72, 75, 80, 85, 90, 92, 95, 100

**Trim:**
10%

**1. Sort dataset**

- The dataset is already sorted.

65, 70, 72, 75, 80, 85, 90, 92, 95, 100

**2. Trim dataset**

- Since the trim is 10%, we have to trim 10% off each end of the dataset.

- As the dataset consists of 10 values, the trim will be 1 off each side.

70, 72, 75, 80, 85, 90, 92, 95

**3. Calculate Mean**

- Get the mean of the trimmed dataset.

![](image-3.png)

Answer = 82.375
