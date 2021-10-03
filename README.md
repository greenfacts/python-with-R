# python-with-R

# Installing and running R and Python together within juypyter
1. Install R base
2. Create and activate a virtual environment to work with R and Python
3. pip install rpy2
4. Add the Virtual Environment to Jupyter Notebook  
  a. pip install --user ipykernel  
  b. python -m ipykernel install --user --name=myenv  
5. Launch Jupyter
6. Add this to the first block: %load_ext rpy2.ipython
7. Use this as the first line in an R code block: %%R
8. Export R variables to Python: %R -o my_R_variable
9. Export Python variables to R: %R -i my_Python_variable

References
- https://www.marsja.se/r-from-python-rpy2-tutorial/
- https://janakiev.com/blog/jupyter-virtual-envs/
