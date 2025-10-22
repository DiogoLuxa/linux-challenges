# 🐚 Desafio 01 – Navegação no sistema de arquivos (`pwd`, `ls`, `cd`)  

[Voltar ao Sumário](../SUMARIO.md)

## 🧩 Enunciado  
Crie um pequeno roteiro de comandos no terminal que:  
1. Mostre o diretório atual.  
2. Liste todos os arquivos e pastas dentro dele.  
3. Acesse a pasta `Documentos`.  
4. Dentro dela, liste novamente o conteúdo.  

O objetivo é praticar os comandos básicos de navegação no sistema de arquivos.  

---

## 💡 Dica  
- Use `pwd` para exibir o caminho do diretório atual.  
- Use `ls` para listar arquivos e pastas.  
- Use `cd nome_da_pasta` para mudar de diretório.  

---

## 💻 Solução  
```bash
pwd
ls
cd Documentos
ls
```

---

## 🧠 Explicação  
- `pwd` (print working directory) mostra em qual diretório você está no momento.  
- `ls` lista o conteúdo do diretório atual.  
- `cd Documentos` muda o diretório de trabalho para a pasta `Documentos`.  
- O segundo `ls` mostra o que existe dentro da pasta `Documentos`.  

---

## ✅ Exemplo de saída  
```bash
/home/usuario
Área de Trabalho  Documentos  Downloads  Imagens
arquivo1.txt  arquivo2.pdf
```

>ℹ️ Esse exercício é ideal para quem está começando no terminal e quer se familiarizar com os comandos básicos de navegação.  

---

- [Próximo desafio → Desafio 02](./desafio_02.md)