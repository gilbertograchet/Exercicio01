<h4 align="center">
⬇️ * # Exercicio01 # * ⬇️
</h4>
<h4 align="center">
  * Exercicio01_CICD_Impacta: *
</h4>

<h4>
  ! CONFIGS INICIAIS !
<h4> 
   R: 
<h4>
</h4>
</h4>
</h4>
<h4>


 
![image](https://github.com/user-attachments/assets/5755be24-1d9b-46f0-ad6b-4e6811ef8de0)


A) No working dir, executar o comando:
   echo 01 > arquivo.txt
<h4> 
   R: 
<h4>   
</h4>
</h4>
</h4>
<h4>


![image](https://github.com/user-attachments/assets/0b8b502e-3044-4db5-a18f-239a5d3d60ab)


B) Adicionar o arquivo no staging e conferir o status:
<h4> 
 R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4> 
<h4>
</h4>
</h4>
</h4>
<h4>



![image](https://github.com/user-attachments/assets/536812c2-40e0-495e-be8e-3107b18132bc)


C) Commitar o arquivo do staging com a descrição "git add example - arquivo.txt":
<h4> 
R:
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "git add example - arquivo.txt" .
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![image](https://github.com/user-attachments/assets/023c70d9-43d0-40cf-b75c-1d295c36e351)


D) Sobrescrever o conteúdo do arquivo.txt:
   echo 02 > arquivo.txt
<h4> 
R:
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 02 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](https://github.com/user-attachments/assets/7520a5c7-1e1d-46e9-b13b-734e45acb9ca)


E) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



![image](https://github.com/user-attachments/assets/7cd1ca6e-b3dc-4f56-b23a-9076917bdf56)



F) Adicionar novamente o arquivo no staging e conferir o status:
<h4>
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](https://github.com/user-attachments/assets/1c9e652b-5d55-4c59-918b-ce71bf8665f3)


G) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>




H) Sobrescrever o conteúdo do arquivo.txt:
 echo 03 > arquivo.txt
<h4>
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 03 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![image](https://github.com/user-attachments/assets/a56cfb03-c8ba-4b49-a542-4aa78858e9c4)


I) Verificar o diffing no arquivo:
<h4>
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



![image](https://github.com/user-attachments/assets/834d4bd9-cc1b-4a48-bc84-60b70edd8f15)


J) Fazer o restore do arquivo da área de staging e verificar o status:
<h4>
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git restore arquivo.txt 
</h4>
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![image](https://github.com/user-attachments/assets/8138cc89-737b-467d-a53d-c6f605f9d971)


K) Realizar o commit do arquivo e verificar o log:
<h4>
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "Primeiro Commit - Arquivo.txt"
</h4>
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git log
<h4>
</h4>
</h4>
</h4>
<h4>

![image](https://github.com/user-attachments/assets/8dd378d3-d043-4ead-a0da-ae061b0ac8e1)

![image](https://github.com/user-attachments/assets/af3218c8-f95b-42a4-8d32-4e7a9415d028)


L) Adicionar um arquivo gitignore com o seguinte conteúdo:
 *.txt
<h4> 
R: 
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ vi .gitignore
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](https://github.com/user-attachments/assets/6442f7b5-94a4-4f30-8014-5fbbed7999ae)


M) Criar um arquivo novo.txt e verificar o status:
<h4> 
R:
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > novo.txt
</h4>
<h4>
@gilbertograchet ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![image](https://github.com/user-attachments/assets/bdd99fb3-17e7-4c33-aaa7-dfcabe3e421e)










  







   



   


 





  


 











