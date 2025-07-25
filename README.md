# TSR Project

This repository contains code and resources for table structure recognition and related experiments.

## Project Structure

- Jupyter notebooks for experiments and model testing
- Configuration files for model parameters
- (Add your data, images, and other resources as needed)

## Setup Instructions

Follow these steps to set up the project and the Table Transformer dependency:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Create and activate a virtual environment (recommended)

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install project dependencies

If you have a `requirements.txt` file, run:

```bash
pip install -r requirements.txt
```

If you use Jupyter notebooks, install Jupyter:

```bash
pip install notebook
```

### 4. Set up Table Transformer

#### Option 1: Install via pip (if available)
If Table Transformer is available on PyPI:
```bash
pip install table-transformer
```

#### Option 2: Install from source (local folder)
If you have the Table Transformer source code in a subdirectory (e.g., `table-transformer/`):

```bash
cd table-transformer
pip install .
cd ..
```

Or, for development mode:
```bash
cd table-transformer
pip install -e .
cd ..
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 6. Add your data and images

Place your images and data files in appropriate folders. These are ignored by git as specified in `.gitignore`.

---

## Notes

- Update the `.gitignore` file as needed to exclude additional files or folders.
- For any additional dependencies, update `requirements.txt` and re-run the install command.
- For issues or questions, open an issue on the repository.
