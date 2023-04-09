# `nlterm`: Integrate ChatGPT in your terminal

# Install
```
pip install nlterm
```

# Example

- Example 1
````
> nlterm
Instruction: reorgnize this folder to like a pypi project. That is I need to put scripts in `src` folder, and have a basic `pyproject.toml`
````
This is the output:
````
```
mkdir src
mv *.py src
touch pyproject.toml
```
Execute? (y/n): 
````

- Example 2
````
> nlterm
Instruction: Install the whl file
````

This is the output:
````
```
pip install nlterm-0.0.2-py3-none-any.whl
```
Execute? (y/n): 
````

- Example 3
Suppose we have files `Chest_xray_report.pdf` and `immunization.pdf` in the current directory.

````
> nlterm
Instruction: merge my chest ray report and immunization
````
This is the output:
````
```
pdftk Chest_xray_report.pdf immunization.pdf output merged_file.pdf
```
Execute? (y/n): 
````
