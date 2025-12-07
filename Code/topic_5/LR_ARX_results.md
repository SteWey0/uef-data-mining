# Simple linear regression model
## Vary the test years. Keep number of components fixed at 24 yearly, 24 weekly, 12 daily
Results of test year 1999:
| Metric                                 | Train (NO2) | Test (NO2) |
|----------------------------------------|-------------:|-----------:|
| R squared                              | 0.39        | 0.24       |
| Index of agreement                     | 0.74        | 0.71       |
| RMSE                                   | 18.54       | 18.76      |
| Proportion of systematic error         | 0.60        | 0.56       |

1998:
| Metric                                 | Train (NO2) | Test (NO2) |
|----------------------------------------|------------:|-----------:|
| R squared                              | 0.38        | 0.36       |
| Index of agreement                     | 0.73        | 0.74       |
| RMSE                                   | 18.48       | 17.98      |
| Proportion of systematic error         | 0.61        | 0.58       |

1997:
| Metric                                 | Train (NO2) | Test (NO2) |
|----------------------------------------|------------:|-----------:|
| R squared                              | 0.42        | 0.15       |
| Index of agreement                     | 0.76        | 0.68       |
| RMSE                                   | 18.06       | 19.72      |
| Proportion of systematic error         | 0.57        | 0.53       |

1996:
| Metric                                 | Train (NO2) | Test (NO2) |
|----------------------------------------|------------:|-----------:|
| R squared                              | 0.40        | 0.28       |
| Index of agreement                     | 0.75        | 0.66       |
| RMSE                                   | 16.97       | 22.63      |
| Proportion of systematic error         | 0.60        | 0.74       |

Mean: 
| Metric                                 | Mean Train (NO2) | Mean Test (NO2) |
|----------------------------------------|------------------:|-----------------:|
| R squared                              | 0.40              | 0.26             |
| Index of agreement                     | 0.75              | 0.70             |
| RMSE                                   | 18.01             | 19.77            |
| Proportion of systematic error         | 0.60              | 0.60             |


## Vary the number of components

Half the number:
| Metric                                 | Train (NO2) | Test (NO2) |
|----------------------------------------|------------:|-----------:|
| R squared                              | 0.21        | 0.28       |
| Index of agreement                     | 0.64        | 0.64       |
| RMSE                                   | 19.43       | 22.62      |
| Proportion of systematic error         | 0.64        | 0.76       |


1.5 the number:
| Metric                                 | Train (NO2) | Test (NO2) |
|----------------------------------------|------------:|-----------:|
| R squared                              | 0.43        | 0.27       |
| Index of agreement                     | 0.77        | 0.66       |
| RMSE                                   | 16.47       | 22.77      |
| Proportion of systematic error         | 0.57        | 0.72       |


# AR(X) model

## Vary the lag 

8 hours:
| Metric                                 | Train NO2 | Test NO2 | Train NO2+O3 | Test NO2+O3 |
|----------------------------------------|----------:|---------:|-------------:|------------:|
| R squared                              | 0.29      | 0.25     | 0.30         | 0.27        |
| Index of agreement                     | 0.66      | 0.65     | 0.67         | 0.66        |
| RMSE                                   | 20.02     | 18.52    | 19.83        | 18.37       |
| Proportion of systematic error         | 0.71      | 0.71     | 0.70         | 0.69        |

12 hours:
| Metric                                 | Train NO2 | Test NO2 | Train NO2+O3 | Test NO2+O3 |
|----------------------------------------|----------:|---------:|-------------:|------------:|
| R squared                              | 0.29      | 0.25     | 0.30         | 0.27        |
| Index of agreement                     | 0.66      | 0.65     | 0.67         | 0.66        |
| RMSE                                   | 20.01     | 18.51    | 19.82        | 18.37       |
| Proportion of systematic error         | 0.71      | 0.71     | 0.70         | 0.68        |

24 hours:
| Metric                                 | Train NO2 | Test NO2 | Train NO2+O3 | Test NO2+O3 |
|----------------------------------------|----------:|---------:|-------------:|------------:|
| R squared                              | 0.30      | 0.26     | 0.32         | 0.27        |
| Index of agreement                     | 0.67      | 0.66     | 0.68         | 0.67        |
| RMSE                                   | 19.81     | 18.38    | 19.63        | 18.25       |
| Proportion of systematic error         | 0.70      | 0.69     | 0.68         | 0.67        |

168 hours:
| Metric                                 | Train NO2 | Test NO2 | Train NO2+O3 | Test NO2+O3 |
|----------------------------------------|----------:|---------:|-------------:|------------:|
| R squared                              | 0.38      | 0.34     | 0.39         | 0.35        |
| Index of agreement                     | 0.74      | 0.72     | 0.74         | 0.73        |
| RMSE                                   | 18.63     | 17.41    | 18.44        | 17.32       |
| Proportion of systematic error         | 0.62      | 0.61     | 0.61         | 0.59        |
