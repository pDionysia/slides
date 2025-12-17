# First results of Experimental Data
Dionysia Petropoulou, 18/12/2025

---

# Frequency-Domain Analysis of Class-Specific Signal Patterns

![Histogram](figures/fft_spectrum.png)

--

![Histogram](figures/comparison_of_class_means.png)

--

![Histogram](figures/fft_samples.png)

---

# Multiclass Classification Results

We test 5 models:
- ROCKET (baseline)
- InceptionTime
- InceptionTimePlus
- ResNet 
- XceptionTime

Using 7 classes: <br>
0: clear, 1: Ethanol, 2: Acetamiprid 10ppb, 3: Acetamiprid 100ppb, 4: Acetamiprid 1000ppb, 5: Acetamiprid 10000ppb and 6: Acetamiprid 100000ppb

--

![Histogram](figures/mult_res.png)

---

# Binary Classification Results

We test the 5 models using 2 classes: <br>
0: clear, Ethanol, Ethanol, Acetamiprid 10ppb <br>
1: Acetamiprid 100ppb, Acetamiprid 1000ppb, Acetamiprid 10000ppb, Acetamiprid 100000ppb

--

![Histogram](figures/bin_res.png)



