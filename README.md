# compila_pdf
# 🔗 Merge de PDFs com Python — Ordenação Natural (Hotmart)

Este projeto resolve um problema comum: unir vários arquivos PDF gerados por plataformas como a Hotmart, que vêm soltos e fora de ordem.

Usando Python, organizamos os arquivos com ordenação **natural** (isto é, respeitando `relatorio2.pdf` antes de `relatorio10.pdf`) e fundimos tudo em um único documento final.

---

## 📂 Exemplo de problema

Arquivos recebidos assim:
```
relatorio1.pdf
relatorio10.pdf
relatorio2.pdf
```

Ordem errada? Comum. Solução? Automação. ✅

---

## 🧠 Como funciona

1. Lê todos os arquivos `.pdf` da pasta indicada (`hotmart/`);
2. Ordena os arquivos numericamente, mesmo com nomes de texto;
3. Junta tudo em um único PDF chamado `hotmart_final.pdf`.

---

## 🛠️ Tecnologias

- Python 3.8+
- [PyPDF2](https://pypi.org/project/pypdf2/) ou [pypdf](https://pypi.org/project/pypdf/) (dependendo da versão instalada)

---

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/pdf-merge-hotmart.git
cd pdf-merge-hotmart
```

Instale as dependências:

```bash
pip install pypdf
```

---

## 🚀 Como usar

1. Coloque seus arquivos PDF na pasta `hotmart/`;
2. Execute o script:

```bash
python pdfsconsolidados.py
```

3. O arquivo `hotmart_final.pdf` será criado no mesmo diretório.

---

## 📌 Observação

A ordenação natural é feita com uma função que separa números de letras no nome dos arquivos. Assim, evita o erro comum da ordenação alfabética.

---

## 🎥 Vídeo de demonstração

> [🔗 Assista aqui](#) – *link do vídeo quando publicar no LinkedIn ou YouTube*

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — fique à vontade para usar, adaptar e compartilhar!

---

## 🙋‍♂️ Autor

Feito com Python e um pouco de cafeína por [Turco](https://www.linkedin.com/in/seu-perfil).

