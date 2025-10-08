# Dataset_Preprocessing
A pipeline for preparing image datasets: includes visualization, renaming, resizing, train/validation/test split, augmentation, and denoising.

# Tree Structure

```
dataset_root/
├── 🖥️ Step 1: Setup Environment
│   ├── 📂 Mount Google Drive
│   └── 📚 Import Required Libraries
├── 📌 Step 2: Visualize Original Dataset
│   ├── 📂 Root Folder & Subfolders
│   ├── 🔹 Count Images
│   ├── 📊 Visualize Distribution
│   ├── 🔹 Rename Images
│   └── 🔄 Resize Images
├── 📌 Step 3: Split Dataset into Train, Validation, and Test
│   ├── 📂 train/
│   │   ├── class_1/
│   │   └── class_2/
│   ├── 📂 validation/
│   │   ├── class_1/
│   │   └── class_2/
│   └── 📂 test/
│       ├── class_1/
│       └── class_2/
├── 📌 Step 4: Augment Training Data
│   ├── 🔄 Apply Augmentations
│   └── 📊 Visualize Distribution
├── 📌 Step 5: Comparison Section
│   └── 🔹 Compare Counts
└── 📌 Step 6: Denoise Training Data Only
    ├── 🧹 Denoising Filters
    ├── 💾 Save Images
    └── 📊 Visualize Distribution
```
