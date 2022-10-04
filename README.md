# HTML/CSS - BIOLOGIA
### YU E MICAEL

- https://ocamilinho.github.io/IFRJ_Biologia/

Esse arquivo é um pequena guia com os comando do git da parte de frontend. além de que serve como entendimento geral 
## Vantagens do uso:
- atualização dos códigos
- trabaho em equipe
- nuvem

## Comandos principais:

### !Importante!
crie um clone do projeto no seu computador!
```git
git clone "https://github.com/Ocamilinho/IFRJ_Biologia/"
```



existem algumas principais ações para uso do git. Veja:

1. inicialização geral do git
2. incialização e conexão com a branch
3. salvar dados e arquivos com commit 
4. sincronzar github com o commit 


### Inicialização do git

É fundamental que inicie ele em alguma pasta do pc,pois dessa forma ele vai fica monitorando as atualizações.São dois os comandos principais:
```git
git init                      \\ Inicia o monitoramento da pasta
```

### Conexão com o github/branch
Para conseguirmos subir os arquivos no "servidor",precisamos necessariament estar conectado com ele e saber manusear as branchs que funcionam como pequenas áreas de trabalho onde podemos salvar partes dos projeto

```git
<<<<<<< HEAD
git remote remove origin \\ Caso der erro ao usar git remote add...
=======
>>>>>>> 2d8a1bcb509e2e70e944635402b76ced5b2a0eeb
git remote add origin https://github.com/[username]/IFRJ_Biologia/  \\ Sincronizaçao com o projeto(Mudem apenas o link)
git checkout [Nome da branch]                                       \\ Mobilidade entre as branchs
```

### Commit e Sincronização 

```git
git add *                                                             \\ adiciona todos os arquivos no origin (área "virtual" para preparação)
git commit -m [nome do commit]                                        \\ atuaização com definicão do nome 
git push origin main                                                  \\ sincroniza origin na branch pesquisa
git pull https://github.com/[username]/IFRJ_Biologia/                 \\ Atualiza todos os arquivos da sua branch
```
