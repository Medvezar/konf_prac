# Задание 1

Код для задание на языке Python:  
  
import matplotlib
print(matplotlib.__version__)  # Версия  
print(matplotlib.__file__)     # Путь к файлам пакета  
print(matplotlib.__doc__)      # Документация  
  
Комманды для bash без менеджера пакета, напрямую из репозитория(с установкой git):    
sudo apt-get update  
sudo apt-get install git  
git clone https://github.com/matplotlib/matplotlib.git  
  
cd matplotlib  
  
python3 -m venv venv  
source venv/bin/activate  
  
pip install -r requirements.txt  
python setup.py install  
  
# Задание 2  
вариант 1:  
  
npm install express  

cat node_modules/express/package.json  

пример содержания файла:  
![image](https://github.com/user-attachments/assets/6cd09bd7-9fed-4013-bedf-26804f6a7a08)
