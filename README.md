
### 🧪 Research Context

These simulations were carried out as part of my PhD research. The results were obtained using stabilized Navier–Stokes and hyperelastic solvers that I developed and implemented within the `Octolib` library. This numerical framework was specifically designed to handle challenging fluid–structure interaction (FSI) problems involving large deformations and nonlinear materials such as Neo-Hookean and Mooney–Rivlin models.

## 🌀 Flow Around a Cylinder – Rd= 3.15e5

| Velocity | Pressure |
|----------|----------|
| ![Velocity Rd= 3.15e5](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/V_2D_Rd3.15e5.gif) | ![Pressure Rd= 3.15e5](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/P_2D_Rd3.15e5.gif) |

## 🌀 Flow Around a Cylinder – Re = 250

| Velocity | Pressure |
|----------|----------|
| ![Velocity Re250](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/V_re250.gif) | ![Pressure Re250](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/P_re250.gif) |

## 🌀 Flow Around a Cylinder – Re = 10000

| Velocity | Pressure |
|----------|----------|
| ![Velocity Re1000](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/V_re1000.gif) | ![Pressure Re250](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/P_re1000.gif) |




## 🧩 Plane Strain Cook’s Membrane

| Geometry | u_y(m)|
|----------|-------------|
| ![Geometry – Cook’s Membrane](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/geometry.png) | ![Deformation – Cook’s Membrane](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/membrane.gif) |

**Description:**  
Neo-Hookean material with Young’s modulus **E = 250 Pa** and density **ρ = 1 kg/m³**.  
Initial traction: **t₀ = (0, 6.25) Pa**. Plane strain condition showing large deformation behavior.



## 🧩 3D Bending Beam – Mooney-Rivlin Material

| Geometry | u<sub>x</sub> (m) |
|----------|------------------|
| ![Geometry – Beam](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/Beam_geometry.png) | ![Deformation – Beam](https://raw.githubusercontent.com/rabdila/Flow-Around-a-Cylinde/main/assets/images/Beam3d.gif) |

**Description:**  
A 3D bending beam subjected to an initial velocity and displacement field:
- **Initial velocity**: **v₀(X, Y, Z) = (Z, 0, 0) m/s**
- **Initial displacement**: **u₀(X, Y, Z) = 0**

The material is modeled as **Mooney-Rivlin**, with parameters:
- Initial density: **ρ₀ = 1.1 × 10³ kg/m³**
- Mooney-Rivlin constants: **α₁ = 2.69 MPa**, **α₂ = 0.142 MPa**

The simulation illustrates large deformation and twist response of the beam under inertial loading.



