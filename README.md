# ITAI 3377 Portfolio – Win Aung

Welcome to my portfolio for the course **ITAI 3377: AI for Edge and IIoT Systems**. This repository includes all assignments, labs, presentations, and reflections completed during the course.

## 📂 Repository Structure


---

## 🔍 Highlights

- **Edge AI Deployment** using TensorFlow Lite and Edge Impulse (Module 2 & 6)
- **IIoT Forecasting** using Nixtla AutoML and synthetic data (Module 6)
- **Real-Time AI** analysis using AoI and ML modeling (Module 7)
- **Predictive AI Storytelling** and robot ethics case studies (Modules 12 & 13)
- **Git-based Workflow** across all projects

---

## 🎥 Presentation

Final summary presentation:  
[Pf_Win_Aung_ITAI3377.pdf]()

---

## 🔗 External Resources

- [Nixtla GitHub](https://github.com/Nixtla)
- [TensorFlow Lite](https://www.tensorflow.org/lite)
- [Edge Impulse Docs](https://docs.edgeimpulse.com)
- [Minority Report (Film)](https://www.imdb.com/title/tt0181689/)
- [Smart City Case Study - Liverpool Traffic](https://arxiv.org/abs/2311.13336)

---

## 🖤 Converting Notebooks to Black & White

Some reports require grayscale images and plots for clear printing. Jupyter's
extension system makes it easy to convert all notebook outputs to black and
white.

1. **Install the nbextension tools**:
   ```bash
   pip install jupyter_contrib_nbextensions jupyter_nbextensions_configurator
   jupyter contrib nbextension install --user
   jupyter nbextensions_configurator enable --user
   ```
2. **Create a grayscale extension** by adding the following CSS to a file
   named `bw.css`:
   ```css
   img, svg { filter: grayscale(100%); }
   ```
3. **Install and enable the extension**:
   ```bash
   jupyter nbextension install bw.css --user --destination bw
   jupyter nbextension enable bw/main
   ```

Once enabled, any notebook opened in Jupyter will display plots and images in
grayscale, allowing consistent black‑and‑white exports.

---

## 👨‍💻 Author

**Win Aung**  
Houston Community College  
Course: ITAI 3377 – AI for Edge and IIoT Systems

---
