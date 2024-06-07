To install a virtual environment, make sure you have either `conda` or `mamba` installed on your system. To install `conda` follow the instructions here: https://conda.io/projects/conda/en/latest/user-guide/install/index.html

Once you have installed `conda`, clone this repository in your local directory (such as `solar_reu_research`) by
```
git clone https://github.com/srijaniiserprinceton/cfa_reu.git
```
Now go into your clone repository directory using
```
cd cfa_reu
```
Install the `conda` environment using 
```
conda env create -f cfa_reu.yml
```
This will take 5-10 mins. If you are using `mamba` (normally resolves environment much faster than `conda`), you can run the above by simply changing `conda` to `mamba`.

You will know this has worked if it exits showing the following
```
# To activate this environment, use
#
#     $ conda activate cfa_reu
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```
At this point you should have an environent called `cfa_reu` in your list of `conda` environments. Check this using 
```
conda info --envs
```
You should see `cfa_reu` listed. Next activate your environment using
```
conda activate cfa_reu
```
If it activated correctly you should see something like this
```
(cfa_reu) bash-3.2$
```
instead of 
```
bash-3.2$
```
* **If you are on MACOS**
You can run the code in `ipython` by first starting an `ipython` kernel
```
(cfa_reu) bash-3.2$ ipython
```
and then running 
```
run astrospice_demo.py
```
* **If you are not on MACOS**
Run the code `astrospice_demo.py` in a `juypter notebook` to see if the environment works. To start a `jupyter` kernel, from your teminal run 
```
jupyter notebook
```
Open the notebook `astrospice_demo.ipynb` and execute the cell.
