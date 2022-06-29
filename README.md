## Install

- Install Anaconda/Miniconda
- Create conda env
- Activate the environment
- Run the following command:

    `while read requirement; do conda install --yes $requirement || pip install $requirement; done < requirements.txt`