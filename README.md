
# ✈️ Flight Route Optimization using Graph Algorithms & Aviation APIs

A real-world flight routing system that simulates and optimizes air travel paths using **graph theory algorithms** and live data from **Aviation APIs**. The project focuses on reducing **flight time** and **fuel consumption** by modeling the global airline network as a weighted graph and finding optimal routes using classical algorithms.

---

## 🎯 Objective

To optimize airline routes between airports by applying **Dijkstra's** and **Floyd-Warshall** algorithms on real-time and historical airline data, minimizing travel duration and improving routing efficiency.

---

## 🚀 Key Features

| 🔍 Feature                     | 💡 Description                                                                 |
|-------------------------------|--------------------------------------------------------------------------------|
| 🌐 Graph-Based Routing         | Modeled airports and flight paths as a weighted graph using real-world data.  |
| 📡 Real-Time API Integration  | Integrated **Airline Routes**, **Schedule**, and **Historical APIs**.         |
| 🧠 Shortest Path Algorithms   | Applied **Dijkstra's** and **Floyd-Warshall** algorithms for path optimization.|
| 📊 Route Simulation           | Simulated optimal flight paths between international airports.                |
| ⏱️ Efficiency Gains           | Achieved ~**7% reduction in average travel time** over real-world routes.     |
| 📈 Visualization              | Used **Plotly** and **NetworkX** to display optimized flight routes.          |

---

## 🛠️ Tech Stack

| Category         | Tools / Libraries                             |
|------------------|------------------------------------------------|
| Programming      | Python                                         |
| Graph Algorithms | NetworkX, Custom Dijkstra & Floyd-Warshall    |
| APIs             | Aviationstack / AeroDataBox / AviationAPI     |
| Data Handling    | Pandas, NumPy                                  |
| Visualization    | Matplotlib, Plotly                             |

---

## 🌐 APIs Used

| API Name                 | Purpose                                 |
|--------------------------|------------------------------------------|
| ✈️ Airline Routes API     | Retrieves airline connectivity data      |
| 🕒 Real-time Schedule API | Provides live flight arrival/departure   |
| 🗂️ Historical Schedule API| Fetches past flight performance records  |

> Note: APIs used via a Developer plan with **30,000 calls/month**.

---

## 📁 Project Structure



flight-route-optimization/
├── data/                 # Preprocessed airport & flight data
├── src/                  # Routing algorithms and API calls
├── notebooks/            # EDA & route simulations
├── visualizations/       # Graph plots of optimized paths
├── api\_keys/             # Encrypted API key handler
└── README.md             # Project documentation



---

## 🧪 Methodology

1. **Data Collection**: Fetched airline routes and flight schedules via APIs.
2. **Graph Construction**: Represented each airport as a node; each route as a weighted edge (flight time).
3. **Optimization**:
   - **Dijkstra's Algorithm**: For single-source shortest path.
   - **Floyd-Warshall Algorithm**: For all-pairs path optimization.
4. **Visualization**: Used `Plotly` and `NetworkX` to map optimized vs real paths.
5. **Simulation**: Compared optimized routes to historical data for performance validation.

---

## 📊 Results

| Metric                        | Outcome                    |
|-------------------------------|-----------------------------|
| Average Time Reduction        | **~7%**                     |
| Simulated Airports            | 100+ global hubs            |
| Routing Accuracy              | Validated using past data   |
| Visualization Clarity         | Interactive graphs via Plotly|

---

## 🖼️ Sample Output

> ![Sample Route](visualizations/sample_route_plot.png)  
> *Optimized route vs historical path between JFK (New York) and LHR (London Heathrow)*

---

## 🔭 Future Scope

- 🌦️ Add **weather-based rerouting** using meteorological APIs  
- 🌱 Estimate **carbon footprint** for optimized vs original routes  
- 📍 Include **passenger-level customization** for layovers & airlines  

---

## 👨‍💻 Author

**Aditya Abhiram**  
📍 Hyderabad, India  
🔗 [LinkedIn](https://linkedin.com/in/adityaabhiram315)  
📧 [adityaabhiram315@gmail.com](mailto:adityaabhiram315@gmail.com)

---

## 🏁 Conclusion

This project showcases how **data science + graph algorithms + APIs** can be combined to build intelligent aviation solutions with measurable real-world impact. Ideal for **resume portfolios**, **data engineer roles**, or **ML system demonstrations**.

