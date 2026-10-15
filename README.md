# 📊 Monitoramento de Jornadas de Trabalho

Sistema web para calcular e analisar indicadores de ocorrências de jornadas de trabalho, desenvolvido para facilitar o acompanhamento de equipes e a apresentação de resultados em reuniões.

## 🎯 Objetivo

Simplificar o cálculo de indicadores de jornadas, permitindo informar a quantidade de colaboradores e os eventos registrados em cada equipe, com apresentação automática dos resultados.

## ✨ Funcionalidades

- Cadastro temporário do nome da equipe.
- Entrada da quantidade de colaboradores.
- Entrada da quantidade de eventos de jornada.
- Cálculo automático do indicador.
- Exibição do resultado em formato positivo.
- Formatação numérica brasileira.
- Cópia do resultado para a área de transferência.
- Opções para realizar um novo cálculo ou finalizar a sessão.
- Interface responsiva para computadores e dispositivos móveis.

## 🧮 Lógica de cálculo

O sistema utiliza a seguinte fórmula:

1. Fator proporcional = quantidade de colaboradores ÷ 100.
2. Resultado = quantidade de eventos × fator proporcional − 100.
3. Valor apresentado = valor absoluto do resultado.

**Exemplo:**

- Colaboradores: 19
- Eventos de jornada: 3
- Fator proporcional: 19 ÷ 100 = 0,19
- Resultado: (3 × 0,19) − 100 = −99,43
- Valor apresentado: 99,43

> Observação: a fórmula acima reproduz a regra definida para o projeto. O resultado é um indicador calculado conforme essa regra, não necessariamente a porcentagem estatística de ocorrências sobre o total de colaboradores.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## 🚀 Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Informe os dados da equipe.
4. Clique em **Calcular resultado**.

Não é necessário instalar dependências para executar a versão atual.

## 🌐 Publicação

O projeto pode ser publicado gratuitamente com o GitHub Pages.

Após ativar a hospedagem, o endereço estará disponível no formato:

`https://SEU-USUARIO.github.io/monitoramento-jornadas/`

Substitua `SEU-USUARIO` pelo nome de usuário da sua conta GitHub.

## 🔒 Limitações atuais

Esta versão funciona no navegador e não utiliza banco de dados. Os resultados não são armazenados permanentemente e devem ser tratados como dados temporários.

Não utilize informações pessoais ou dados internos confidenciais de colaboradores nesta demonstração pública.

## 👨‍💻 Autor

Projeto desenvolvido como iniciativa de aprendizado em desenvolvimento web, automação de cálculos e análise de indicadores de jornadas de trabalho.

**Tecnologias:** HTML, CSS e JavaScript.

---

Athos Reis | Desenvolvedor de Business Intelligence

---
