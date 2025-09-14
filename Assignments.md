# Assignment : Battery Parameter

### **Problem 1**
**Question:** A 34 kWh battery is charged at SoC of 64%. What is the energy it contains?

To find the energy contained in the battery, you need to calculate 64% of its total capacity.
* **Total Capacity:** 34 kWh
* **State of Charge (SoC):** 64% or 0.64

**Calculation:**
Energy = Total Capacity × SoC
Energy = 34 kWh × 0.64
Energy = **21.76 kWh**

---

### **Problem 2**
**Question:** A 34 kWh capacity battery is voltage 350V. What is its capacity in Ah?

To convert from kilowatt-hours (kWh) to ampere-hours (Ah), you can use the formula that relates energy, voltage, and current over time.

**Formula:**
Energy (Wh) = Voltage (V) × Capacity (Ah)

First, convert the energy from kWh to Wh:
* 34 kWh = 34 × 1000 = **34,000 Wh**

Now, rearrange the formula to solve for Capacity (Ah):
Capacity (Ah) = Energy (Wh) / Voltage (V)
Capacity (Ah) = 34,000 Wh / 350 V
Capacity (Ah) ≈ **97.14 Ah**

---

### **Problem 3**
**Question:** A 3.5V battery is at 2.7V at SoC of 0% and 4.3V at SoC of 100%. This implies the voltage of the battery lies in between 3.5 ± $\Delta$% volts. What is $\Delta$?

This question asks for the percentage variation ($\Delta$) from the nominal voltage of 3.5V. The range of the battery's voltage is from 2.7V to 4.3V. The nominal voltage (3.5V) should be the center of this range for the statement to be true. Let's find the average voltage and the deviation.

**Step 1:** Find the range of the voltage.
Range = Max Voltage - Min Voltage
Range = 4.3 V - 2.7 V = 1.6 V

**Step 2:** Find the average voltage.
Average Voltage = (Max Voltage + Min Voltage) / 2
Average Voltage = (4.3 V + 2.7 V) / 2 = 7.0 V / 2 = 3.5 V
This confirms that 3.5V is the nominal voltage.

**Step 3:** Calculate the maximum deviation from the nominal voltage.
Deviation = Max Voltage - Nominal Voltage
Deviation = 4.3 V - 3.5 V = 0.8 V
Alternatively, Deviation = Nominal Voltage - Min Voltage = 3.5 V - 2.7 V = 0.8 V

**Step 4:** Convert this deviation to a percentage of the nominal voltage.
$\Delta$ = (Deviation / Nominal Voltage) × 100%
$\Delta$ = (0.8 V / 3.5 V) × 100%
$\Delta$ ≈ **22.86%**

---

### **Problem 4**
**Question:** Assuming SoC is a linear function of voltage, what is (a) SoC at 4V and (b) voltage at SoC of 64%?

Using the information from the previous problem, we have a linear relationship between voltage and SoC.
* SoC = 0% at 2.7V
* SoC = 100% at 4.3V

The relationship can be expressed as a linear equation:
$SoC(V) = m \times V + c$
where $m$ is the slope and $c$ is the y-intercept.

**Step 1: Find the slope ($m$)**
$m = \frac{\Delta SoC}{\Delta V} = \frac{100\% - 0\%}{4.3 V - 2.7 V} = \frac{100\%}{1.6 V} = 62.5\% / V$

**Step 2: Find the y-intercept ($c$)**
Using the point (2.7V, 0% SoC):
$0 = (62.5 \times 2.7) + c$
$0 = 168.75 + c$
$c = -168.75$

So the full equation is:
$SoC(V) = 62.5 \times V - 168.75$

**Part (a): Find SoC at 4V**
$SoC(4V) = (62.5 \times 4) - 168.75$
$SoC(4V) = 250 - 168.75$
$SoC(4V) = **81.25%**$

**Part (b): Find voltage at SoC of 64%**
Rearrange the equation to solve for V:
$SoC + 168.75 = 62.5 \times V$
$V = (SoC + 168.75) / 62.5$

$V = (64 + 168.75) / 62.5$
$V = 232.75 / 62.5$
$V = **3.724 V**$

---

### **Problem 5**
**Question:** Petrol volumetric Energy Density in kWh/l and gravitational in kWh/kg

The volumetric and gravimetric energy densities of gasoline (petrol) are standard values. The provided question likely asks for these specific values. 
* **Volumetric Energy Density:** This measures energy per unit volume. For petrol, a common approximate value is **9.7 kWh/l** (or 32 MJ/l).

* **Gravimetric Energy Density:** This measures energy per unit mass. For petrol, a common approximate value is **12.1 kWh/kg** (or 43.5 MJ/kg).

---

### **Problem 6**
**Question:** Coal volumetric Energy Density in kWh/l and gravitational in kWh/kg

Similar to the previous question, these are standard values for coal. The energy density of coal varies significantly depending on its type and quality (e.g., anthracite, bituminous). We'll use a representative range.

* **Volumetric Energy Density:** This can be highly variable due to the different densities of various coal types. A typical range for coal is **5 to 9 kWh/l**.

* **Gravimetric Energy Density:** This also varies with the type of coal, but a common range is **6 to 8 kWh/kg**.
