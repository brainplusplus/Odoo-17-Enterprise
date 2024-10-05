pip install virtualenv
pip install --upgrade pip setuptools wheel
python -m venv env
source env/bin/activate
env/Scripts/activate.bat //In CMD
env/Scripts/Activate.ps1 //In Powershel
pip install -r requirements.txt --use-pep517
python odoo-bin --config=odoo.conf


pip3 install virtualenv
pip3 install --upgrade pip setuptools wheel
python3 -m venv env
source env/bin/activate
env/Scripts/activate.bat //In CMD
env/Scripts/Activate.ps1 //In Powershel
pip3 install -r requirements.txt --use-pep517
python3 odoo-bin --config=odoo.conf
sudo apt-get install libpq-dev
sudo apt-get install libsasl2-dev python-dev-is-python3 libldap2-dev libssl-dev

python --version
python3 --version

# Add additional repository to download python 3.11
sudo add-apt-repository ppa:deadsnakes/ppa

# This might take more than few minutes
sudo apt update
sudo apt upgrade

# Install python 3.11
sudo apt-get install python3.11

# python3 shows 3.10 and python3.11 shows 3.11 as version
python3 --version
python3.11 --version

sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.10 1
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.11 1

sudo update-alternatives --config python3
#choose 2 for python 3.11

# In case if you have problem with open…

INSERT INTO public.ir_config_parameter (id, create_uid, write_uid, key, value, create_date, write_date) VALUES (DEFAULT, 2, 2, 'database.expiration_date', '2050-11-04 11:40:02', '2024-10-05 15:12:30.000000', '2024-10-05 15:12:39.000000')

UPDATE public.ir_config_parameter SET value = '2040-11-04 11:40:02' WHERE key = 'database.expiration_date'

INSERT INTO public.ir_config_parameter (id, create_uid, write_uid, key, value, create_date, write_date) VALUES (DEFAULT, 2, 2, 'database.expiration_reason', 'none', '2024-10-05 15:12:34.000000', '2024-10-05 15:12:41.000000')