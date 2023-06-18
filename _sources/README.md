![logo](images/cnpa_banner.png)

# Complex Networks Palermo

This repository is the official database for the [_Complex Networks (21958)_](https://www.unipa.it/persone/docenti/m/salvatore.micciche/?pagina=insegnamento&idInsegnamento=155641&idCattedra=149802) course by [**Salvatore Miccichè**](https://www.unipa.it/persone/docenti/m/salvatore.micciche/) in [Università degli Studi di Palermo](https://www.unipa.it/). This repository was made by [**Alessandro Romancino**](https://github.com/alex180500) and is distributed under the [MIT LICENSE](LICENSE).

The code is uploaded in a book made with [Jupyter Book](https://jupyterbook.org/en/stable/intro.html) which is available at the following website: \
[**https://cnpalermo.github.io/complex-networks-palermo/**](https://cnpalermo.github.io/complex-networks-palermo/)

## Book Structure

The **Complex Networks** section will contain the bulk of the course code, with all most useful functions and explainations. The **Tutorials** section will instead focus on less general but still didactic examples. The **Contributions** section instead contains all the code produced by students.

```{tableofcontents}
```

## Acknowledgments

Thanks for the contributions by [**Alessandro Ferrara**](https://github.com/Pherrara). Thanks also to **Mattia Romeo** for the various code snippets.

There are many useful general resources for Complex Networks: \
{cite:t}`newman,latora`

### Bibliography
```{bibliography}
:style: unsrt
```

## Running the Code

If you want to run the notebooks locally and have an hands on approach go ahead and download all the contents directly from the main [GitHub Page over here](https://github.com/CNPalermo/complex-networks-palermo).

A general tutorial on how to install Python is present (italian only for now) at: \
[https://github.com/alex180500/aisf-corso-python](https://github.com/alex180500/aisf-corso-python)

### Dependencies

You just need these packages (versions are the only one tested):
- numpy **≥ 1.24** _(for numerical calculations)_
- python-igraph **≥ 0.10** _(for most of the graph functions)_
- matplotlib **≥ 3.6** _(for general plotting)_
- pycairo **≥ 1.23** _(for all the igraph plots)_

### Contributing

Please, if you make an exercise or some cool Complex Network code, you are **encouraged** to add it here. Also, feel free to open discussions on the Issue page and issuing your pull requests!

Please make sure your code is well documented following a format similar to the notebooks present in this repository. In order to add your files just follow these steps:

- Fork the project on your profile
- Create your branch `git checkout -b feature`
- Commit your changes with your files in the contributions folder `git commit -m 'added these features here'` (**please provide good comments!**)
- Push to your branch `git push origin feature`
- Open a pull request here

## Roadmap

- [x] Add tutorials for data import and the CN logo
- [ ] igraph cheatsheet
- [ ] Add various model constructores
- [ ] Add conda guide and how to install python
- [ ] Jupyter guide
- [ ] Git guide





