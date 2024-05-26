# Underfrequency Load Shedding Implementation in PSSE

## Uploaded file's overview is here 🗂️[Project Structure](#project-structure)

## Abstract

Underfrequency Load Shedding (UFLS) is a critical mechanism in power systems to prevent widespread blackouts by shedding loads when the frequency drops below a certain threshold. This project focuses on implementing UFLS using Power System Simulation (PSS/E).

### Objectives:
1. **Selection of Buses**: Identify buses susceptible to underfrequency events through QV analysis.
2. **Load Flow Analysis**: Utilize the Newton-Raphson method to assess system stability and determine the optimal load shedding strategy.

### Methodology:
- **QV Analysis**: Identifies vulnerable buses where load shedding can be most effective during underfrequency conditions.
- **Newton-Raphson Load Flow Analysis**: Evaluates the steady-state behavior of the power system, aiding in understanding operating conditions under different load scenarios.

### Implementation:
- **UFLS Strategies in PSS/E**: Simulate various underfrequency scenarios and assess their impact on system stability. Strategic load shedding at predetermined buses helps mitigate the risk of widespread blackouts, ensuring reliability and resilience of the power grid.

### Contribution:
This project advances underfrequency protection techniques and provides insights into the application of PSS/E for real-time system analysis and decision-making. The findings assist power system operators and engineers in developing effective UFLS schemes to enhance grid resilience and minimize the impact of underfrequency events.

## Evaluation

The Automatic Under Frequency Load Shedding scheme has seen significant improvements, particularly in:
- **Frequency Nadir**
- **Rate of Change of Frequency (ROCOF)**

These advancements contribute to the overall effectiveness and efficiency of the scheme, ensuring a more reliable and robust power system.

## Project Structure

### 📁 Uploaded Folders:

1. **1.IEEE24_jconto_bus_system**: Contains the following files:
    - `sav` files: Save case files for the 24-bus system.
    - `dyr` files: Dynamics data files.
    - 📄 Documentation: Detailed documentation of the 24-bus system.

2. **2.IEEE24_abnormal**: Contains files for abnormal conditions, including:
    - `sav` files: Save case files under abnormal conditions.
    - `dyr` files: Dynamics data files under abnormal conditions.
    - `out` files: Output files.
    - `xlsx` files: Excel files with data and results.
    - 📝 `abnormal.py`: Script for automating abnormal condition scenarios.

3. **3.IEEE24_loadshedding**: Contains files for post-load shedding scenarios, including:
    - `sav` files: Save case files after load shedding.
    - `dyr` files: Dynamics data files after load shedding.
    - `out` files: Output files.
    - `xlsx` files: Excel files with data and results.
    - 📝 `loadshedding.py`: Script for automating load shedding scenarios.

### 📑 Project Report

- **Under Frequency Load Shedding Implementation.pdf**: Contains the detailed project report.



## Notes

**PSSE Limitations**: While PSSE is utilized for this project, it may not be the most beginner-friendly software due to limited tutorials and only documentation available online. Alternatives like Simulink, PowerWorld, and DIgSILENT PowerFactory are recommended for easier power system modeling and analysis.

## Let's Connect!

Feel free to reach out to me on [GitHub](https://github.com/JubayerONROB) or [LinkedIn](https://www.linkedin.com/in/a-j-a-jubayer-talukder-a601b924b).

---

Thank you for visiting my GitHub! Looking forward to connecting and creating something amazing together! 🚀

