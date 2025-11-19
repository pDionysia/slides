# Experimental Data Presentation
Dionysia Petropoulou, 2025

---

# THz Experimental Setup

![Histogram](figures/exp_setup.png)

--

![Histogram](figures/wafer.png)

---

## PART A — CHEMICAL MEASUREMENTS (Bare Si Wafer)

Measurement Plan (Chemicals Only):

- Chemicals: Ethanol, Metalaxyl, Acetamiprid, Abamectin

- Concentrations: 10 ppb → 100000 ppb

- 5 measurements per concentration

---

# Data Format

![Histogram](figures/data_format.png)

--

- Time delay → when each part of the pulse arrives
- THz electric field → how strong the pulse is at that moment

Together, they give the full time-domain waveform, which contains all the information about:

- the sample

- the chemicals

- the SRRs

- how they modify the THz wave

---

# Ethanol vs Acetamiprid 100000ppb (5 measurements)
# Chemical Measurements – Time Domain

<img src="figures/17_10_25-ethanol.png" 
     style="width:75%; max-height:350px; display:block; margin:0 auto 20px;">

<img src="figures/17_10_25_Acetamiprid_100000ppb.png" 
     style="width:75%; max-height:350px; display:block; margin:auto;">


---

## PART B — METAMATERIAL MEASUREMENTS (SRRs)

- SRRs: tiny metal rings with a gap
- They behave like small antennas that have a specific resonant frequency in the THz range

- When something changes around them (like a chemical being deposited ) their resonance shifts, and we can measure that

--

![Histogram](figures/wafer_2.png)

---

## SRR Results – clear vs ethanol

<div style="display: flex; justify-content: space-around;">

  <div style="width: 75%;">
    <h4>SRRs clear – Time Domain</h4>
    <img src="figures/SRRs_clear.png" style="width: 100%;">
  </div>

  <div style="width: 75%;">
    <h4>SRRs ethanol – Time Domain</h4>
    <img src="figures/SRRs_ETHANOL.png" style="width: 100%;">
  </div>

</div>

--

<div style="display: flex; justify-content: space-around;">

  <div style="width: 75%;">
    <h4>SRRs clear – FFT</h4>
    <img src="figures/SRRs_clear_FFT.png" style="width: 100%;">
  </div>

  <div style="width: 75%;">
    <h4>SRRs ethanol – FFT</h4>
    <img src="figures/SRRs_ETHANOL_FFT.png" style="width: 100%;">
  </div>

</div>

---

# SRR with 10ppb and 100 ppb of Acetamiprid

<div style="display: flex; justify-content: space-around;">

  <div style="width: 75%;">
    <h4>SRRs 10ppb – Time Domain</h4>
    <img src="figures/SRRs_10ppb_Acetamiprid.png" style="width: 100%;">
  </div>

  <div style="width: 75%;">
    <h4>SRRs 100ppb – Time Domain</h4>
    <img src="figures/SRRs_100ppb_Acetamiprid.png" style="width: 100%;">
  </div>

</div>

--

<div style="display: flex; justify-content: space-around;">

  <div style="width: 75%;">
    <h4>SRRs 10ppb – FFT</h4>
    <img src="figures/SRRs_10ppb_Acetamiprid_FFT.png" style="width: 100%;">
  </div>

  <div style="width: 75%;">
    <h4>SRRs 100ppb – FFT</h4>
    <img src="figures/SRRs_100ppb_Acetamiprid_FFT.png" style="width: 100%;">
  </div>

</div>

---

# Summary / Conclusions

- Time-domain signals look similar because chemical layer is thin

- SRRs show clear resonance in FFT

- Ethanol and acetamiprid shift the resonance

- SRRs → excellent THz sensors

---

### Thank you!









