# Data analysis
- Document here the project: BH_Housing_Prices
- Description: This is a Data Science project that aims on evaluating the price range
and the correleation of features of several available houses in Belo Horizonte/Brazil.
The main goal of this project is to get a glimpse of good investments opportunities
within the city's real estate market.
- Data Source: Kaggle
- Type of analysis:

Please document the project the better you can.

# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for BH_Housing_Prices in gitlab.com/{group}.
If your project is not set please add it:

- Create a new project on `gitlab.com/{group}/BH_Housing_Prices`
- Then populate it:

```bash
##   e.g. if group is "{group}" and project_name is "BH_Housing_Prices"
git remote add origin git@github.com:{group}/BH_Housing_Prices.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
BH_Housing_Prices-run
```

# Install

Go to `https://github.com/{group}/BH_Housing_Prices` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:{group}/BH_Housing_Prices.git
cd BH_Housing_Prices
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
BH_Housing_Prices-run
```
