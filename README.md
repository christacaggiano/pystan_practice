# Practice Exercises in PyStan

PyStan Jupyter notebooks created December 2018 for Zaitlen Lab @ UCLA

## To use these notebooks

Clone or fork this repository
```bash
git clone https://github.com/christacaggiano/pystan_practice.git

cd pystan_practice
```


Assuming installation of [anaconda or miniconda](https://www.anaconda.com/), create a clean stan environment using the provided `environment.yaml` file


**on linux**
```bash
conda env create -f environment.yml
conda activate stan
jupyter notebook
```

**on mac**
```bash
conda env create -f environment.yml
source activate stan
jupyter notebook
```

## Resources Consulted:

### Videos
* [Introduction to Bayesian Data Analysis and Stan with Andrew Gelman](https://www.youtube.com/watch?v=T1gYvX5c2sM)
* [A visual guide to Bayesian Thinking](https://www.youtube.com/watch?v=BrK7X_XlGB8)
* [PyStan: Bayesian inference for fun and for profit](https://www.youtube.com/watch?v=tjiLOTRwpfY)
* [Should this drug be approved? A Bayesian's answer with Pystan](https://www.youtube.com/watch?v=piQvcVala9I&t=153s)

### Blogs
* [Beginners Exercise: Bayesian computation with Stan and Farmer Jöns
](http://www.sumsar.net/files/posts/2017-01-15-bayesian-computation-with-stan-and-farmer-jons/stan_exercise.html)
* [An Introduction to Bayesian Inference in Pystan](https://towardsdatascience.com/an-introduction-to-bayesian-inference-in-pystan-c27078e58d53)

### Books
* [*Bayesian Data Analysis*, Gelman et al](https://the-eye.eu/public/Books/qt.vidyagam.es/library/Monitoring%20and%20Analysis/Bayesian%20Data%20Analysis%2C%20Third%20Edition/Bayesian%20Data%20Analysis%2C%20Third%20Edition%20-%20Andrew%20Gelman%20%26%20John%20B.%20Carlin%20%26%20Hal%20S.%20Stern%20%26%20David%20B.%20Dunson%20%26%20Aki%20Vehtari%20%26%20Donald%20B.%20Rubin.pdf)


### Documentation
* [Stan Documentation](https://mc-stan.org/docs/2_18/reference-manual/analysis-chapter.html)
* [PyStan Documentation](https://pystan.readthedocs.io/en/latest/)
* [Conda documentation](https://conda.io/docs/user-guide/tasks/manage-environments.html)
