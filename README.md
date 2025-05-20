# Newton's Cradle Simscape Model (MATLAB 2024a)

This repository contains a **Simscape model of a Newton's Cradle**, implemented using **MATLAB R2024a** and above . The model simulates the dynamic behavior of a Newton's Cradle with realistic **frictional damping** using the **MATLAB Friction Library**.

## Preview


### ⚙️ Control Diagram
![System Model](images/image%201.png)

### 📌 Newton’s Cradle System Model
![Control Diagram](images/image%204.png)

## Features

- Built using MATLAB Simscape for realistic physics-based modeling
- Utilizes the MATLAB Friction Library to simulate joint and contact friction
- Customizable number of spheres, masses, and pendulum lengths
- Includes a control diagram for visualizing model logic and force transmission
- Compatible with **MATLAB R2024a** or later

## Requirements

- MATLAB R2024a
- Simscape and Simulink
- MATLAB Friction Library (available on File Exchange or MATLAB Add-On Explorer)

## File Structure

```
📁 NewtonsCradleSimscape
│
├── Newtons_Cradle.slx         # Simulink Simscape model
├── FrictionParams.m           # Friction parameters script
├── README.md                  # Project readme
└── images/
    ├── system_view.png        # Image of the cradle system
    └── control_diagram.png    # Image of the control diagram
```



## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/sployal/Newtons_cradle
   cd Newtons_cradle
   ```

2. Open MATLAB R2024a and run:
   ```matlab
   open('Newtons_Cradle.slx')
   ```

3. Run the simulation and observe the system behavior. You may adjust:
   - Mass
   - String length
   - Friction coefficients (in `FrictionParams.m`)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Davie — [@sployal](https://github.com/sployal)

---

*This simulation is for educational and research purposes. Contributions and feedback are welcome!*
