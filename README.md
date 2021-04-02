## Run
```
python3 main.py
```

## Steps
1. **Import the image**
2. **Pre Processing the Image** \
   2.1 Gaussian blur: We need to gaussian blur the image to reduce noise in thresholding algorithm \
   2.2 Thresholding: Segmenting the regions of the image \
   2.3 Dilating the image: In cases like noise removal, erosion is followed by dilation.
3. **Sudoku Extraction** \
3.1 Find Contours \
3.2 Find Corners: Using Ramer Doughlas Peucker algorithm / approxPolyDP for finding corners \
3.3 Crop and Warp Image: We remove all the elements in the image except the sudoku \
3.4 Extract Cells 
4. **Interpreting the Digits** \
4.1 Import the libraries and load the dataset \
4.2 Preprocess the data \
4.3 Creating the Model \
4.4 Predicting the digits
5. **Solving the Sudoku**

## Steps in deatil
### Sudoku
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/sudoku_1.jpg) 
### Pre Processing the Image
![](images/pre_processed.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/processed.png)
### Sudoku Extraction
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/pre_processed.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/cropped.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/processed_sudoku.png) \


### Interpreting the Digits
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/extracted_cell.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/cell_contour.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/model.png) 
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/number.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/predicted_num.png) 
### Solving
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/sudokuboard.png) \
![](https://github.com/Joy2469/Sudoku_AI/blob/master/images/Solved.png) 


