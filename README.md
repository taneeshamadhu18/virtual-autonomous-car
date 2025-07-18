# 🚗 Virtual Autonomous Car (VAC)

An AI-powered simulation of a self-driving car that can detect lanes, recognize objects, explain its driving decisions using traffic rules, and interact via a natural language interface.

---

## 📦 Features

| Module | Description |
|--------|-------------|
| 🛣️ **Lane Detection** | Detects lane markings using OpenCV (Canny + Hough Transform). |
| 🚦 **Object Detection** | Detects pedestrians, vehicles, and signals using YOLOv8. |
| 🧠 **Decision Engine** | Applies rules to decide actions (e.g., brake if pedestrian detected). |
| 📚 **RAG Assistant** | Uses LangChain + ChromaDB to answer questions about the trip using traffic rules and logs. |
| 🧾 **Trip Logger** | Logs lane loss, detected objects, and system actions to CSV. |
| 🖼️ **Gradio Dashboard** | Upload videos, preview detection, and ask questions like “Why did the car slow down?” |

---

## 🧠 Tech Stack

- **Python**, **OpenCV**, **YOLOv8**
- **LangChain** + **ChromaDB**
- **Gradio** for interactive UI
- **Google Colab** for rapid prototyping
- Optional: **Streamlit** or **HuggingFace Spaces** for deployment

---

## 🚀 Quick Start (Colab Recommended)

1. Clone the repo or open in Google Colab.
2. Upload a driving video (e.g., `solidWhiteRight.mp4`)
3. Run detection cells to generate outputs.
4. Launch the Gradio interface to:
   - Preview processed frames
   - Upload custom videos
   - Ask natural language questions about decisions

---

## 🤖 Example Questions You Can Ask

- *Why did the car slow down between frame 30–60?*
- *Was any pedestrian detected during the trip?*
- *Did the car lose lane tracking at any point?*

---

## 📂 Project Structure

