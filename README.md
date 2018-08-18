A [zsh] _[Jupyter]_ kernel
==========================
This requires [IPython] 3.

Install
-------
~~~ sh
pip install zsh_kernel
python -m zsh_kernel.install
~~~

To use it, run one of:
~~~ sh
jupyter notebook
# In the notebook interface, select zsh from the 'New' menu
jupyter qtconsole --kernel zsh
jupyter console --kernel zsh
~~~

For details of how this works, see the Jupyter docs on `wrapper kernels`_, and
Pexpect's docs on the `replwrap module`_


License
-------
[MIT] © [Daniel Bayley]

[MIT]:              LICENSE.md
[Daniel Bayley]:    https://github.com/danielbayley

[zsh]:              http://zsh.org
[ipython]:          https://ipython.readthedocs.io
[jupyter]:          http://jupyter.org

[wrapper]:          http://jupyter-client.readthedocs.org/en/latest/wrapperkernels.html
[pexpect]:          http://pexpect.readthedocs.org/en/latest/api/replwrap.html
