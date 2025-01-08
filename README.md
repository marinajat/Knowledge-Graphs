# Knowledge Graphs: Representação e Manipulação de Grafos de Conhecimento

## 📚 Descrição do Projeto
Este projeto foi desenvolvido com o objetivo de explorar os conceitos de grafos através da construção e manipulação de Knowledge Graphs.  
Knowledge Graphs são estruturas de dados que representam conhecimento de forma semântica, conectando entidades e conceitos por meio de relacionamentos.

Durante o projeto, foram aplicados conhecimentos de **Processamento de Linguagem Natural (PLN)** e manipulação de grafos para:  
- Criar uma **base de conhecimento** em forma de grafo, incluindo entidades, relacionamentos e propriedades relevantes.  
- Implementar funcionalidades de manipulação do grafo, como **adicionar, remover e consultar nós e arestas**.  
- Analisar as potenciais **aplicações e limitações** do uso de grafos de conhecimento no mundo real.  

---

## 🛠️ Tecnologias Utilizadas
- **Linguagem de Programação**: Python 
- **Bibliotecas e Frameworks**: NetworkX, Matplotlib, Spacy  
- **Processamento de Linguagem Natural (PLN)**: Técnicas e ferramentas aplicadas na criação da base de conhecimento.  
- **Representação de Grafos**: Conceitos e práticas para construção e manipulação de Knowledge Graphs.  

---

## 📂 Base de Dados
A base de dados utilizada neste projeto foi construída a partir de descrições textuais das relações entre os personagens da série **Dark**, da Netflix.  

O texto contém informações sobre os personagens, suas conexões familiares, relações amorosas, eventos principais e outros vínculos narrativos relevantes. Essas informações foram processadas utilizando técnicas de Processamento de Linguagem Natural (PLN) para identificar:  
- **Entidades**: Os personagens da série (e.g., Jonas, Martha, Claudia, etc.).  
- **Relações**: As conexões entre os personagens (e.g., "casou com", "gerou", "viajou no tempo", etc.).  

Com base nisso, foi criado um **grafo de conhecimento** que representa visualmente a complexa teia de interações da história de **Dark**.  

### Exemplos de Dados
- **Entidades**: Jonas, Martha, Claudia, Ulrich, Mikkel, entre outros.  
- **Relações**:  
  - Jonas viajou no tempo.  
  - Martha estuda na escola.  
  - Claudia gerou Regina.  
  - Peter casou com Charlotte.  

### Aplicação no Projeto
O texto é processado pelo modelo de linguagem do SpaCy para identificar as entidades e relações, que são então estruturadas no formato de grafo utilizando a biblioteca NetworkX. Isso permite:  
- Visualizar as conexões complexas entre os personagens e eventos.  
- Analisar as dinâmicas e interações semânticas da narrativa.  

O grafo resultante oferece uma representação clara das interações, servindo como exemplo prático da aplicação de **Knowledge Graphs** para modelar dados ricos e interconectados.  

### Visualização
O grafo gerado pode ser visualizado com diferentes layouts (e.g., Kamada-Kawai), destacando as relações entre os personagens e permitindo uma análise mais intuitiva da trama.  

---

## 🎯 Objetivos e Resultados
Este projeto foi desenvolvido com foco em consolidar conceitos teóricos e práticos relacionados a **Knowledge Graphs**, promovendo:  
1. **Compreensão de estruturas semânticas de conhecimento**.  
2. **Desenvolvimento de habilidades práticas em manipulação de grafos**.  
3. **Aplicação de técnicas de PLN** no contexto de grafos de conhecimento.  
4. **Reflexão sobre o potencial e as limitações** dessa abordagem para problemas do mundo real.  

---

## 🚀 Execução do Projeto
O projeto pode ser executado diretamente no Google Colab, garantindo um ambiente configurado para rodar o código sem necessidade de instalações adicionais.  
Acesse o notebook por meio do link abaixo:  
[Executar no Colab](https://colab.research.google.com/drive/1RXWTVeuBb0agAC_q9otAT0o9sudAXQNI)  

