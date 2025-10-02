# Bayesian Regression for Weather Forecasting

This project looks at how **Bayesian regression** can be used to improve weather forecasting using data from **ARPAV** (Agenzia Regionale per la Prevenzione e Protezione Ambientale del Veneto).  
Instead of just predicting future values, the idea was to also measure how **certain or uncertain** those predictions are — which is really important when dealing with something as complex as the weather.

---

## What We Did
- Collected and cleaned **time series data** from ARPAV.  
- Built regression models in a **Bayesian framework**.  
- Explored the **posterior distributions** of the parameters.  
- Compared the Bayesian approach with more traditional regression methods.  

---

## Why It’s Interesting
- Bayesian methods don’t just give a number, they also give a **confidence interval** around the prediction.  
- This makes the model more transparent and useful, since we can see how reliable a forecast is.  
- The approach proved to be more robust when data was noisy or incomplete.  

---

## Tools We Used
- **Python** for data analysis and modeling  
- **PyMC / Stan** for Bayesian inference  
- **Pandas, NumPy, Matplotlib** for data handling and visualization  

---

## Credits
This project was developed in collaboration with:  
- **Alessandro Miotto**  
- **Lorenzo Rizzi**  
- **Riccardo Corte**  




