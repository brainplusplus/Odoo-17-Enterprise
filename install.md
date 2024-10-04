pip install virtualenv
pip install --upgrade pip setuptools wheel
python -m venv env
source env/bin/activate
env/Scripts/activate.bat //In CMD
env/Scripts/Activate.ps1 //In Powershel
pip install -r requirements.txt --use-pep517
python odoo-bin --config=odoo.conf
