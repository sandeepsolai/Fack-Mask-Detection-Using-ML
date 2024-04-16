## Face Mask Detection using 

### Setup

- Install Python3 from [here](https://www.python.org/)
- Open Windows Command Prompt.
- Clone the repository

```bash
  git clone https://github.com/sandeepsolai/FACE-MASK-DETECTION-USING-ML.git
```

- Navigate inside the `Face Mask Detection` directory.
- Run this command

```bash
  pip install -r requirements.txt
```

- If you want to test detection on your image then go to `mask_detection.py` file and just change the path in the `image_path` variable at `line 15` and add your own image's path in that field.
- Now we are good to go.

Run using Python:

```bash
  python mask_detection.py
```

Now you will see the Output with detections and bounding boxes in th `Results` folder.

To see how the Model was trained go to `Model/Object_Detection.ipynb`
