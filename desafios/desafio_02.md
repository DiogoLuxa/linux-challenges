# 🐧 Desafio 02 – Criação e remoção de arquivos e diretórios (`touch`, `mkdir`, `rm`)  

[Voltar ao Sumário](../SUMARIO.md)

## 🧩 Enunciado  
Crie um pequeno roteiro de comandos no terminal que:  
- Crie uma nova pasta chamada `projetos`.  
- Acesse essa nova pasta.  
- Crie um arquivo chamado `leia-me.txt` dentro dela.  
- Liste o conteúdo da pasta para verificar se o arquivo foi criado.  
- Remova o arquivo `leia-me.txt`.  
- Volte para o diretório anterior.  
- Remova a pasta `projetos`.  

O objetivo é praticar a criação e exclusão de arquivos e diretórios no Linux.  

---

## 💡 Dica  
- Use `mkdir` para criar uma nova pasta.  
- Use `touch` para criar um arquivo vazio.  
- Use `rm` para remover arquivos.  
- Use `rmdir` para remover pastas vazias.  
- Use `cd ..` para voltar ao diretório anterior.  

---

## 💻 Solução  
```bash
mkdir projetos
cd projetos
touch leia-me.txt
ls
rm leia-me.txt
cd ..
rmdir projetos
```

---

## 🧠 Explicação  
- `mkdir projetos` cria uma pasta chamada `projetos`.  
- `cd projetos` acessa essa pasta.  
- `touch leia-me.txt` cria um arquivo vazio com esse nome.  
- `ls` lista o conteúdo da pasta atual.  
- `rm leia-me.txt` remove o arquivo.  
- `cd ..` volta ao diretório anterior.  
- `rmdir projetos` remove a pasta (desde que esteja vazia).  

---

## ✅ Exemplo de saída  
```bash
leia-me.txt
```

*(após o comando `ls`, antes da remoção do arquivo)*  

---

ℹ️ Esse exercício é ideal para quem está começando a usar o terminal Linux e quer aprender a manipular arquivos e pastas com segurança.  

- [Desafio anterior → Desafio 01](./desafio_01.md)
- [Próximo desafio → Desafio 03](./desafio_03.md)