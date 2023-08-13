# karyar-python-projects-template

Hello dear students and welcome.
To create your project, just simply [use this template](https://github.com/new?template_name=karyar-python-projects-template).


# Installation

To Start developing using this template you need to follow these steps:

1 - Create a virtual environment:

```bash
python -m venv env
```

2 - Activate the virtual environment:

- Windows:

```bash
env/Scripts/activate
```

- Mac/Linux:

```bash
source env/bin/activate
```

3 - Install the required packages:

```bash
pip install -r requirements.txt
```

4 - Install pre-commit to your `.git/hooks/`:
```bash
pre-commit install
```

Also make sure you autoupdate pre-commit if you faced any issues:
```bash
pre-commit autoupdate
```


5 - Start developing your project and we wish you the best ;)


# Commiting
You may have noticed we are using pre-commit that checks many things
and lowers the risks of implementing disasters.
pre-commit checks before you commit your changes
and if anything goes wrong, you cannot commit.
Fix the errors and try to commit again and you're good to go.
If you want to run pre-commit without commiting you can run:
```bash
pre-commit run -a
```
