# Setting up Conda Environment, and a short guide to use Conda command.

1. After setting up Conda, you should be able to access Anaconda Prompt. It should look something like this:

```python
(base) C:\Windows\System32>
```

2. Setting up the environment. Rename "myenv" as you wish. Next, setup Python version.

```python
(base) C:\Windows\System32>conda create -n myenv python=3.9
```

3. Activate your new working environment.

```python
(base) C:\Windows\System32>conda activate myenv # replace myenv to your new environment name
(Your environment name) C:\Windows\System32>
```

4. If you want to deactivate your new working environment.

```python
(Your environment name) C:\Windows\System32>conda deactivate
(base) C:\Windows\System32>
```

5. If you want to delete your working environment.

```python
(base) C:\Windows\System32>conda env remove --name myenv # replace your environment name here
```

6. Checking all working environments you created.

```python
(base) C:\Windows\System32>conda env list
```

7. Checking Conda version.

```python
(base) C:\Windows\System32>conda --version
```

8. Update Conda version if needed.

```python
(base) C:\Windows\System32>conda update conda
```

9. Assuming you installed all the packages using Conda, and you can update them this way.

```python
(Your environment name) C:\Windows\System32>conda update --all # this way update all the outdate pkgs
(Your environment name) C:\Windows\System32>conda update package_name # this way only update the specific pkg
```

10. If you use pip to install pkgs, you can also update them this way.

```python
(Your environment name) C:\Windows\System32>pip list --outdated
(Your environment name) C:\Windows\System32>pip install --upgrade package_name
```

### Note:

For geospatial analyses Python modules and install guide, refer to my page: [Python Packages](https://github.com/Fangsheng-Zhou/Python_Modules_For_Geospatial_Analyses)
