# Background-Replacement-DIS-Libraire

---

### Step 1: Input Videos

- **Original video - Source**
- **Background video - Target**

Extract both foreground frames and background frames using `frames.py`. In this script, you can specify the desired number of frames per second to extract.

The extracted frames will be stored in separate folders:
- `fg_frames` folder for foreground frames
- `bg_frames` folder for background frames

### Step 2: Processing Frames

Process both the foreground and background frames using the `Bg_replacement_image_bulk_images.ipynb` notebook. The final processed frames will be stored in a specified folder.

### Step 3: Merging Frames

Using the processed/blended frames, merge the frames with `frames_merge.py` to obtain a video with the background replaced.

---


Model File: https://hanyaatechnologies-my.sharepoint.com/:f:/g/personal/saidulu_shaik_hanyaatech_com/EkN41SfUfOVIj_yEkuCmDm0BC_o68lLM2UEnzhK1NEhsyg?e=VGRlLJ