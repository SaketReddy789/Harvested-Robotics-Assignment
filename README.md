🚜 Training Pipeline: High-Resolution Weed Segmentation
This folder contains the notebook used to train the YOLOv8n-seg model. Due to the high-resolution requirements (1280px) and GPU acceleration needs, this code is strictly optimized for the Kaggle environment.

⚠️ Environment Requirement: Kaggle
This notebook (.ipynb) utilizes internal Kaggle system paths (/kaggle/input/ and /kaggle/working/). Running this script in a local environment without modifying these paths will result in FileNotFound errors.

📂 Setup & Execution
Platform: Upload the provided .ipynb file to a new Kaggle Notebook.

Accelerator: Set the "Accelerator" to GPU T4 x2 (or Single T4).

Data Input: * Download the inputt dataset provided in the repository.

Upload this dataset to Kaggle under the name inputt.

Ensure the path is exactly: /kaggle/input/inputt.

Output: The model will save training logs and weights (best.pt) to /kaggle/working/runs/segment/train/weights/.
