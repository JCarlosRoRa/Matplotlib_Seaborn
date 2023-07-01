


Requisito previos 

```sh

sudo apt install -y python3-pip
sudo apt install -y git

```


instalacion de venv con wsl

```sh

sudo apt install -y python3-venv
mkdir ##carpeta del proyecto
cd ## carpeta del proyecto 
python3 -m venv env 
source env/bin/activate 



```

instalacion de modulos del proyecto 

i

```sh

pip install matplotlib
pip3 freeze
pip3 freeze > requirenments.txt
pip3 install -r requirenments.txt
deactivate


```