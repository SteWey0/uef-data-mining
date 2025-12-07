# 1st network, only No2 lag

## Different layers

(4)
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.27  | 0.27 |
| IA     | 0.65  | 0.65 |
| RMSE   | 18.97 | 18.02 |
| MAE    | 15.05 | 14.29 |
| PSE    | 0.73  | 0.74 |

Not required:
(64,64) 
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.28  | 0.27 |
| IA     | 0.66  | 0.65 |
| RMSE   | 18.91 | 17.98 |
| MAE    | 14.95 | 14.26 |
| PSE    | 0.71  | 0.72 |

(128, 64, 32)
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.28  | 0.27 |
| IA     | 0.65  | 0.64 |
| RMSE   | 18.91 | 17.99 |
| MAE    | 15.02 | 14.34 |
| PSE    | 0.74  | 0.75 |

# 2nd network, No2 lag and periodic components

## Different layers

(4); ReLu -> 6s
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.32  | 0.33 |
| IA     | 0.68  | 0.70 |
| RMSE   | 18.39 | 17.25 |
| MAE    | 14.50 | 13.43 |
| PSE    | 0.70  | 0.66 |

(64, 64); ReLu -> 27s
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.49  | 0.37 |
| IA     | 0.80  | 0.76 |
| RMSE   | 15.95 | 16.75 |
| MAE    | 12.38 | 12.83 |
| PSE    | 0.53  | 0.50 |

(128, 64, 32); ReLu -> 31s
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.48  | 0.36 |
| IA     | 0.80  | 0.76 |
| RMSE   | 16.07 | 16.88 |
| MAE    | 12.46 | 12.92 |
| PSE    | 0.50  | 0.46 |

(128, 64, 32); tanh -> 51s
| Metric | Train | Test |
|--------|------:|-----:|
| R²     | 0.57  | 0.30 |
| IA     | 0.84  | 0.75 |
| RMSE   | 14.67 | 17.65 |
| MAE    | 11.26 | 13.50 |
| PSE    | 0.47  | 0.45 |

# 2nd network, No2 lag, periodic components and meterological data

## Different layers

(8,4)
| Metric | Train | Test |
|--------|-------|------|
| R² | 0.44 | 0.42 |
| IA | 0.77 | 0.77 |
| RMSE | 16.70 | 16.02 |
| MAE | 13.00 | 12.35 |
| PSE | 0.57 | 0.51 |

(64, 64) -> 1min 16s
| Metric | Train | Test |
|--------|-------|------|
| R² | 0.66 | 0.37 |
| IA | 0.89 | 0.80 |
| RMSE | 13.07 | 16.72 |
| MAE | 10.10 | 12.84 |
| PSE | 0.37 | 0.30 |

(128, 64, 32) -> 2min 
| Metric | Train | Test |
|--------|-------|------|
| R² | 0.75 | 0.17 |
| IA | 0.93 | 0.76 |
| RMSE | 11.10 | 19.19 |
| MAE | 8.38 | 14.37 |
| PSE | 0.21 | 0.23 |
