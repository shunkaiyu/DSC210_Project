# DSC210_Project

## How to Run the Code of stereo-vision method:
1) Change the dataset directory in *main.py* file:

    ```PY
    img1 = cv2.imread(f"Dataset{number}/im0.png", 0)
    img2 = cv2.imread(f"Dataset{number}/im1.png", 0)
    ```
2) Run the following command:
  
    ```sh
    python main.py
    ```

## Reference:
https://github.com/savnani5/Depth-Estimation-using-Stereovision

## How to Run the Code of SOTA method:
1) Download depth_anything_v2_vits.pth checkpoint and put it into checkpoints folder.

2) run code in `run.ipynb`.

## Results
<!-- Image is currently blank/missing -->
![Combined Results](https://imgur.com/KC2W3PE.png)
