# Invisibility Cloak using OpenCV (Green Cloth)

A simple **Computer Vision student project** that creates an invisibility effect by detecting a **green-colored cloth** and replacing it with the captured background using **Python and OpenCV**.

---

## How It Works
- Captures a **static background frame**.
- Converts each frame to **HSV color space**.
- Detects the **green color region** using masking.
- Replaces the green region with background pixels using **bitwise operations**.

---

## Known Limitations
- Does not work well on **shiny or reflective surfaces**.
- Detection becomes unstable under **strong or changing lighting**.
- Poor performance when the background color is **similar to green**.

---

## Installation
```bash
pip install -r requirements.txt
