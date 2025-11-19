# Comparação Empírica entre Mecanismos Centralizados e Descentralizados de Autenticação

**Autor:** Douglas Viana Fernandes  
**Instituição:** Pontifícia Universidade Católica de Minas Gerais – PUCMG  
**Curso:** Engenharia de Software  
**Disciplina:** Trabalho de Conclusão de Curso I  
**Professores:** Cleiton Silva, Leonardo Cardoso, Danilo e Raphael  

---

## 📌 Descrição do Projeto

Este projeto investiga, de maneira **empírica e comparativa**, dois paradigmas amplamente utilizados para autenticação digital:

- mecanismos **centralizados** (OAuth 2.0, OpenID Connect, TOTP, senhas tradicionais)  
- mecanismos **descentralizados** baseados em **blockchain**, contratos inteligentes e provas criptográficas.

A motivação surge do fato de que modelos centralizados dependem de provedores confiáveis e criam riscos estruturais como **ponto único de falha**, baixa auditabilidade e reduzida autonomia do usuário. Por outro lado, abordagens descentralizadas prometem maior **transparência, imutabilidade e soberania**, mas carregam desafios como custo operacional e complexidade de adoção.

Este trabalho compara esses dois modelos com base em **métricas empíricas reportadas na literatura**, oferecendo uma visão clara dos **benefícios, limitações e trade-offs** envolvidos.

---

## 📌 Contextualização

Com a crescente dependência de sistemas online, os mecanismos de autenticação tornaram-se críticos para segurança, privacidade e integridade de dados. Protocolos amplamente adotados, como *OAuth 2.0* e *OpenID Connect*, funcionam bem na prática, mas dependem da integridade de servidores centrais — que podem ser atacados, comprometidos ou mal configurados.

A literatura recente propõe alternativas baseadas em **blockchain**, explorando:

- contratos inteligentes,
- modelos de verificação distribuída,
- ausência de autoridade central,
- maior auditabilidade de operações.

Entretanto, ainda **não existe uma comparação sistemática**, baseada em evidências concretas, entre esses dois modelos de autenticação. A maioria dos estudos analisa soluções isoladas.

Este trabalho aborda exatamente essa lacuna.

---

## 🎯 Objetivo Geral

**Comparar, com base em evidências empíricas publicadas, mecanismos de autenticação tradicionais e modelos descentralizados baseados em blockchain, identificando benefícios, limitações e condições práticas de adoção.**

---

## 🎯 Objetivos Específicos

- Identificar e organizar métricas empíricas disponíveis na literatura sobre mecanismos centralizados e descentralizados.  
- Construir uma matriz comparativa envolvendo segurança, desempenho e auditabilidade.  
- Analisar criticamente os *trade-offs* entre os modelos, destacando vantagens e limitações reais.  
- Sintetizar diretrizes de Engenharia de Software que auxiliem na adoção responsável de abordagens descentralizadas.

---

## 📌 Problema de Pesquisa

A literatura carece de estudos comparativos robustos sobre autenticação. A maioria dos trabalhos aborda soluções isoladas, o que impede compreender:

- em quais cenários a descentralização realmente traz benefícios;
- quais riscos continuam existindo;
- quais custos e barreiras dificultam a adoção prática.

Sem essa comparação, engenheiros e instituições não têm clareza para tomar decisões técnicas fundamentadas.

---

## ❓ Questão de Pesquisa

**Em que medida mecanismos de autenticação baseados em blockchain superam ou complementam modelos centralizados quanto à segurança, ao desempenho e à auditabilidade/operacionalidade?**

---

## 🧪 Metodologia

O estudo segue uma abordagem **empírica e documental**, fundamentada na Engenharia de Software Experimental:

1. **Seleção de artigos primários** sobre autenticação centralizada e descentralizada (2018–2025).  
2. **Extração de métricas empíricas** reportadas nos estudos (latência, uso de CPU, vulnerabilidades, custos de verificação, etc.).  
3. **Construção de matrizes comparativas** envolvendo três dimensões principais:
   - Segurança  
   - Desempenho  
   - Auditabilidade / Operacionalidade  
4. **Análise crítica** dos resultados encontrados.  
5. **Síntese de diretrizes de Engenharia de Software** para adoção de tecnologias descentralizadas.

---

## 📌 Resultados Esperados

- Um panorama comparativo estruturado sobre autenticação centralizada vs. descentralizada.  
- Identificação de vantagens reais da descentralização — e também de suas limitações práticas.  
- Uma matriz que facilite decisões de adoção tecnológica em instituições públicas e privadas.  
- Diretrizes aplicáveis para arquitetos e engenheiros de software.  
- Base metodológica para continuação no **TCC II**, incluindo possibilidade de implementação ou simulação.

---

## 📚 Escopo do Estudo

O trabalho **não envolve implementação**, prototipação ou testes próprios.  
Toda análise é realizada **a partir de dados empíricos já publicados**.

As dimensões comparadas incluem:

- segurança criptográfica  
- vulnerabilidades conhecidas  
- desempenho (latência, processamento, throughput)  
- auditabilidade  
- dependência de terceiros  
- custos operacionais  
- maturidade e viabilidade técnica  

---

## 📁 Organização do Repositório

