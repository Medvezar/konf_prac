# Задача 1 Решение:

sed 's/:.*//' /etc/passwd > data.txt   
sort data.txt 

![image](https://github.com/user-attachments/assets/f25d0384-7a90-44db-99de-b386ddf57222)

# Задача 2 Решение:

sed 's/#.*//' /etc/protocols | sort -ru -nk2 > data.txt  
head -5 data.txt

![image](https://github.com/user-attachments/assets/0c26160e-8ac9-4e1b-8a42-dab7a778c387)

# Задача 3 Решение:

touch myscript.sv  
nano myscript.sv  
-вложение файла-  
#!/bin/bash  
  
text=$*  
length=${#text}  


for _ in \$(seq 1 \$((length + 2))); do  
    line+="-"  
done  
  
echo "+${line}+"  
echo "| ${text} |"  
echo "+${line}+"  
-конец файла-  
chmod +x ./myscript  
![image](https://github.com/user-attachments/assets/a1abfd77-7340-4a72-959c-39d16fb6b31f)

