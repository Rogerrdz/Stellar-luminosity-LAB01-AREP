# # Stellar Luminosity Regression Models

This project implements linear and polynomial regression models from first principles to model stellar luminosity based on physical properties such as stellar mass and effective temperature. The objective is to understand how linear, nonlinear, and interaction effects influence luminosity, while reinforcing foundational machine learning concepts and cloud-based execution.

## Getting Started

These instructions will allow you to run the project locally and understand its structure. The project consists of two Jupyter notebooks and does not require external datasets or machine learning libraries.

### Prerequisites

You need the following software installed:

- Python 3.x
- Jupyter Notebook or JupyterLab

Required Python libraries:

```
numpy
matplotlib

```


These libraries can be installed using:


```
pip install numpy matplotlib
```


### Installing

Clone the repository to your local machine:

```
git clone <https://github.com/Rogerrdz/Stellar-luminosity-LAB01-AREP.git>
```


Navigate to the project directory:

```
cd stellar-luminosity-regression
```

Launch Jupyter Notebook:

```
jupyter notebook
```

Open and run the notebooks in order:

```
01_part1_linreg_1feature.ipynb
02_part2_polyreg.ipynb
```

Running all cells will train the models, generate plots, and demonstrate predictions.

## Running the tests

This project does not include automated test suites. Validation is performed through visual inspection of plots, convergence behavior, and comparison between predicted and actual values.

### End-to-end validation

The notebooks validate the models by:

- Plotting loss vs iterations to verify convergence
- Comparing predicted vs actual luminosity
- Evaluating cost behavior when modifying parameters

### Coding style checks

Code correctness is ensured by:

- Clear function definitions
- Consistent variable naming
- Vectorized NumPy operations where required

## Deployment

No live deployment is required. The notebooks are executed locally and on AWS SageMaker for validation purposes only. No endpoints, APIs, or MLOps pipelines are created.

## Built With

* Python – Programming language
* NumPy – Numerical computation
* Matplotlib – Data visualization
* Jupyter Notebook – Interactive execution environment
* AWS SageMaker – Cloud-based notebook execution

## Contributing

This project was developed as an academic assignment. 

## Versioning

Versioning is not applied, as this is a single-delivery academic project.

## Authors

* **Roger Alexander Rodriguez** 

## License

This project is for academic use only.

## Acknowledgments

- Course instructors and teaching assistants
- Provided laboratory notebooks and guidelines
- Open-source scientific Python community

---

## AWS SageMaker Execution Evidence

### Upload and Execution Description

Both notebooks were uploaded manually to AWS SageMaker Studio using the file upload option. Once uploaded, each notebook was opened and all cells were executed sequentially without modification.

### Evidence

The following evidence is included in this repository (as screenshots):

- Both notebooks visible and opened in AWS SageMaker
- Successful execution of all cells (no errors)
- At least one rendered plot from each notebook

**AWS - Sagemaker**

![Sagemaker](assets\Sagemaker.png)

**Execution of Notebook 1**

![Notebook 1](assets\Not1_1.png)

![Notebook 1](assets\Not1_2.png)

![Notebook 1](assets\Not1_3.png)

![Notebook 1](assets\Not1_4_Expe.png)

**Execution of Notebook 2**

![Notebook 1](\assets\Not2_1.png)

![Notebook 1](assets\Not2_2.png)

![Notebook 1](assets\Not2_3.png)


![Notebook 1](assets\Not2_4.png)

![Notebook 1](assets\Not2_4.png)

### Local vs Cloud Execution

The notebooks executed identically in both local and AWS SageMaker environments. No differences in results or behavior were observed, confirming environment consistency and reproducibility.


