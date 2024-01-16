# 01 - Introdução a MLOps

>  Not all debt is bad, but all debt needs to be serviced.

Não é novidade que produtos potencializados com aplicação de machine learning ou de inteligência artificial são cada vez mais comuns, a comunidade em torno desses temas se expande rapidamente e vemos isso claramente através da velocidade em que temas complexos como por exemplo, no momento que este livro esta sendo escrito, arquiteturas de transformers com suas redes de encoders e decoders são aplicadas nos mais simples gadgets e utensílios do dia-a-dia. Embora ter sua airfryer utilizando AI pareça ser algo corriqueiro (e talvez, inútil?), é resultado de um movimento que vem recebendo tanta força quanto o de ML & AI em si, o de produtizar modelos de aprendizado de máquina.

Em uma lente mais técnica, e talvez mais útil para humanidade, pesquisas de alto nível em aprendizado de máquina existem bem antes desses termos se popularizarem, biólogos analisam bases de dados complexas a fim de encontrar padrões protéicos podendo predizer estruturas de proteínas e aminoácidos para desenvolvimento de medicamentos, físicos simulam a interação entre materiais em várias escalas, da atômica a macroscópia realizando analises experimentais que levariam alguns anos se feitas de maneira manual, entre outros. Como grande parte do uso inicial das tecnologias de aprendizado de maquina partiram de pesquisas acadêmicas (ou bélicas), por natureza tanto o perfil do profissional que aplicava tais técnicas quanto a necessidade do trabalho não exigia a tão famigerada visão de produto onde, leia-se, necessidade de encapsular as coisas e transformar em algo utilizável na ponta final, de maneira organizavel, reprodutível e aplicável.

Com o passar dos anos, as necessidades de consumo e produção de aprendizado de máquina se descolaram, e as conhecidas dívidas técnicas (technical debts) se mostraram especialmente presentes em aplicações de aprendizado de máquina e inteligência artificial onde, por incrivel que pareça, descobrimos que não era tão fácil levar jupyters notebooks repletos de códigos quase ilegíveis, sem uma ordem lógica e claramente não otimizados para um ambiente produtivo - muito menos instalar os mesmos na sua máquina de lavar potencializada com AI.

Em 2015, o famoso paper (https://proceedings.neurips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf?ref=hackernoon.com)[Hidden Technical Debt in Machine Learning Systems] dá o grande ponta pé inicial na ideia de que, produzir aplicações de aprendizado de máquina exige uma visão técnica e ,até então negligenciada, que aparece mais facilmente no design completo de sistemas que utilizam aprendizado de máquina (e não de estudos isolados) trazendo visões mais tradicionais de engenharia de software para o campo majoritariamente acadêmico ou de pesquisa.

> Desenvolver sistemas de aprendizado de máquina é relativamente barato e rápido mas mantê-los ao longo do tempo é caro e complexo

# Código, Dados e Modelos
