# Settings
**Model**: Random Forest
- Num Estimators: 100
- Max Depth: None
- Max Leaf Nodes: None

**Features**:  'zip'  'occupation'  'donations_ytd'  'donation' 

---
# Test metrics
### Classification Report:
| | Precision | Recall | f1-Score | Support |
| ---: | :---: | :---: | :---: | :---: |
| **DEM** | 0.99 | 0.96 | 0.98 | 285591 |
| **IND** | 0.34 | 0.66 | 0.45 | 3620 |
| **REP** | 0.79 | 0.96 | 0.87 | 28711 |
| **Macro Avg** | 0.71 | 0.86 | 0.76 | 317922 |
| **Weighted Avg** | `0.97` | `0.96` | `0.96` | 317922 |

**Accuracy**: 0.96	**Balanced Accuracy**: 0.86
### **Confusion Matrix**:
| **True / Predicted** | DEM | IND | REP |
| --: | :---: | :---: | :---: |
| **DEM** | `274202` | 4443 | 6946 |
| **IND** | 1075 | `2382` | 163 |
| **REP** | 1170 | 110 | `27431` |

---
# Train metrics
### Classification Report:
| | Precision | Recall | f1-Score | Support |
| ---: | :---: | :---: | :---: | :---: |
| **DEM** | 1.0 | 1.0 | 1.0 | 114572 |
| **IND** | 1.0 | 1.0 | 1.0 | 114572 |
| **REP** | 1.0 | 1.0 | 1.0 | 114572 |
| **Macro Avg** | 1.0 | 1.0 | 1.0 | 343716 |
| **Weighted Avg** | `1.0` | `1.0` | `1.0` | 343716 |

**Accuracy**: 1.0	**Balanced Accuracy**: 1.0
### **Confusion Matrix**:
| **True / Predicted** | DEM | IND | REP |
| --: | :---: | :---: | :---: |
| **DEM** | `114562` | 9 | 1 |
| **IND** | 0 | `114572` | 0 |
| **REP** | 11 | 0 | `114561` |
