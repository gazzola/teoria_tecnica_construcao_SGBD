# Teoria e Técnica de Construção de Sistemas de Gerenciamento de Bases de Dados Relacionais

Objetivos:

Apresentação aprofundada dos principais conceitos, estruturas e técnicas empregadas pelos Sistemas de Gerenciamento de Bases de Dados Relacionais – SGBDR, bem como análise de como essas técnicas são empregadas no desenvolvimento de outros paradigmas de sistemas gerenciadores de bases dados, tal como os Sistemas Orientados a Objetos e mais recentemente os sistemas voltados às ferramentas Not-Only SQL (No-SQL). São estudados os algoritmos internos usados para a interpretação de consultas em SQL e sua otimização, bem como a implementação dos métodos básicos de acesso aos dados em espaços escalares, multidimensionais e métricos. Com isso pretende-se que o aluno possa fazer uma análise crítica das técnicas de construção de aplicativos centrados em SGBD tanto Relacionais como Orientados a Objetos e NoSQL, avaliando e comparando as melhores alternativas de implementação em situações reais, de maneira a obter do sistema resultante seu melhor desempenho.

Justificativa:

Com a disponibilidade sempre crescente de novas formas de coleta de dados e de informações (tanto com variados sensores como gerados pelos usuários em redes sociais e outros mecanismos de interação), o armazenamento de grandes volumes de dados tem crescido exponencialmente em importância. No entanto, não apenas o volume, mas também as formas de aceso, manipulação e análise têm se tornado cada vez mais heterogêneas, imponto a necessidade de novas funcionalidades aos SGBD. Assim, seu uso eficiente se torna cada vez mais dependente de um planejamento bem fundamentado na compreensão de suas funcionalidades, recursos e conceitos de desenvolvimento, que requerem que as características dos sistemas usados sejam levadas em conta. Embora a correta utilização dos SGBDs em situações que envolvem pequeno volume de dados não seja crítica, quando esse volume aumenta, quando o tempo de resposta se torna crítico, e quando a variedade dos dados aumenta, então questões de desempenho se tornam primordiais. Nessas situações, o conhecimento das tecnologias empregadas na construção dos sistemas se torna importante para obter um desempenho adequado. Além disso, do ponto de vista do desenvolvimento de pesquisas na área de bases de dados, um conhecimento sólido das técnicas de construção de Sistemas relacionais, orientado a objetos e NoSQLé fundamental, pois as possíveis contribuições de cada tecnologia podem ser conseguidas apenas quando corretamente contextualizadas no funcionamento desses sistemas.

Conteúdo:

- Caracterização SGBDR, SGBDOR e ferramentas No-SQL. Diferenciação de conceitos em cada sistema. - Características distintivas dos SGBDR e SGBDOR. Classes de ferramentas de armazenagem de dados. - Paradigmas de representação de dados: relacional, tabular, documentos, grafos, dicionários. - Técnicas de compilação de consulta, otimização de consultas, geração de planos de acesso. - Indexação de dados. Árvores e hashing, controle de concorrência. - Previsão de seletividade, previsão de custo de acesso. Organização de memória. Paralelismo. - Acesso a dados em domínios escalares, ordenáveis, multidimensionais e métricos.

Forma de Avaliação:

São atribuídas notas aos trabalhos práticos e às provas realizadas em sala de aula. A nota final é calculada pela média ponderada dessas notas segundo a fórmula

Observação:

Bibliografia:

Fundamentais: 
Garcia-Molina, H., Ullman, J. D., Widow, J. D. - Database Systems: The Complete Book, Pearson Education, ISBN: 0130319953. 1152pp, October 2001. 
O'Neil, P., O'Neil, E. - Database: Principles, Programming, and Performance, Second Edition, Elsevier Science & Technology, ISBN: 1558604383, 870pp., April 2000. 
N. Bruno, Automated Physical Databases Design and tuning. Boca Raton, FL: CRC Press, 2011. 
Christopher J. Date, SQL and Relational Theory - How to Write Accurate SQL Code, O'Reilly Media, 2009. 

Complementares: 
MELTON, J., SIMON, A. - "SQL:1999 - Understanding Relational Language Components, Elsevier Science & Technology Books, ISBN: 1558604561, 752pp., May 2001. 
G. Graefe, "Query Evaluation Techniques for Large Databases," ACM Computing Surveys, Vol. 25, No. 2, June 1993, pp. 98-182. 
G. Graefe, "Modern B-Tree Techniques," Foundations and Trends in Databases, 2011, Vol. 3, No. 4, pp. 203-402. 
Goetz Graefe, Haris Volos, Hideaki Kimura, Harumi A. Kuno, Joseph Tucek, Mark Lillibridge, Alistair C. Veitch: In-Memory Performance for Big Data PVLDB 8(1): 37-48 (2014) 
ask others 
Daniel J. Abadi, et alli: The Beckman Report on Database Research. SIGMOD Record 43(3): 61-70 (2014) 
Daniel Abadi, Michael J. Carey, Surajit Chaudhuri, Hector Garcia-Molina, Jignesh M. Patel, Raghu Ramakrishnan: Cloud Databases: What's New? PVLDB 3(2): 1657 (2010)
