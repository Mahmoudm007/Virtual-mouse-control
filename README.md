# A CV Preprocessing Magic Tool

This project is a comprehensive tool developed from scratch using C++. It utilizes the OpenCV library for image processing functionalities and integrates a user-friendly interface created with Qt Creator desktop application.

## Description
This project aims to provide a versatile tool for preprocessing images, particularly tailored for Computer Vision (CV) applications. It offers a range of features to manipulate and enhance images before feeding them into CV algorithms. The key functionalities include:

- ***Adding Noise Cumulatively***: Introduce various types of noise into the image.
  
    ****Gausian noise****
  ![Example Image](images/gaussian_noise.png)

    ****Uniform noise****
  ![Example Image](images/uniform_n.png)

    ****Salt and papper noise****
  ![Example Image](images/salt.png)
  
- **Applying Filters**: Implement different filters to modify image properties.
    ****Gaussian filter****
  ![Example Image](images/gaus_f.png)
  
    ****Median filter****
    ![Example Image](images/median.png)
  
    ****Average filter****
    ![Example Image](images/avg.png)

- **Edge Detection**: Employ multiple methods to detect edges within the images.
  
    ****Sobel detector****
    ![Example Image](images/sob.png)
  
    ****Robert detector****
    ![Example Image](images/rob.png)

    ****Canny detector****
    ![Example Image](images/canny.png)
  
- **Thresholding**: Apply global or local thresholding techniques.

  
  ***Global thresholding***
  ![Example Image](images/global.png)

  ***Local thresholding***
  ![Example Image](images/local.png)
  
- **Equalizing and Normalizing**: Adjust the image histogram to improve contrast.

  
    ***Equalized image***
    ![Example Image](images/eq.png)


    ***Normalized image***
    ![Example Image](images/norm.png)
  
- **Color Space Transformation**: Convert RGB images to grayscale.

  
    ***Gray scale image***
    ![Example Image](images/gray.png)

  
- **Displaying Distribution Curve and CDF**: Visualize the distribution and Cumulative Distribution Function (CDF) of each color channel.
  
- **Frequency Domain Filtering**: Apply low or high pass filters in the frequency domain.

  
  ***Low-pass filter***
  ![Example Image](images/low.png)

  
  ***High-pass filter***
  ![Example Image](images/high.png)

  
- **Hybrid Image Creation**: Merge two images in the frequency domain to generate a new hybrid image.

  
    ***Hybrid image***
    ![Example Image](images/hybrid.png)

## Implementation Details
- **Language**: C++
- **Image Reading and Display**: OpenCV
- **User Interface**: Qt Creator Desktop Application

## Usage
[OpenCV installation](https://opencv.org/)
[Adding openCV to visual studio](https://www.youtube.com/watch?v=unSce_GPwto&pp=ygUdb3BlbmN2IGMrKyB2aXN1YWwgc3R1ZGlvIGNvZGU%3D)



## Screenshots of application

![Filter and noise tab](images/tab1.png)

![Edge detection tab](images/tab2.png)

![Equalized and normalized tab](images/tab3.png)

![Histograms tab](images/tab4.jpg)

![Thresholding  tab](images/tab5.png)

![Hybrid  tab](images/tab6.png)

