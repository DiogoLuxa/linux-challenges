# 🐧 Desafio 03 – Visualização de conteúdo (`cat`, `less`, `head`, `tail`)  

[Voltar ao Sumário](../SUMARIO.md)

## 🧩 Enunciado  
Crie um pequeno roteiro de comandos no terminal que:  

- Crie um arquivo chamado `notas.txt`.  
- Adicione algumas linhas de texto dentro dele.  
- Visualize o conteúdo completo do arquivo.  
- Visualize o conteúdo do arquivo página por página.  
- Mostre apenas as 3 primeiras linhas do arquivo.  
- Mostre apenas as 2 últimas linhas do arquivo.  

O objetivo é praticar os comandos de visualização de conteúdo no Linux.  

---

## 💡 Dica  
- Use `echo "texto" >> arquivo` para adicionar linhas a um arquivo.  
- Use `cat` para exibir o conteúdo completo.  
- Use `less` para visualizar o conteúdo de forma paginada.  
- Use `head -n X` para mostrar as primeiras linhas.  
- Use `tail -n X` para mostrar as últimas linhas.  

---

## 💻 Solução  
```bash
touch notas.txt
echo "Primeira linha" >> notas.txt
echo "Segunda linha" >> notas.txt
echo "Terceira linha" >> notas.txt
echo "Quarta linha" >> notas.txt
cat notas.txt
less notas.txt (para sair, pressione 'q')
head -n 3 notas.txt
tail -n 2 notas.txt
```

---

## 🧠 Explicação  
- `touch notas.txt` cria o arquivo vazio.  
- `echo "texto" >> notas.txt` adiciona linhas de texto ao arquivo.  
- `cat notas.txt` mostra todo o conteúdo de uma vez.  
- `less notas.txt` permite navegar pelo conteúdo com as setas (pressione `q` para sair).  
- `head -n 3 notas.txt` mostra apenas as 3 primeiras linhas.  
- `tail -n 2 notas.txt` mostra apenas as 2 últimas linhas.  

---

## ✅ Exemplo de saída  
```bash
Primeira linha
Segunda linha
Terceira linha
Quarta linha
```

*(após o comando `cat notas.txt`)*  

---

ℹ️ Esse exercício é ótimo para aprender a inspecionar arquivos de texto no terminal Linux, especialmente quando eles são grandes.  

- [Desafio anterior → Desafio 02](./desafio_02.md)
- [Próximo desafio → Desafio 04](./desafio_04.md)
