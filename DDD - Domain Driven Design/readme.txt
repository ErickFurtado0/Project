DDD - Domain Driven Desing

Definição
O Domain Driven Desing é um metódo/prática aonde combina práticas de design e desenvolvimento no intuito de fazer a modelagem estratégica e tática com alta qualidade na entrega do software. Seu principal objetivo é acelerar o desenvolvimento de software que lidam com complexos processos de negócio.

Regras
Ubiquitous Language - 4 Principais Práticas									                        Ubiquitous Language - Motivações 					            Ubiquitous Language - Problemas
1. Prática de construir uma comum e rigorosa linguagem entre desenvolvedores e usuários.			Seguir a prática desde do básico do projeto até a parte			Não ter acesso ao Domain Expert
2. Linguagem que é compartilhada por todos os envolvidos no projeto.						        mais complexa do código							                Não falar a mesma lingua do Domain Expert
3. Vocabulário do domínio.																				                                                            Falsos Domain Experts (CUIDADO!!!)
4. Usado em todas as formas de falar e escrever.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Bounded Context - Principais Práticas										                                    Bounded Context - Benefícios
1. Tudo dentro de um único contexto mas separado por espaço delimitado aonde eles tem sua própia regra.		    ° Manutenção.
2. Possui sua própria Ubiquitous Language por domínio.								                            ° Entidades passam a ter significados e responsabilidades diferentes dependendo do contexto.
3. Arquitetura Independente aonde cada um mantém o seu funcionamento a parte, sem invadir o espaço do outro.	° Fácil para modelar e compreender.
														                                                        ° Alteração em um domínio não afeta outro, pois existe um limite, uma fronteira, uma delimitação entre os domínios.
														                                                        ° Simplifica o design dos módulos dos softwares.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Arquitetura
Forma de organização melhor do projeto incluindo o DDD.

