# Hearity - Final Capstone Project 2024

`Hearity` is ...

## Our Team

|               Nama               |  Bangkit-ID  |        Path        |                                  LinkedIn                                  |
| :------------------------------: | :----------: | :----------------: | :------------------------------------------------------------------------: |
|      Agnes Sura Pati Sinaga      | M218B4KX0174 |  Machine Learning  |        [here](https://www.linkedin.com/in/agnes-sura-pati-sinaga/)         |
| Aryasaty Kirana Tungga Maheswari | M180B4KX0685 |  Machine Learning  |            [here](https://www.linkedin.com/in/aryasatykirana/)             |
|   Gusti Ayu Putu Erika Erlina    | M013B4KX1650 |  Machine Learning  | [here](https://www.linkedin.com/in/gusti-ayu-putu-erika-erlina-2105a5219/) |
|          Eko Kurniawan           | A013B4KY1243 | Mobile Development |              [here](https://www.linkedin.com/in/eko-kurnia/)               |
|      Rangga Felicia Fulfian      | A388B4KY3689 | Mobile Development |         [here](https://www.linkedin.com/in/ranggafeliciafulfian/)          |
|      Nabila Naurotul Ummah       | C013B4KX3183 |  Cloud Computing   |       [here](https://www.linkedin.com/in/nabila-naurotul-338558284/)       |
|       Naufal Adhi Ramadhan       | C621B4KY3277 |  Cloud Computing   |            [here](https://linkedin.com/in/naufaladhiramadhan/)             |

## Mobile Development

App displays visualization of hearing forecasting results in the form of graphs or tables, starting from the last test time to tomorrow’s graph (daily forecasting). Then, sends notifications to the user to remind them to wear earbuds or earmuffs.
The search feature will help users find the nearest hospital or hearing center based on their current location.

#### Used Libraries

- Retrofit: used to simplify the process of data exchange between Android applications and servers through REST APIs.
- Room: used to store data in local storage.
- MPANDROIDCHART or Kandy: used to display data in the form of charts from the data that has been obtained.

## Machine Learning

Develop a multivariate multioutput time series forecasting using some techniques like CNN, FNN, or other related models. Then, the outcome of the forecasting will be a graph of the user’s hearing quality and system recommendations technique that generates the reminder for users and some recommendations about ear’s health in the form of articles, and videos.

#### Used Libraries

- Pandas: Used for data manipulation and analysis, providing data structures like DataFrames for handling datasets.
- Numpy: Provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays.
- TensorFlow: For building and training neural networks and other machine learning models.
- Keras: A high-level neural networks API, written in Python and capable of running on top of TensorFlow, designed for quick experimentation with deep neural networks.
- Matplotlib: Matplotlib is essential for visualizing data in Python, widely used across preprocessing and model evaluation stages. This visualization capability supports model diagnostics and helps ensure data is ready for modeling or use.
- Scikit-learn: Offering various preprocessing tools, including data scaling for standardization and normalization. By scaling data, Scikit-learn ensures that features are on a comparable scale, which improves the performance and convergence speed of machine learning algorithms.
- Logging: The logging module in Python is a crucial tool for tracking and debugging projects, as it records events from different parts of an application. This library helps capture errors, log the flow of functions, and monitor the overall behavior of code.
- Tensor Flow Lite : For deploying TensorFlow models on mobile and embedded devices.

## Cloud Computing

Implement APIs using Express.js for Node.js, integrating them with the database and machine learning model on Google Cloud. The APIs, deployed on Cloud Engine, will be accessible to the mobile app. Resources will be managed via Google Cloud Console and Cloud Shell.

#### Used Libraries

- Express.js: Used to quickly and easily build servers and APIs in Node.js, with features for handling routing and middleware.
- ESLint: Ensures code consistency and prevents errors in JavaScript by identifying issues and enforcing agreed-upon coding standards.
- Dotenv: Manages environment variables securely, such as API keys or passwords, without embedding them directly in the code.
- Mongoose: Simplifies data management in MongoDB by providing structured schemas and data models, making validation and data manipulation easier.
