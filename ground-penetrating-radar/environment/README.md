
``gpr-env``
=========

Creating the `gpr-env` for GPR Preprocessing

Installing
----------
``conda env`` allows creating environments using a ``yml`` specification file
and install all of the dependencies from it. 

To create `gpr-env` with conda, run the following command in your root environment:

    conda env create -f gpr-env.yml

To activate the `gpr-env` in conda:

    conda activate gpr-env

Verify that the new environment was installed correctly:

    conda env list

  You can also use ``conda info --envs``

``gpr-env.yml``
------------------- 

Snippet of the Environment file

    name: ie-env
    channels:
      - plotly
      - conda-forge
      - anaconda
      - defaults
    dependencies:
      - alabaster=0.7.12=pyhd3eb1b0_0
      - anyio=3.5.0=py39haa95532_0
      - argon2-cffi=21.3.0=pyhd3eb1b0_0
      - argon2-cffi-bindings=21.2.0=py39h2bbff1b_0
      - arrow=1.2.3=py39haa95532_0
      - astroid=2.11.7=py39haa95532_0
      - asttokens=2.0.5=pyhd3eb1b0_0
      - atomicwrites=1.4.0=py_0
      - attrs=21.4.0=pyhd3eb1b0_0
      - autopep8=1.6.0=pyhd3eb1b0_1
      - babel=2.9.1=pyhd3eb1b0_0
      - backcall=0.2.0=pyhd3eb1b0_0
    prefix: C:\ProgramData\Anaconda3\envs\gpr-env
