# Electric Field Simulation

This Python project visualizes the **electric field produced by multiple point charges** in a 2D plane using the **superposition principle**. It provides both **vector plots** and **field lines** to help understand electric field behavior in classical electrostatics.

---

## **Features**
- Supports **any number of point charges** with customizable positions and magnitudes.
- Visualizes **electric field vectors** (quiver plot) for direction and magnitude.
- Displays **electric field lines** (streamplot) for intuitive field visualization.
- Positive charges are marked in **red**, negative charges in **blue**.

---

## **Physics Concepts**
- **Coulomb’s Law:** 
\[
\mathbf{F} = k \frac{q_1 q_2}{r^2} \hat{\mathbf{r}}
\]  
- **Electric Field of a Point Charge:** 
\[
\mathbf{E} = k \frac{q}{r^2} \hat{\mathbf{r}}
\]  
- **Superposition Principle:** The net electric field is the vector sum of individual fields.

---

## **Getting Started**

### **Prerequisites**
- Python 3.x
- Required libraries (install via pip):
```bash
pip install numpy matplotlib
