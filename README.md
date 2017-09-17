# deep-learning-keras
Follows this (https://www.udemy.com/a-gentle-introduction-to-deep-learning-using-keras) udemy course

# Dependencies
1. Tensorflow 
    
    Install tensorflow in a virtualenv from: https://www.tensorflow.org/install

    For the following installs have the virtualenv running. Don't use `sudo` while installing in virtualenv
    
2. Keras

    Install keras using `pip` as follows: `pip install keras`. See this: https://keras.io/
    
3. Jupyter

    Install Jupyter also using `pip` as follows: `pip install jupyter`. 
    
    Create a new kernel using `python -m ipykernel install --user --name=<kernel-name>`. Use this kernel when creating notebooks or looking through downloaded course notebooks.
    
    See this: https://help.pythonanywhere.com/pages/IPythonNotebookVirtualenvs/
    
# Checks
Run jupyter server using `jupyter notebook`. This opens an interactive notebook in browser and loads up the current directory.

Create a new notebook(`New -> [kernel-name]`) using the kernel.

Check that keras is working properly, by importing these two libraries in the notebook

```python
   from keras.models import Sequential
   from keras.layers import Dense
```




    
    
