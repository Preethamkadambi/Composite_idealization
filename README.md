# 📘 Aircraft Structures: Laminated Composites Idealization

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](YOUR_STREAMLIT_APP_URL_HERE)

A digital companion application for the **Aircraft Structures** course (University of Liège). This interactive tool allows students and engineers to reproduce numerical examples and exercises regarding the idealization of laminated composite structures.

## 🚀 Live Demo
**[Click here to try the app live](YOUR_STREAMLIT_APP_URL_HERE)**

## 📊 Included Cases
The application covers 6 distinct cases with detailed, step-by-step validation against the lecture notes:

1.  **Micromechanics (Pg 27-30):** Homogenization of properties and structural response of a composite bar.
2.  **Bending (Pg 63-67):** Modified second moments of area and stress distribution in a Z-section.
3.  **Shearing (Pg 70-75):** Open shear flow, cut correction, and final flow in a closed trapezoidal section.
4.  **Torsion (Pg 77-80):** Shear flow and warping in a doubly symmetrical rectangular box.
5.  **Torsion (Pg 82-83):** Stiffness and stress analysis of an Open C-Section.
6.  **Exercise (Pg 84-89):** Full torsion analysis of an I-Section.

## ⚙️ Installation

To run this application locally:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/composite-idealization.git](https://github.com/YOUR_USERNAME/composite-idealization.git)
    cd composite-idealization
    ```

2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the app**
    ```bash
    streamlit run composite_cases.py
    ```

## 📝 Features
* **Formula Validation:** Renders LaTeX formulas for every step.
* **Page References:** Cites specific page numbers from the course PDF for every calculation.
* **Interactive Inputs:** Modify geometry and loads to see how results change.
* **Detailed Logging:** Displays intermediate values (e.g., $EI_{yy}$, $q_{open}$, Warping $u_x$) to facilitate hand-calc verification.

## 📄 License
This project is for educational purposes based on the "StructAeroCompositeIdealization" course notes.