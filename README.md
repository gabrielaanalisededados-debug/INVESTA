# INVESTA — Simulador de Fundos Imobiliários

**Planeje seus aportes. Projete seu patrimônio.**

A INVESTA é uma ferramenta de simulação financeira desenvolvida no Microsoft Excel, com o objetivo de auxiliar na visualização do crescimento patrimonial por meio de aportes mensais e na distribuição de investimentos entre diferentes categorias de Fundos de Investimento Imobiliário (FIIs).

O projeto apresenta uma interface intuitiva, cálculos automatizados, cenários de longo prazo e gráficos dinâmicos.

## Objetivo do projeto

Desenvolver uma ferramenta interativa que permita ao usuário simular estratégias de investimento, visualizar projeções patrimoniais e compreender como diferentes distribuições de aportes podem influenciar a composição de uma carteira.

## Funcionalidades

- **Simulação de investimentos:** cálculo do patrimônio acumulado com base no aporte mensal, prazo e taxa de rendimento.
- **Projeções financeiras:** visualização de cenários de 2, 5, 10, 20 e 30 anos.
- **Perfis de investidor:** três modelos de distribuição — Conservador, Moderado e Agressivo.
- **Distribuição de FIIs:** divisão dos aportes entre seis categorias de fundos.
- **Composição patrimonial:** separação entre valores aportados e rendimentos projetados.
- **Gráficos dinâmicos:** representação visual da composição do patrimônio e da distribuição dos investimentos.
- **Cálculo de dividendos:** estimativa de rendimentos mensais com base na taxa configurada.
- **Proteção de células:** preservação das fórmulas e liberação dos campos destinados à edição pelo usuário.

## Perfis de investimento

A ferramenta apresenta três modelos de distribuição:

| Categoria | Conservador | Moderado | Agressivo |
|---|---:|---:|---:|
| Papel | 30% | 32% | 50% |
| Tijolo | 50% | 35% | 10% |
| Híbridos | 10% | 8% | 5% |
| FOFs | 10% | 5% | 5% |
| Desenvolvimento | 0% | 10% | 20% |
| Hotelarias | 0% | 10% | 10% |
| **Total** | **100%** | **100%** | **100%** |

Os percentuais são parâmetros ilustrativos utilizados na simulação, não recomendações de investimento.

## Tecnologias e recursos utilizados

- Microsoft Excel
- Fórmulas financeiras, incluindo VF
- PROCV
- Intervalos nomeados
- Validação de dados
- Formatação condicional e formatação personalizada
- Gráficos dinâmicos
- Proteção de células e planilhas

## Estrutura do projeto

- `INVESTAOFICIAL.xlsx` — arquivo principal do simulador.
- `README.md` — documentação do projeto.
- `screenshots/` — capturas de tela demonstrativas.

## Premissas da simulação

A ferramenta utiliza parâmetros configuráveis para realizar as projeções, incluindo:

- Taxa mensal de acumulação configurada em 1,079% na demonstração.
- Taxa de rendimento da carteira configurada em 0,60%.
- Aportes mensais definidos pelo usuário.
- Horizontes de investimento de 2 a 30 anos.

Os resultados são projeções matemáticas baseadas nas premissas informadas. Não representam rentabilidade garantida nem previsão de desempenho futuro dos FIIs. As taxas constantes simplificam o comportamento real do mercado.

## Aprendizados e desenvolvimento

O desenvolvimento da INVESTA envolveu a aplicação prática de conhecimentos em Excel, organização de bases de dados, criação de fórmulas financeiras, automação de cálculos, construção de gráficos e estruturação de uma interface voltada à experiência do usuário.

O projeto também permitiu trabalhar com identificação e correção de referências, intervalos nomeados, testes de funcionamento e proteção de fórmulas.

## Sobre o projeto

Projeto desenvolvido como parte da jornada de aprendizado em análise de dados, com aprimoramentos de estrutura, identidade visual e funcionalidades.

**Desenvolvido por:** Gabriela

---

*INVESTA — Planeje seus aportes. Projete seu patrimônio.*
