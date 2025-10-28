# 🐧 Desafio 04 – Copiando arquivos e diretórios (`cp`)  

[Voltar ao Sumário](../SUMARIO.md)

## 🧩 Enunciado  
Crie um pequeno roteiro de comandos no terminal que:  

- Crie um arquivo chamado `lista.txt`.  
- Adicione algumas linhas de texto dentro dele.  
- Faça uma cópia desse arquivo com o nome `lista_backup.txt`.  
- Crie uma pasta chamada `backup`.  
- Copie o arquivo `lista_backup.txt` para dentro da pasta `backup`.  
- Liste o conteúdo da pasta `backup` para verificar se a cópia foi feita corretamente.  

O objetivo é praticar o uso do comando `cp` para copiar arquivos e diretórios no Linux.  

---

## 💡 Dica  
- Use `echo "texto" >> arquivo` para adicionar linhas a um arquivo.  
- Use `cp arquivo destino` para copiar arquivos.  
- Use `cp -r pasta destino` para copiar diretórios inteiros.  
- Use `ls` para verificar o conteúdo de uma pasta.  

---

## 💻 Solução  
```bash
touch lista.txt
echo "Item 1" >> lista.txt
echo "Item 2" >> lista.txt
echo "Item 3" >> lista.txt
cp lista.txt lista_backup.txt
mkdir backup
cp lista_backup.txt backup/
ls backup
```

---

## 🧠 Explicação  
- `touch lista.txt` cria o arquivo vazio.  
- `echo "texto" >> lista.txt` adiciona linhas de texto ao arquivo.  
- `cp lista.txt lista_backup.txt` cria uma cópia do arquivo com outro nome.  
- `mkdir backup` cria uma nova pasta chamada `backup`.  
- `cp lista_backup.txt backup/` copia o arquivo para dentro da pasta.  
- `ls backup` lista o conteúdo da pasta `backup`, mostrando o arquivo copiado.  

---

## ✅ Exemplo de saída  
```bash
lista_backup.txt
```

*(após o comando `ls backup`)*  

---

ℹ️ Esse exercício é ótimo para aprender a duplicar arquivos e organizar cópias de segurança no terminal Linux.  

- [Desafio anterior → Desafio 03](./desafio_03.md)
- [Próximo desafio → Desafio 05](./desafio_05.md)