# Desafio de Projeto Sobre Git/GitHub da DIO
Repositório Criado Para O Desafio de Projeto.

## Links Úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)

### O que é GIT e GitHub?

GIT: É um sistma de contole de versão.
 
GitHub: É uma Plataforma para Gerenciamento de Código de Criação de um Ambiente 
  Colaborativo entre os Desenvolvedores, Ultilizando o Git como Sistema de Controle.
  
 ### O que é Git Bash?
  
 Git Bash: É um terminal para otimizar o uso do Git.
  
  
 ## Configuração Básicas
  
 É importante nos identificarmos para o Git, informando nosso nome e e-mail. no seu terminal, execute os comandos:
  
       git config --global user.name "Seu Nome"
       git config --global user.email seuemail@gmail.com
  
 
  ## Criando um novo repositório
  
  Crie uma pasta ou abra o terminal no diretório e execute o comando:
    
            git init
    
    
  ## Rastreando os arquivos
     
  Podemos ver a situação dos arquivos no repositório Git com o comando:
  
             git status
         
   
   Você para adicionar arquivos no repositório devemos executar o seguinte comando:
   
             git add "nome do arquivo"
      
   
   Para fazer adicionar todos os ficheiros de uma só vez executamos o seguinte comando:
      
             git add *
       
   
   ## Enviando alterações
    
   Para gravarmos as mudanças no repositório (fazer o commit), devemos executar o comando:
    
             
             git commit -m "comentários das alterações que fizeste"
         
   
   ## Preparando seu projeto para o GitHub
    
             git remote add origin https://github.com/seunome/repositorio.git
    
   
   ## Enviando as alterações para o GitHub
     
   Com o repositório remoto configurado, podemos enviar nossas mudanças para o GitHub basta executar o comando git push, da seguinte forma:
                
              git push origin master
    
    
    
