# 🇲🇦 Morocco National Team Performance Analysis - CAN 2023 ⚽

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![StatsBomb](https://img.shields.io/badge/Data-StatsBomb-red.svg)](https://statsbomb.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/yourusername/morocco-can-analysis/graphs/commit-activity)

## 🌟 Overview

An in-depth statistical analysis of the **Morocco National Football Team's performance** during the latest edition of the **Africa Cup of Nations (CAN)**. This project leverages advanced football analytics using StatsBombPy to provide comprehensive insights into team tactics, player performance, and match dynamics.

> **🏆 Why This Matters**: Morocco's recent success in international football, including their historic World Cup 2022 run, makes this analysis particularly valuable for understanding African football excellence and tactical evolution.

## 🎯 Key Features

### 📊 **Comprehensive Match Analysis**
- Detailed breakdown of every Morocco match in the tournament
- Goal analysis, key moments, and tactical phases
- Performance metrics across different game situations

### 🎯 **Pass Analysis Engine**
- **Successful Passes**: Heat maps and distribution patterns
- **Incomplete Passes**: Analysis of failed attempts and pressure situations
- Pass accuracy under different tactical setups and match phases

### 🔥 **Activity Heat Maps**
- Player positioning and movement patterns
- Territory control visualization
- Defensive and offensive activity zones

### 👤 **Individual Player Insights**
- Event-by-event player performance tracking
- Comprehensive player statistics and contributions
- Performance comparison across tournament matches

## 🚀 Quick Start

### Prerequisites
```bash
pip install statsbombpy pandas matplotlib seaborn numpy
```


## 📁 Project Structure

```
📦 Morocco CAN Analysis
├── 📋 Match_Output.zip          # Complete match analysis results
├── ✅ Successful_Passes.zip     # Successful pass analysis & visualizations
├── ❌ Incomplete_Passes.zip     # Failed pass analysis & insights
├── 🔥 Activity_Heatmap.zip      # Player activity heat maps
├── 🎯 Player_Events.zip         # Individual player event tracking
├── 📊 All_Events_Per_Player.zip # Comprehensive player statistics
├── 📜 README.md                 # This file
```

## 📈 Analysis Highlights

### 🎯 **Tactical Insights**
- Formation analysis and tactical flexibility
- Pressing patterns and defensive organization
- Set-piece effectiveness and corner kick strategies

### 🏃‍♂️ **Performance Metrics**
- Distance covered per player and position
- Sprint frequency and intensity zones
- Possession statistics and territory control

### 🎨 **Visualization Features**
- Interactive heat maps with matplotlib/seaborn
- Pass network diagrams
- Shot maps  analysis
  

## 🔍 Key Findings Preview

### 🏆 GENERAL INFORMATION:
   - Total events analyzed: **6,712**
   - Number of teams: **1**
   - Unique players: **22**
   - Number of matches: **4**

### ⚽ EVENT DISTRIBUTION:
   - **Pass**: 1,945 (29.0%)
   - **Ball Receipt**: 1,907 (28.4%)
   - **Carry**: 1,541 (23.0%)
   - **Pressure**: 496 (7.4%)
   - **Ball Recovery**: 154 (2.3%)
   - **Duel**: 99 (1.5%)
   - **Foul Committed**: 61 (0.9%)
   - **Shot**: 58 (0.9%)
   - **Block**: 56 (0.8%)
   - **Clearance**: 56 (0.8%)

### 🎯 PASSING ANALYSIS:
   - **Total passes**: 1,945
   - **Successful passes**: 1,659
   - **Success rate**: **85.3%**
   - **Average length**: 21.1m
   - **Longest pass**: 83.8m
   - **Distribution by height**:
     - Ground Pass: 1,460
     - High Pass: 320
     - Low Pass: 165

### 🥅 SHOOTING ANALYSIS:
   - **Total shots**: 58
   - **Shot outcomes**:
     - Off Target: 21 (36.2%)
     - Saved: 15 (25.9%)
     - Blocked: 13 (22.4%)
     - **Goal**: 5 (8.6%)
     - Wayward: 3 (5.2%)
     - Post: 1 (1.7%)
   - **Total xG**: 7.87
   - **Average xG per shot**: 0.136
   - **Shots by body part**:
     - Left Foot: 28
     - Right Foot: 19
     - Head: 11

### 🛡️ DEFENSIVE ANALYSIS:
   - **Interceptions**: 21
   - **Clearances**: 56
   - **Total duels**: 99
   - **Duels won**: 13 (13.1%)
   - **Fouls committed**: 61

### ⚽ POSSESSION ANALYSIS:
   - **Action distribution**:
     - **Morocco**: 5,825 actions (86.8%)
     - Zambia: 234 actions (3.5%)
     - South Africa: 222 actions (3.3%)
     - Congo DR: 222 actions (3.3%)
     - Tanzania: 209 actions (3.1%)
   - **Average action duration**: 1.3s

### ⭐ KEY PLAYERS:
   #### 🏃‍♂️ **Most Active Players**:
      1. **Achraf Hakimi Mouh**: 812 actions
      2. **Azzedine Ounahi**: 791 actions
      3. **Nayef Aguerd**: 771 actions
      4. **Sofyan Amrabat**: 661 actions
      5. **Romain Saïss**: 501 actions
      6. **Hakim Ziyech**: 457 actions
      7. **Sofiane Boufal**: 298 actions
      8. **Yassine Bounou**: 273 actions
      9. **Amine Adli**: 253 actions
     10. **Abdessamad Ezzalzouli**: 249 actions

   #### 📈 **Performance Leaders**:
   - **Top Passers**:
     - Nayef Aguerd: 269
     - Achraf Hakimi Mouh: 260
     - Azzedine Ounahi: 217
   
   - **Top Shooters**:
     - Youssef En-Nesyri: 8
     - Azzedine Ounahi: 7
     - Hakim Ziyech: 7
   
   - **Top Dribblers**:
     - Azzedine Ounahi: 12
     - Sofiane Boufal: 10
     - Abdessamad Ezzalzouli: 9
   
   - **Top Interceptors**:
     - Romain Saïss: 3
     - Mohamed Chibi: 3
     - Hakim Ziyech: 3

### 🏟️ FIELD ZONE ANALYSIS:
   - **Activity by zone**:
     - **Right Midfield**: 1,429 (21.5%)
     - **Left Midfield**: 996 (15.0%)
     - **Right Attack**: 819 (12.3%)
     - **Center Midfield**: 726 (10.9%)
     - **Center Defense**: 618 (9.3%)
     - **Left Attack**: 613 (9.2%)
     - **Right Defense**: 574 (8.6%)
     - **Left Defense**: 491 (7.4%)
     - **Center Attack**: 395 (5.9%)

### 📊 **Summary Statistics Object**:
```python
{
  'general': {
    'total_events': 6712, 
    'teams': ['Morocco'], 
    'players': 22
  },
  'passes': {
    'total': 1945,
    'success_rate': 85.30,
    'average_length': 21.15
  },
  'shots': {
    'total': 58, 
    'total_xg': 7.87
  },
  'defensive': {
    'interceptions': 21, 
    'clearances': 56, 
    'fouls': 61
  },
  'possession': {
    'Morocco': 5825,
    'Zambia': 234,
    'South Africa': 222,
    'Congo DR': 222,
    'Tanzania': 209
  },
  'key_players': {
    'Achraf Hakimi Mouh': 812,
    'Azzedine Ounahi': 791,
    'Nayef Aguerd': 771,
    'Sofyan Amrabat': 661,
    'Romain Saïss': 501
  },
  'zones': {
    'Right Midfield': 1429,
    'Left Midfield': 996,
    'Right Attack': 819,
    'Center Midfield': 726,
    'Center Defense': 618,
    'Left Attack': 613,
    'Right Defense': 574,
    'Left Defense': 491,
    'Center Attack': 395
  }
}
```

## 🛠️ Technical Stack

- **🐍 Python 3.8+**: Core programming language
- **📊 StatsBombPy**: Professional football data access
- **📈 Pandas**: Data manipulation and analysis
- **🎨 Matplotlib/Seaborn**: Data visualization
- **🔢 NumPy**: Numerical computations
- **📋 Jupyter Notebooks**: Interactive analysis environment

## 📚 Data Source

This project uses **StatsBomb's open data**, which provides:
- Event-by-event match data
- Player tracking information
- Advanced metrics (xG, xA, PPDA, etc.)
- Tactical and positional data

*StatsBomb provides free access to certain competitions for research and educational purposes.*


## 💡 Contribution Ideas
- Additional visualization types
- Statistical model improvements
- Comparative analysis with other teams
- Performance prediction models


## 🎓 Educational Value

This project is perfect for:
- **🎓 Students** learning sports analytics
- **⚽ Football enthusiasts** wanting deeper insights
- **📊 Data scientists** exploring sports data
- **🏆 Coaches and analysts** studying tactical patterns

## 🌍 Connect & Follow

- **💼 LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/abdellah-maghous-036a0a159/)
- **🐦 Twitter**: [@YourTwitter](https://x.com/data212maroc)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **StatsBomb** for providing free access to football data
- **Morocco National Team** for inspiring performances
- **Open source community** for amazing Python libraries
- **African football** community for the passion and support

## ⭐ Star This Repository

If you find this analysis valuable, please consider giving it a star! It helps others discover the project and motivates continued development.

---

*"Football is not just about what happens on the pitch - it's about understanding the beautiful patterns hidden in the data."*

