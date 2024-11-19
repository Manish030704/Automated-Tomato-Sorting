# 🍅 **Automated Tomato Sorting with Python & OpenCV**

Welcome to the **Automated Tomato Sorting** project! This system uses **Python** and **OpenCV** to intelligently sort tomatoes based on their color and quality. With this system, you can automate the process of classifying tomatoes, calculating their prices, and displaying the total cost for a batch. Whether you're in the agricultural industry, a researcher, or just curious about how computer vision works, this project has something exciting to offer!

## 🚀 **Features**

- **Color-based Sorting**: The system automatically classifies tomatoes into three categories based on their color:
    - **Red**: Fully ripe tomatoes
    - **Yellow**: Ripe, but not fully matured
    - **Green**: Unripe, raw tomatoes 
  
- **Automated Pricing**: Each tomato's price is determined by its color:
    - **Red (Good)**: ₹1000
    - **Yellow (Edible)**: ₹800
    - **Green (InEdible)**: ₹300
  
- **Cost Calculation**: The system computes the total price based on the quantity of tomatoes in each category and displays the total value for your entire batch.

- **Real-Time Processing**: Whether you're working with stored images or streaming live footage from a webcam, the system can classify and process tomatoes on the fly!

- **Easy-to-Use Interface**: Simply load your images, and the system will handle the classification and display all the results.

## 🎯 **Why Use This System?**

- **Efficient Sorting**: Automatically sorts tomatoes in seconds, saving you time and manual effort.
- **Accurate Results**: Leverages computer vision techniques to ensure precise classification based on real-world criteria.
- **Cost-Effective**: Helps farmers, grocery stores, and markets easily determine the total value of tomatoes based on their quality.
- **Practical Application**: Ideal for use in sorting systems, automated farms, or inventory management.

## 🛠️ **Prerequisites**

Before running the project, make sure you have the following installed on your system:

- **Python 3.x** (Ensure you're using a modern version of Python)
- **OpenCV**: A powerful library for computer vision tasks
- **NumPy**: For handling numerical operations

### Install Required Libraries

To set up the project, follow these steps:

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/Manish030704/Automated-Tomato-Sorting
    ```

2. **Navigate** to the project directory:

    ```bash
    cd automated-tomato-sorting
    ```

3. **Install dependencies** using pip:

    ```bash
    pip install opencv-python numpy
    ```

4. **Run the main script**:

    ```bash
    python main.py
    ```

### 📸 **How It Works**
1. **Load images**: Place your tomato images in the `/images` folder.
2. **Processing**: The script will classify the tomatoes based on their color and calculate their prices.
3. **Display Results**: The system will show the classified images and print the total cost for each category.

## 💡 **Future Enhancements**

- **Machine Learning Integration**: Train a machine learning model to classify tomatoes based on additional features like texture and shape.
- **User Interface**: Add a web or desktop app for even easier interaction.
- **Advanced Pricing**: Add more complex pricing models based on the weight or size of the tomatoes.




### **Don't forget to star this repo! ⭐**
