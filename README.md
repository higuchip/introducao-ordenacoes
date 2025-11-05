# Introdução às Ordenações

> Material didático sobre análises de ordenação (PCA, NMDS, PCoA) para dados de vegetação

[![R](https://img.shields.io/badge/R-%3E%3D%204.0.0-blue)](https://www.r-project.org/)

## 📚 Sobre

Este repositório contém material didático desenvolvido para a disciplina **Descrição e Análise da Vegetação** da UDESC (Universidade do Estado de Santa Catarina). O objetivo é ensinar técnicas de ordenação para análise de dados ecológicos de forma prática e acessível.

### 🎯 Tópicos Abordados

- **PCA** (Análise de Componentes Principais) - Para dados ambientais
- **PCoA** (Análise de Coordenadas Principais) - Ordenação métrica
- **NMDS** (Escalonamento Multidimensional Não-Métrico) - Ordenação não-métrica
- **envfit** - Ajuste de variáveis ambientais
- **PERMANOVA** - Teste de diferenças multivariadas
- **betadisper** - Análise de dispersão

## 📊 Apresentação

**[🔗 Acesse a apresentação online](https://seu-usuario.github.io/introducao-ordenacoes/)**

## 📁 Estrutura do Repositório

```
introducao-ordenacoes/
├── slides/
│   ├── introducao-ordenacoes.qmd    # Arquivo fonte Quarto
│   └── introducao-ordenacoes.html   # Apresentação renderizada
├── data/
│   ├── environmental_data.csv       # Dados de solo
│   └── vegetation_data.csv          # Dados de vegetação
├── README.md
└── .gitignore
```

## 🚀 Como Usar

### Opção 1: Visualizar Online
Acesse diretamente a apresentação através do link do GitHub Pages (acima).

### Opção 2: Rodar Localmente

**Pré-requisitos:**
- R (versão ≥ 4.0.0)
- RStudio (recomendado)
- Quarto CLI

**Pacotes R necessários:**
```r
install.packages(c("vegan", "dplyr", "knitr", "DiagrammeR"))
```

**Clonar o repositório:**
```bash
git clone https://github.com/seu-usuario/introducao-ordenacoes.git
cd introducao-ordenacoes
```

**Renderizar a apresentação:**
```r
# No RStudio, abra o arquivo .qmd e clique em "Render"
# Ou via linha de comando:
quarto render slides/introducao-ordenacoes.qmd
```

## 📖 Dados Exemplo

Os dados utilizados são da **Floresta Ombrófila Mista (Floresta com Araucária)** do Planalto Catarinense:

- **50 parcelas** de vegetação
- **90 espécies** arbóreas
- **2.837 indivíduos** amostrados
- **Variáveis ambientais**: pH, nutrientes (P, K, Ca, Mg), matéria orgânica, altitude, declividade

## 🎓 Para Estudantes

### Antes da Aula
1. Instale R e RStudio
2. Instale os pacotes necessários (veja acima)
3. Revise conceitos básicos de ecologia de comunidades

### Durante a Aula
- Siga a apresentação online
- Execute os códigos no seu R
- Experimente modificar parâmetros

### Depois da Aula
- Pratique com seus próprios dados
- Explore a documentação do pacote `vegan`
- Leia os artigos de referência (abaixo)

## 📚 Referências Principais

- Borcard, D., Gillet, F., & Legendre, P. (2018). *Numerical Ecology with R*. Springer.
- Legendre, P., & Legendre, L. (2012). *Numerical Ecology* (3rd ed.). Elsevier.
- Oksanen, J. et al. (2022). vegan: Community Ecology Package. R package.
- Zelený, D. (2023). *Analysis of community ecology data in R*. https://www.davidzeleny.net/anadat-r/

## 👨‍🏫 Autor

**Prof. Pedro Higuchi**  
📧 Email: [higuchip@gmail.com]  
🏫 UDESC - Universidade do Estado de Santa Catarina  


## 🤝 Contribuindo

Contribuições são bem-vindas! Se você encontrar erros ou tiver sugestões:

1. Abra uma [Issue](https://github.com/seu-usuario/introducao-ordenacoes/issues)
2. Faça um Fork do repositório
3. Crie uma branch para sua feature (`git checkout -b minha-feature`)
4. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
5. Push para a branch (`git push origin minha-feature`)
6. Abra um Pull Request

## 📄 Licença

Este material está licenciado sob [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

**Você pode:**
- ✅ Compartilhar — copiar e redistribuir o material
- ✅ Adaptar — remixar, transformar e criar a partir do material

**Desde que:**
- 📝 Dê o crédito apropriado ao autor original
- 🔗 Indique se mudanças foram feitas

## 🌟 Citação

Se você usar este material, por favor cite:

```
Higuchi, P. (2025). Introdução às Ordenações: Simplificando Dados Complexos 
de Vegetação. Universidade do Estado de Santa Catarina. 
Disponível em: https://github.com/higuchip/introducao-ordenacoes
```

## 📞 Contato

Dúvidas ou sugestões? Entre em contato:
- 📧 Email: higuchip@gmail.com

---

**⭐ Se este material foi útil, considere dar uma estrela no repositório!**

*Última atualização: Novembro 2025*
