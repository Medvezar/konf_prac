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


# Задача 4 Решение:
-содержание файла-  
![image](https://github.com/user-attachments/assets/2483513c-a5d1-4c12-862c-9e54f6675078)

-результат-  
![image](https://github.com/user-attachments/assets/41d92743-2690-4e14-866d-bbe40bff3dc1)

# Задача 5 Решение:
-содержание файла-  
![image](https://github.com/user-attachments/assets/f07f8732-b76c-41e2-9108-c00e856144d2)
-результат-  
![image](https://github.com/user-attachments/assets/a39cb1bd-a077-4683-88a8-cafad8ff6180)

# Задача 6 Решение:
-содержание файла-  
![image](https://github.com/user-attachments/assets/72069a73-d028-457b-af1e-be82fda7e1f5)

