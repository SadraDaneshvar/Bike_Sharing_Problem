<span style="font-family:Times New Roman; font-size:14pt;">
<h1 align="center"><b>Bike Sharing Problem: Integrating Quantitative Models and Machine Learning for Demand Forecasting with Mathematical Optimization for Bike Allocation</b></h2>
</span>

With the growing popularity of bike-sharing as a sustainable mode of urban transportation, efficiently managing the distribution of bikes across a network of stations becomes crucial. This project addresses the operational challenges inherent in managing these bike-sharing systems, with a specific focus on a dataset originating from a bike-sharing company in Seoul. The dataset, available on Kaggle ([Seoul Bike Sharing Demand Prediction](https://www.kaggle.com/datasets/saurabhshahane/seoul-bike-sharing-demand-prediction)), provides a rich foundation for analyzing and predicting bike-sharing demand patterns. The initiative is structured around a two-phased approach: the first phase is dedicated to forecasting the demand for bikes using a combination of quantitative models and machine learning techniques, and the second phase concentrates on employing mathematical optimization to ascertain the optimal allocation of bikes across the network. This comprehensive strategy aims to enhance the efficiency and user experience of bike-sharing services by ensuring bikes are available where and when they are needed.

## Phase 1: Demand Forecasting

In the initial phase, the project delves into the predictive aspect of the bike-sharing problem. Recognizing the dynamic nature of bike-sharing demand, which fluctuates based on various factors such as time of day, weather conditions, and urban events, this phase utilizes a blend of quantitative models and machine learning algorithms to forecast bike usage. Specifically, the Autoregressive Integrated Moving Average (ARIMA) model and machine learning techniques, including Random Forest, are applied to historical bike usage data. This approach not only captures the underlying patterns and seasonality in the data but also accounts for non-linear relationships and interactions between different variables, providing a robust and accurate prediction of future demand across different stations in the network.

## Phase 2: Bike Allocation Optimization

Building on the demand forecasts generated in Phase 1, the second phase of the project focuses on the strategic allocation of bikes across the network to meet this demand optimally. The core of this phase is a mathematical optimization model that seeks to minimize operational costs while ensuring that the availability of bikes aligns with the forecasted demand. The model incorporates various operational constraints, such as station capacities and redistribution logistics, and employs linear optimization techniques to determine the ideal number of bikes that should be allocated to each station. This phase not only ensures that the bike-sharing system operates efficiently but also enhances user satisfaction by improving the availability of bikes when and where they are needed most.

Through these two interconnected phases, the project offers a comprehensive solution to the bike-sharing problem, combining advanced analytics for demand forecasting with strategic planning for bike allocation. The outcome is a more efficient, responsive, and user-centric bike-sharing system that can adapt to the changing dynamics of urban mobility.

## Explore the Project

In this repository, you will find two meticulously documented Jupyter notebooks, each dedicated to one of the project's phases. The first notebook encompasses the entire demand forecasting process (Phase 1), providing a detailed walkthrough of the methodologies employed, from data preprocessing to the implementation of ARIMA and machine learning models. It includes a thorough explanation of each step, ensuring clarity and comprehensiveness in understanding the forecasting approach and its outcomes.

The second notebook delves into the bike allocation optimization process (Phase 2), where the mathematical model developed for optimal bike distribution is thoroughly explained and implemented. This notebook not only presents the optimization techniques and solutions but also offers a holistic analysis of the results, demonstrating the practical implications of the model on bike-sharing operations. The detailed documentation within this notebook makes the complex optimization process accessible, facilitating a deep understanding of the strategic allocation of bikes.

For a complete insight into the results, methodologies, and analytical processes underpinning this project, we highly encourage you to explore these notebooks. They serve as a comprehensive resource, elucidating every facet of the project with a depth that ensures both transparency and transferability of knowledge. 

## License
[MIT LICENSE](LICENSE)
