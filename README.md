# **Linear-Regression-from-scratch**
**A repository tracking my Data science journey showcasing my hands-on project, this project focuses on building Linear regression from scratch using the Normal equation and Gradient descent. ** 

A simple project comparing two common approaches to solving Linear Regression —  **Normal Equation** and the **Gradient Descent**— using NumPy and Matplotlib. This notebook demonstrates how both methods estimate parameters (θ), minimize cost, and explains how their performances differ depending on dataset size and hyperparameters.

##  What You'll Learn

- How to implement linear regression using:
  -  The Normal Equation (analytical solution)
  -  Gradient Descent (iterative optimization)
- How to compute the cost function
- How learning rate and iterations affect convergence
- When to prefer one method over the other

## Project Structure

```
├── Linear_Regression_fs.ipynb        # Main notebook
├── README.md                      # Project overview
```

## Key Concepts
- **Normal Equation** solves directly with:

  \[ theta = (X^TX)^{-1}X^Ty \]

- **Gradient Descent** iteratively adjusts parameters using:

  \[ theta = theta - alpha . {1}/{m} X^T (X.theta - y) \]


- Visualizations show how each method converges 

## Results

| Method           | Cost Value |
|------------------|------------|
| Normal Equation  | 6823       |
| Gradient Descent | 7013       |

## Tools Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook


##  Author

**Lawal Habeeb**  
Aspiring Data Scientist | Pharmacist 

email:habeebobashola09@gmail.com
Resouces used:
Khan academy:https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data
Statquest linear Regression : https://www.youtube.com/watch?v=nk2CQITm_eo
Assemble Ai Linear regression : https://youtu.be/ltXSoduiVwY?si=ts3XNgYNScRdzJvg
This mathmatics lecture(really helpful) : https://youtu.be/jc2IthslyzM?si=HvScY5LHrfH1v9hI
ChatGpt
Feel free to use and modify!


