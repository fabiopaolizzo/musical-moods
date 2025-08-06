# MUSICAL-MOODS: A Large-Scale Multimodal Dataset for AI

This repository is the central hub for the MUSICAL-MOODS dataset, a foundational resource for training and validating AI models on complex, subjective, and unstructured human data. This work is directly applicable to building the robust, scalable algorithms required for analyzing unstructured data.

The dataset was engineered as the primary outcome of my Marie Skłodowska-Curie Global Fellowship at the University of California, Irvine, and the University of Rome Tor Vergata.

---

### Dataset Components

The full dataset comprises over 10 hours of multimodal acquisitions from dance improvisations. The data is organized into the following repositories, each containing a distinct data modality:

-   **[Language Data](https://github.com/fabiopaolizzo/musical-moods.language):** Transcripts and NLP-ready text from post-session interviews, providing the "ground truth" for the subjective experiences being modeled.

-   **[Audio Data](https://github.com/fabiopaolizzo/musical-moods.audio):** Processed audio files (44.1kHz, 320kbps MP3) from the interactive music system, representing a complex and noisy time-series data source.

-   **[Motion Capture (MoCap) Data](https://github.com/fabiopaolizzo/musical-moods.mocap):** High-dimensional, vector-based time-series data captured with an industry-standard 53-marker Vicon system.

-   **[Video Data](https://github.com/fabiopaolizzo/musical-moods.video):** Video recordings (640x360) captured in a green screen environment, serving as the qualitative ground truth and validation reference for the MoCap data.

---

### Core Research Problem & Capabilities

This project was designed to solve a core challenge in modern AI: training predictive models on noisy, high-dimensional data that reflects nuanced human emotional and cognitive states. The work established a foundational methodology for:

-   **Time-Series Analysis:** Analyzing complex, high-dimensional, and noisy time-series data to identify emergent patterns and behaviors.

-   **Representation Learning:** Developing robust, multi-modal representations from disparate and unstructured data streams (language, video, sensor data).

-   **Behavioral & Sentiment Modeling:** Building predictive models to classify and forecast nuanced human emotional and cognitive states from data.

-   **Cross-Modal Data Fusion:** Fusing different data types into a single, coherent analytical framework to create a more accurate and holistic model.

---

*This research was supported by the EU's Horizon 2020 programme (MSCA-IF-GF, REA Grant Agreement No. 659434).*```
