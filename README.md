# 🥩 Lista de Compras do Churrasco

Aplicação simples em **HTML + JavaScript** que gera automaticamente uma lista de compras para churrasco, calculando quantidades e valores de acordo com o número de pessoas.  

O usuário pode **remover itens individualmente** ou até **excluir uma seção inteira** (Carnes, Acompanhamentos, Bebidas, etc.).  
Se todos os itens de uma seção forem removidos, a seção desaparece automaticamente.  

---

## ✨ Funcionalidades

- ✅ Geração automática da lista de compras baseada em categorias (Carnes, Bebidas, Acompanhamentos e Extras).  
- ✅ Cálculo de quantidade por pessoa (multiplicação automática pelo número de convidados).  
- ✅ Cálculo do preço total de cada item.  
- ✅ Botão **❌** para remover itens individuais.  
- ✅ Remoção automática da seção se todos os itens forem apagados.  
- ✅ Botão **Excluir Seção** para remover categorias inteiras.  

---

## 🛠️ Tecnologias

- **HTML5** – estrutura da página  
- **CSS3** – estilos básicos  
- **JavaScript (puro)** – geração dinâmica da lista, cálculos e remoções  

---

## 📂 Estrutura do Projeto
```
├── index.html # Página principal com HTML, CSS e JS embutidos
└── README.md # Documentação do projeto
```

---

## 🚀 Como executar

1. Clone este repositório ou baixe os arquivos.  
   ```bash
   git clone https://github.com/seu-usuario/lista-churrasco.git
   ```
2. Abra o arquivo index.html diretamente no navegador.

3. A lista será gerada automaticamente.

---

## 📸 Demonstração

Carnes
- Picanha – 1.50 kg – R$ 97.50  ❌
- Fraldinha – 1.20 kg – R$ 42.00  ❌
[Excluir Seção]

### Após remover itens

- Itens podem ser removidos individualmente (❌).

- Se todos os itens de uma seção forem apagados → seção desaparece.

- Também é possível remover a seção inteira clicando em Excluir Seção.

---

## 🔮 Melhorias Futuras

- Adicionar botão para editar quantidades manualmente.

- Input para mudar o número de convidados dinamicamente.

- Exportar lista em PDF/CSV.

- Persistência em LocalStorage para manter a lista salva.

---

## 📄 Licença

Este projeto é de uso livre para estudos e melhorias. 🎉
