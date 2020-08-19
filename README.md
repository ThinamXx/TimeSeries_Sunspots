# **Time Series: Sunspots**

#### [**Sunspots**](https://www.kaggle.com/robervalt/sunspots)
- Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are regions of reduced surface temperature caused by concentrations of magnetic field flux that inhibit convection. Sunspots usually appear in pairs of opposite magnetic polarity. Their number varies according to the approximately 11-year solar cycle.

#### **Time Series**
- A time series is a series of data points indexed in time order. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data.

**Recurrent Neural Network**
- A recurrent neural network is a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows it to exhibit temporal dynamic behavior.

**LSTM**
- Long short-term memory is an artificial recurrent neural network architecture used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. It can not only process single data points, but also entire sequences of data.

**Convolutional Neural Network**
- In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.

#### **Getting the Data**
- In this Project, I have downloaded the data using the link mentioned below. You can manually download the data from [Kaggle](https://www.kaggle.com/robervalt/sunspots). I am using Google Colab for this Project, so the act of reading the data might be different in different platforms.

```javascript
!wget --no-check-certificate \
    https://storage.googleapis.com/laurencemoroney-blog.appspot.com/Sunspots.csv \
    -O /tmp/sunspots.csv
```

#### **Snapshot of the Data**

![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1597843410/Time_ca878j.png)

#### **Snapshot of the Model Forecasting**

![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1597843517/0011_ce15kw.png)
