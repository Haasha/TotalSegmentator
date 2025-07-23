# Quickstart Guide for TotalSegmentator Setup

Follow these steps to set up your environment from scratch:

1. **Create a new Conda environment**

   ```bash
   conda create --name total-seg python
   ```

2. **Activate the environment**

   ```bash
   conda activate total-seg
   ```

3. **Navigate to the TotalSegmentator directory**

   ```bash
   cd TotalSegmentator
   ```

4. **Install TotalSegmentator in editable mode**

   ```bash
   pip install -e .
   ```

5. **Check if following versions throw some error**

   ```bash
   blosc2==2.5.1
   dicom2nifti==2.5.1
   highdicom
   ```
You're now ready to use TotalSegmentator! 