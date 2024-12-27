# One Day in Disneyland Magic Kingdom
**By: Yiheng Su**

## 📖 Overview

Disneyland Magic Kingdom (Orlando, FL) offers a variety of rides and attractions, but long wait times and occasional closures can make it difficult to fully enjoy the park in just one day. This project tackles the problem of planning an optimal one-day itinerary using optimization models.

### Goals:
1. **Maximize the number of attractions visited.**
2. **Minimizing the leaving time.**
3. **Minimizing the travelling time.**
4. **Maximize personal ratings for rides and attractions.**

This project is inspired by the Traveling Salesman Problem (TSP) and incorporates dynamic factors like ride availability and wait times.

---

## 📊 Data and Methods
The project uses:
- **Wait Time Data**: Collected from historical and real-time APIs.
- **Travel Times**: Based on the park layout and distances between attractions.
- **Optimization Models**: Built with integer programming to calculate efficient itineraries.

---

## 📂 Repository Structure
- `notebooks/`: Contains Jupyter Notebooks for the project.
- `data/`: Includes datasets like ride wait times and park maps.
- `images/`: Stores visualizations and example itineraries.
- `README.md`: Project overview and setup instructions.
- `requirements.txt`: List of Python dependencies.

---

## 📈 Results
The optimization models generated several possible schedules for a one-day visit to Disneyland Magic Kingdom. After comparing different objectives—such as maximizing attractions visited, minimizing waiting times, and reducing travel time—the most reasonable playing schedule was the one generated in **Section 3.3**, which focuses on **minimizing travel time**.

### Key Outcomes:
1. **Efficient Timing**: This schedule avoids extremely early arrivals (e.g., 7:30 AM) and allows for a reasonable departure time around 10:00 PM.
2. **Comprehensive Experience**: All rides and attractions are included in the schedule, ensuring a fulfilling visit.
3. **Minimized Walking**: By prioritizing travel time, unnecessary back-and-forth walking between rides is avoided, making the experience more enjoyable and less exhausting.

This optimized itinerary highlights how thoughtful planning can significantly enhance a visit to a theme park, balancing efficiency and enjoyment.

---

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Disneyland-One-Day-Schedule.git
