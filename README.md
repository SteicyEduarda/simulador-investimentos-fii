# 📊 Simulador de Investimentos em Fundos Imobiliários

## 📋 Resumo Executivo

Ferramenta educacional em **Excel** para simular e analisar investimentos em **Fundos Imobiliários (FIIs)**, permitindo visualizar cenários de rentabilidade e acumulação de patrimônio.

**Status:** ✅ Completo | **Nível:** Iniciante | **Tecnologia:** Microsoft Excel

---

## 🎯 Objetivo

Ajudar **investidores iniciantes** a:
- 💰 Compreender dinâmica de investimentos em FIIs
- 📊 Simular diferentes cenários de aplicação
- 💵 Visualizar projeções de dividendos
- 📈 Analisar impacto do reinvestimento

---

## 💡 Por que Fundos Imobiliários?

**FIIs** são investimentos que:
- Distribuem dividendos mensais (100% do lucro)
- Têm menor volatilidade que ações
- Permitem acesso ao mercado imobiliário
- São acessíveis para pequenos investidores

> ⚠️ **Aviso Legal:** Este simulador é apenas educacional. Não representa recomendação de investimento ou garantia de rentabilidade.

---

## 📁 Estrutura do Projeto

```
simulador-investimentos-fii/
├── README.md                          ← Você está aqui
├── .gitignore
│
├── planilhas/
│   ├── Simulador_FII_v1.xlsx          ← Arquivo principal (Excel)
│   └── Simulador_FII_template.xlsx    ← Template para copiar
│
├── docs/
│   ├── guia-uso.pdf                   ← Manual de instrução
│   ├── glossario-fii.md               ← Termos explicados
│   └── cenarios-exemplo.md            ← Exemplos práticos
│
└── README.md
```

---

## 📈 Funcionalidades da Planilha

### 1️⃣ Simulação Básica
- Entrada de valor de investimento inicial
- Aporte mensal configurável
- Taxa de rendimento anual
- Período de simulação (meses)

### 2️⃣ Cálculos Automáticos
```excel
Patrimônio Acumulado = (Investimento + Aportes) + Dividendos
Dividendos Mensais = Patrimônio × (Taxa Anual / 12)
Rentabilidade Total = (Valor Final - Investimento Total) / Investimento Total
```

### 3️⃣ Cenários de Análise
- Comparação de diferentes taxas de rendimento
- Impacto de aportes regulares
- Análise de reinvestimento de dividendos
- Projeção de 5, 10, 20 anos

### 4️⃣ Visualizações
- 📊 Gráfico de evolução do patrimônio
- 💵 Gráfico de dividendos mensais
- 📈 Tabela comparativa de cenários
- 🎯 Meta de patrimônio (opcional)

---

## ▶️ Como Usar

### Passo 1: Baixe a Planilha
1. Acesse o repositório
2. Baixe `Simulador_FII_v1.xlsx`
3. Abra com Microsoft Excel ou Google Sheets

### Passo 2: Configure os Parâmetros

Na aba **"SIMULADOR"**, preencha:

| Campo | Exemplo | Descrição |
|-------|---------|----------|
| **Investimento Inicial** | R$ 5.000 | Valor que você vai aplicar agora |
| **Aporte Mensal** | R$ 500 | Quanto adiciona todo mês |
| **Rendimento Anual (%)** | 10% | Taxa esperada de retorno ao ano |
| **Período (meses)** | 60 | Quanto tempo de simulação |
| **Reinvestir Dividendos?** | SIM/NÃO | Aplicar dividendos novamente |

### Passo 3: Analise os Resultados

A planilha calcula automaticamente:
- ✅ Patrimônio mês a mês
- ✅ Total de dividendos acumulados
- ✅ Rentabilidade percentual
- ✅ Gráficos visuais

### Passo 4: Teste Cenários

Mude os parâmetros e veja como mudam os resultados!

**Exemplo de Cenários:**
```
Cenário Conservador: 5% a.a., R$ 300/mês
Cenário Moderado:    10% a.a., R$ 500/mês  
Cenário Agressivo:   12% a.a., R$ 1.000/mês
```

---

## 📊 Exemplo Prático

### Simulação: R$ 10.000 iniciais + R$ 500/mês, 10% a.a., 10 anos

```
Mês 1:   Patrimônio: R$ 10.500 | Dividendos: R$ 83
Mês 6:   Patrimônio: R$ 13.000 | Dividendos: R$ 108
Mês 12:  Patrimônio: R$ 16.500 | Dividendos: R$ 137
Mês 24:  Patrimônio: R$ 24.500 | Dividendos: R$ 204
Mês 60:  Patrimônio: R$ 45.000 | Dividendos: R$ 375
Mês 120: Patrimônio: R$ 92.000 | Dividendos: R$ 767

Rentabilidade Total: 420% em 10 anos
```

---

## 🛠️ Ferramentas Utilizadas

- **Microsoft Excel** 2019 ou superior
- **Google Sheets** (compatível)
- Funções: `SUM`, `PMT`, `RATE`, `FV`
- Gráficos XY/Dispersão

---

## 💡 Possíveis Melhorias

- [ ] Adicionar comparação com outros investimentos (CDB, Tesouro)
- [ ] Dashboard interativo com Power BI
- [ ] Simulação de reinvestimento automático
- [ ] Comparação entre FIIs específicos
- [ ] Análise de tributação (IR)
- [ ] API para preços reais de FIIs
- [ ] Versão em Google Sheets compartilhável
- [ ] Exportação de relatórios em PDF

---

## 📚 Aprendizados

Durante o desenvolvimento, foram praticados:

✅ **Excel Avançado:** Fórmulas complexas, validações, proteção de células  
✅ **Finanças:** Cálculo de juros compostos, VPL, TIR  
✅ **Dados:** Organização de informações, lógica de simulação  
✅ **Visualização:** Gráficos informativos e intuitivos  
✅ **Git & GitHub:** Controle de versão de arquivos  
✅ **Documentação:** Comunicação clara de funcionalidades  

---

## 📖 Termos Importantes

### Fundos Imobiliários (FIIs)
Fundos que investem em imóveis e distribuem 100% do lucro aos investidores mensalmente.

### Dividendos
Parte do lucro distribuída periodicamente aos investidores.

### Patrimônio Acumulado
Valor total investido + lucros obtidos.

### Rendimento Anual
Taxa de retorno esperada em um ano (em %).

### Aporte
Novo investimento realizado periodicamente.

---

## ⚠️ Avisos Importantes

1. **Educacional:** Este simulador é para fins didáticos
2. **Não é recomendação:** Não recomenda investimento específico
3. **Taxas simplificadas:** Não inclui impostos, taxas de corretagem
4. **Histórico ≠ Futuro:** Rentabilidade passada não garante resultados
5. **Risco:** Todo investimento tem risco, incluindo perda de capital

---

## 🔗 Recursos Externos

- [B3 — Informações sobre FIIs](https://www.b3.com.br/pt_br/produtos-e-servicos/negociacao/renda-variavel/fundo-de-investimento-imobiliario.htm)
- [Central do Investidor — CVM](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/auditorias)
- [Guia de FIIs — XP Investimentos](https://www.xp.com.br/)

---

## 📞 Contato & Dúvidas

Tem dúvidas sobre como usar o simulador?

- 💬 Abra uma [issue](https://github.com/SteicyEduarda/simulador-investimentos-fii/issues)
- 🔗 [LinkedIn](https://www.linkedin.com/in/steicyeduarda)
- 📧 Envie uma mensagem via GitHub

---

## 👩‍💻 Autora

**Steicy Eduarda**

- Formação: Analista de Dados Jr.
- Interesse: Análise de Dados e Finanças
- Projeto: Desafio prático da [DIO](https://www.dio.me/)

---

**Última atualização:** Agosto 2026  
**Status:** ✅ Projeto Completo