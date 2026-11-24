# 🥗 NutriVida — Calculadora de IMC e Alimentação Equilibrada

O **NutriVida** é uma aplicação web desenvolvida para calcular o Índice de Massa Corporal (IMC) em adultos, sincronizar o resultado com a tabela oficial da OMS e sugerir cardápios saudáveis e práticos. O projeto foi desenhado com uma abordagem respeitosa, moderna e inclusiva, voltada para pessoas comuns que buscam qualidade de vida utilizando comida de verdade e ingredientes do cotidiano (como arroz, feijão, ovos, carnes magras e vegetais da estação).

Este repositório foi construído para atender integralmente a todos os critérios da **Atividade 01 — Aula 07**.

---

## 📋 Requisitos da Atividade 01 Atendidos

1. **Estrutura com CSS Externo:**
   - Separação completa entre a marcação HTML (`index.html`) e o arquivo de estilos (`style.css`).
   - Vínculo realizado através da tag `<link rel="stylesheet" href="style.css">` no elemento `<head>`.

2. **Box Model em 20 Elementos:**
   - Mapeamento explícito de 20 elementos utilizando classes de `.el-01-...` até `.el-20-...`.
   - Cada um dos 20 elementos possui todas as propriedades de Box Model definidas explicitamente no CSS:
     - **Content** (`width` e/ou `height`)
     - **Padding** (`padding`)
     - **Border** (`border`)
     - **Margin** (`margin`)

3. **Flexbox e Responsividade:**
   - Aplicação de mais de 20 propriedades/regras de Flexbox (`display: flex`, `flex-direction`, `justify-content`, `align-items`, `flex-wrap`, `gap`, `flex`, etc.).
   - Design totalmente responsivo que se adapta perfeitamente a telas de celulares, tablets e desktops.

---

## 🚀 Funcionalidades da Aplicação

- **Cálculo Prático e Instrução Clara:** Interface com orientação para separação decimal por ponto (ex: `72.5` kg e `1.70` m), tratando automaticamente digitações com vírgula.
- **Sincronização em Tempo Real com a OMS:** Destaque automático da faixa de classificação correspondente na tabela oficial (de Abaixo do Peso até Obesidade Grau III).
- **Orientação Clínica sobre Bioimpedância:** Nota explicativa destacando que o IMC é uma ferramenta de *triagem rápida*, enquanto a *bioimpedância* é o método recomendado para mensurar gordura, massa muscular e hidratação.
- **Estimativa Calórica Diária:** Cálculo da meta calórica ajustada ao nível de atividade física e objetivo nutricional.
- **Sugestões de Cardápio Equilibrado:** Opções de refeições completas (Café da manhã, Almoço, Lanche e Jantar) utilizando ingredientes acessíveis do dia a dia.
- **Guia Alimentar do Cotidiano:** Categorização prática de proteínas, carboidratos e vegetais frescos.

---

## 📁 Estrutura de Arquivos

```
atividade-01-imc/
├── index.html   # Estrutura HTML da aplicação com script de cálculo e sincronização
├── style.css    # Folha de estilo externa (Box Model + Flexbox)
└── README.md    # Documentação do projeto
```

---

## 🛠️ Como Executar

1. Baixe os arquivos do projeto e salve-os na mesma pasta.
2. Abra o arquivo `index.html` em qualquer navegador web atualizado (Chrome, Edge, Firefox, Safari).
3. Para testar a responsividade, utilize o atalho `F12` no navegador e ative a visualização de dispositivos móveis.

---

## 🎨 Conceito Visual e Linguagem

- **Linguagem Inclusiva e Respeitosa:** Eliminação de termos pejorativos, promovendo a alimentação saudável através da "comida de verdade".
- **Identidade Visual:** Tons verdes e alaranjados que transmitem saúde, bem-estar e acessibilidade com um visual moderno e acolhedor.