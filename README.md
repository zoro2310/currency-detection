# currency-detection

## INSTRUCTIONS TO RUN THE CODE
### <There's also an alternative at the end>
- Create the data set
    ```
    From the repository either download the complete dataset 
    or create your own using following instruction
    - Create a folder named dataset
    - Inside the folder create subfolder named "10,20,100,200,500,2000"
    - Download multiple images for each category (try to get 50+ each) with the same file extension(prefered jpg)
    - Move the images to their respective folder and named them properly
    ```
- Create the testimg set
    ```
    From the repository either download the complete testimg folder 
    or create your own using following instruction
    - Create a folder named testimg
    - Download one image for each category with the same file extension
    - Move the images to the folder and named them properly
    - Note down the name of image you want to test 
    - Change the code where we created the input image to the file name you want to test
    Ex.
    If you want to the input image to be test1.jpeg
    change: test_img = read_img('testimg/test2.jpeg')
    to: test_img = read_img('testimg/test1.jpeg')
    ```
- Create the Utils file
    ```
    From the repository either download the util file 
    or create your own using following instruction
    - Create a file named util.py
    - Inside the file you should paste the code from util.py in the repository to your local system
    ```
- Create the Main file
    ```
    From the repository download the Main.py file into your project folder
    ```
- Run the Main FIle

## Alternatively you can fork the repository and clone that to your local system or open in github codespace and then run the Main file