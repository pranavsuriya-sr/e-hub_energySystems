# ⚡ Energy Systems Analysis & Visualization

A comprehensive Python-based web application developed using Streamlit, this project provides tools for analysis and visualization in energy systems. The website includes modules for power and impedance triangle plotting, circuit solving, phase diagram visualization, and more, making it a valuable resource for students and professionals in energy systems.

## 📜 Abstract

This project presents a web application with four distinct solvers to analyze and visualize energy systems:
- **Power and Impedance Triangle Plotter**: Visualizes key parameters in AC circuits through power and impedance triangles.
- **Circuit Solver and Visualizer**: Allows analysis and computation of electrical circuits with various components.
- **Phasor Diagram Plotter**: Provides visualizations of phase diagrams for short transmission lines.
  
The user-friendly interface of Streamlit enhances accessibility, making these analytical tools practical and efficient.

## 🌟 Features

1. **Power and Impedance Triangle Plotter**:
   - Users input voltage, current, and phase angle values to visualize power and impedance triangles.
   - Functions:
     - `calculate_power_triangle`: Calculates real, reactive, and apparent power.
     - `calculate_imped_triangle`: Calculates impedance triangle components.
     - `plot_power_triangle` and `plot_imped_triangle`: Display power and impedance triangles.

2. **Circuit Solver and Visualizer**:
   - Enables users to design circuits with resistors, capacitors, and inductors, and visualize total impedance and current.
   - Functions:
     - `draw_circuit`: Uses schemdraw to create circuit diagrams.
     - `calculate_imped`: Calculates impedance based on component types and values.

3. **Phasor Diagram Plotter for Short Transmission Lines**:
   - Users can input transmission line parameters to visualize phasors for sending and receiving voltage, line and load currents.
   - Ideal for understanding short transmission line behavior and optimizing configurations.

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**: `matplotlib`, `numpy`, `schemdraw` for plotting and calculations

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/pranavsuriya-sr/projES.git
   cd projES
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run app.py
   ```

## 🎨 Modules Overview

### Power and Impedance Triangle Plotter
- Provides a visual representation of AC circuit relationships.
- Users input voltage, current, and phase angle values to generate power and impedance triangles.

### Circuit Solver and Visualizer
- Analyzes electrical circuits with selected components and displays total impedance and current.
- Interactive component configuration enhances learning and experimentation.

### Phasor Diagram Plotter for Short Transmission Lines
- Specialized for analyzing short transmission lines with phasor diagrams.
- Visualizes phase relationships for optimized transmission line configurations.


## 🌐 Live Demo

- [GitHub Repository](https://github.com/pranavsuriya-sr/projES)
- [Web Application](https://energysystems-pranavsuriya.streamlit.app/)

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For questions or feedback, feel free to reach out to [Pranavsuriya](https://github.com/pranavsuriya-sr) on GitHub.

---

<div align="center">
  Made with ❤️ by [Pranavsuriya](https://github.com/pranavsuriya-sr)
</div>
