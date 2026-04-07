### R-squared
$$R^2 = 1 - \frac{\hat{\epsilon}' \hat{\epsilon}}{(y - \bar{y})' (y - \bar{y})}; \quad \bar{y} = \sum_{t = 1}^{T} y_t / T$$

### Adjusted R-squared
$$\bar{R}^2 = 1 - (1 - R^2) \frac{T - 1}{T - k}$$

### Standard Error of the Regression (S.E. of regression)
$$s = \sqrt{\frac{\hat{\epsilon}' \hat{\epsilon}}{(T - k)}}$$

### Suma de los Cuadrados de los Residuos (SSR)**
$$\hat{\epsilon}' \hat{\epsilon} = \sum_{t=1}^{T} (y_i - X_i' b)^2$$

### **Logaritmo de la Función de Verosimilitud (Log Likelihood)**
$$l = -\frac{T}{2} (1 + \log(2\pi) + \log(\hat{\epsilon}' \hat{\epsilon} / T))$$

### **Estadístico de Durbin-Watson (DW)**
$$DW = \sum_{t=2}^{T} (\hat{\epsilon}_t - \hat{\epsilon}_{t-1})^2 / \sum_{t=1}^{T} \hat{\epsilon}_t^2$$


### **Media y Desviación Típica de la Variable Dependiente**

### **Media ($\bar{y}$):**
$$\bar{y} = \sum_{t=1}^{T} y_t / T$$

### **Desviación Típica ($s_y$):**
$$s_y = \sqrt{\sum_{t=1}^{T} (y_t - \bar{y})^2 / (T - 1)}$$

### **Akaike Information Criterion (AIC):**
$$AIC = -2l/T + 2k/T$$

### **Schwarz Criterion (SC / BIC):**
$$SC = -2l/T + (k \log T) / T$$

### **Hannan-Quinn Criterion (HQ):**
$$HQ = -2(l/T) + 2k \log(\log(T))/T$$

### **Estadístico F (F-Statistic)**

$$F = \frac{R^2 / (k - 1)}{(1 - R^2) / (T - k)}$$
