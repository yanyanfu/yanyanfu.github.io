---
---
---
collection: publications
permalink: /publications/1-scam23-acerA

title: "ACER: An AST-based Call Graph Generator Framework"
authors: "Andrew Chen, **Yanfu Yan**, and Denys Poshyvanyk"
venue_key: "scam23"
track: 
date: 2024-10-2
doiurl: 2308.15669

paperurl: /files/1-scam23-acer.pdf
package: https://github.com/WM-SEMERU/ACER
notes: 
distinction: 
---

**Abstract:** We introduce ACER, an AST-based call graph generator framework. ACER leverages tree-sitter to interface with any language. We opted to focus on generators that operate on abstract syntax trees (ASTs) due to their speed and simplicitly in certain scenarios; however, a fully quantified intermediate representation usually provides far better information at the cost of requiring compilation. To evaluate our framework, we created two context-insensitive Java generators and compared them to existing open-source Java generators.
