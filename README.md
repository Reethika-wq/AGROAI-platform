### AGROAI: Intelligence-Driven Agricultural Suite
**Empowering Farmers with AI-Powered Vision**

---

#### 🔗 Quick Access
*   **Main Platform:** [agroai-platform.netlify.app](https://agroai-platform.netlify.app/)
*   **Pest Module (Live):** [pest-detection-ai.streamlit.app](https://pest-detection-ai.streamlit.app/)
*   **Plant Module (Live):** [plant--diseased-ai.streamlit.app](https://plant--diseased-ai.streamlit.app/)

---

### 📖 About the Project
AGROAI is an integrated Artificial Intelligence ecosystem designed to solve two of the biggest challenges in modern farming: **Crop Disease** and **Pest Infestations**. 

Globally, farmers lose up to 40% of their crops to pests and diseases annually. AGROAI provides an instant, "expert-in-your-pocket" solution that identifies these threats in seconds using only a smartphone camera.

---

### 🔍 Detailed Module Explanation

#### 1. Intelligence-Driven Pest Management (PestIdentify AI)
**The Problem:** Farmers often use "broad-spectrum" pesticides, killing both harmful pests and beneficial insects (like bees). This is expensive and bad for the environment.

**The Solution:** This module uses a **PyTorch-based Deep Learning model** (built with `timm` and `torchvision`) to identify specific pest species. 
*   **Intelligence-Driven:** By knowing the exact pest, farmers can use "targeted" treatment, reducing chemical use by up to 60%.
*   **Data Source:** Trained on high-resolution entomological datasets to distinguish between similar-looking insects.

#### 2. PhytoSense AI (Plant Disease Detection)
**The Problem:** Early-stage plant diseases are often invisible to the human eye. By the time a farmer notices a yellow leaf, the whole field might be infected.

**The Solution:** Using **TensorFlow and Keras**, this module analyzes leaf pathology (patterns, spots, and colors) to detect 38 different types of healthy and diseased states.
*   **Early Detection:** Identifies microscopic markers of fungal, bacterial, and viral infections.
*   **Sustainable Yield:** Helps in isolating infected plants early to save the rest of the harvest.

---

### ⚙️ How the Project Works (Technical Workflow)

1.  **Image Acquisition:** The user captures a photo of a leaf or insect via the Streamlit interface.
2.  **Preprocessing:** Using **OpenCV** and **Pillow**, the image is resized, normalized, and converted into a numerical tensor.
3.  **Neural Inference:** 
    *   The **Pest Module** runs the image through a PyTorch model.
    *   The **Plant Module** runs the image through a TensorFlow/Keras CNN (Convolutional Neural Network).


---

### 📂 Repository Access & Data
You do **not** need to download data to use the live apps. However, if you wish to see the source code, models, or datasets, they are hosted here:

*   **Pest Repository:** [Reethika-wq/Intelligence-Driven-Pest-Management](https://github.com/Reethika-wq/Intelligence-Driven-Pest-Management)
*   **Plant Repository:** [Reethika-wq/PhytoSense-AI](https://github.com/Reethika-wq/PhytoSense-AI)

