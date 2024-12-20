# Settings
**Model**: k Nearest Neighbor
- Num Neighbors = 2
- Distance = euclidean

**Features**:  'zip'  'occupation'  'donations_ytd'  'donation' 

---
# Test metrics
### Classification Report:
| | Precision | Recall | f1-Score | Support |
| ---: | :---: | :---: | :---: | :---: |
| **DEM** | 0.97 | 0.87 | 0.92 | 285591 |
| **IND** | 0.17 | 0.68 | 0.27 | 3620 |
| **REP** | 0.45 | 0.77 | 0.57 | 28711 |
| **Macro Avg** | 0.53 | 0.77 | 0.59 | 317922 |
| **Weighted Avg** | `0.92` | `0.86` | `0.88` | 317922 |

**Accuracy**: 0.86	**Balanced Accuracy**: 0.77
### **Confusion Matrix**:
| **True / Predicted** | DEM | IND | REP |
| --: | :---: | :---: | :---: |
| **DEM** | `247286` | 11249 | 27056 |
| **IND** | 850 | `2477` | 293 |
| **REP** | 5796 | 810 | `22105` |

---
# Train metrics
### Classification Report:
| | Precision | Recall | f1-Score | Support |
| ---: | :---: | :---: | :---: | :---: |
| **DEM** | 0.91 | 1.0 | 0.95 | 114572 |
| **IND** | 0.99 | 1.0 | 0.99 | 114572 |
| **REP** | 1.0 | 0.89 | 0.94 | 114572 |
| **Macro Avg** | 0.96 | 0.96 | 0.96 | 343716 |
| **Weighted Avg** | `0.96` | `0.96` | `0.96` | 343716 |

**Accuracy**: 0.96	**Balanced Accuracy**: 0.96
### **Confusion Matrix**:
| **True / Predicted** | DEM | IND | REP |
| --: | :---: | :---: | :---: |
| **DEM** | `114571` | 1 | 0 |
| **IND** | 57 | `114515` | 0 |
| **REP** | 11560 | 1587 | `101425` |
