# Building a Portfolio
we will use mkdocs to build our portfolio

link to [mkdocs](https://www.mkdocs.org/)

## 1. intall mkdocs

```bash
conda create -n mkdocs python=3.12 -y
conda activate mkdocs
pip install mkdocs
# python -m pip install mkdocs

## 2. create a new project
mkdocs new ishaque_portfolio
cd ishaque_portfoliomkdocs new ishaque_portfolio
cd ishaque_portfolio

## 3. run the development server
mkdocs serve

>> This is how you  specift the port and host name

mkdocs serve -a 127.0.0.1:8501
