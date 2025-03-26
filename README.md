# UX Researcher Agent with IBM Granite Models


This repository provides a complete implementation of the UX Researcher Agent (cupcake design) using IBM Granite Vision and Language Models. The agent autonomously evaluates user interface (UI) designs, delivering structured insights on usability, accessibility, clarity, and visual hierarchy.

![Implementation design]("User-2.png")

## Project Overview


The UX Researcher Agent leverages the power of the Granite 3.2 Vision and Language Models to rapidly and accurately analyze UI screenshots or mockups. It generates detailed, actionable feedback, significantly accelerating the UX validation process while ensuring complete privacy and security through local processing.


## Features


- **Vision-based UI component extraction:** Automatically identifies UI elements, their positions, colors, visibility, and labels.
- **Comprehensive UX analysis:** Evaluates designs based on usability, accessibility, clarity, and visual hierarchy.
- **Instant actionable feedback:** Provides clear, structured suggestions for immediate improvements.
- **Local and secure:** Processes all data locally, ensuring data privacy and compliance.


## Installation and Setup


Follow these steps to set up the project locally:


### Prerequisites


- [Ollama](https://ollama.com/download)
- Python 3.x


### Install Dependencies


```bash
pip install ollama gradio pillow easyocr opencv-python numpy
```


### Download Granite Models


```bash
ollama pull granite3.2
ollama pull granite3.2-vision
```


## Running the UX Researcher Agent


Launch the Gradio interface by executing the notebook:


```bash
jupyter notebook UX_Feedback_Agent_Granite.ipynb
```


In the opened notebook, run all cells. Gradio will provide a simple interface for uploading your UI images and receiving UX feedback.


## Usage


1. **Upload UI Design:** Use the Gradio interface to upload your UI screenshots.
2. **Receive Analysis:** Get structured, detailed UX feedback instantly.


See this [Blog here](https://medium.com/@khan.rafflesia/building-a-ux-researcher-agent-with-ibm-granite-model-f071ab73d793) for more details 



