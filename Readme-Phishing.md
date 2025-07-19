# Demonstração de Ataque de Falsificação de Website com SEToolkit

Este arquivo documenta a execução de um **exemplo educacional** de ataque de engenharia social usando o **Social-Engineer Toolkit (SEToolkit)** para **clonar um website legítimo e capturar credenciais inseridas pela vítima**.

> ⚠️ **Aviso Legal:** Este experimento foi conduzido exclusivamente em ambiente de laboratório para fins educativos e de conscientização sobre segurança da informação. Não é permitido realizar esse tipo de teste sem autorização expressa e legal.

---

## 🔧 Ferramentas Utilizadas

- **Kali Linux**
- **SEToolkit (Social-Engineer Toolkit)**
- **Apache2 (servidor web local)**
- Navegador (usado como simulação da vítima)

---

## 🎯 Objetivo

Simular um ataque de **phishing** através da **falsificação do site oficial do Java**, com captura de informações inseridas em um formulário falso, utilizando o módulo **Credential Harvester** do SEToolkit.

---

## ⚙️ Etapas Realizadas

- Acesso root: sudo su
- Iniciando o setoolkit: setoolkit
- Tipo de ataque: Social-Engineering Attacks
- Vetor de ataque: Web Site Attack Vectors
- Método de ataque: Credential Harvester Attack Method > 1) Website Templates > Java

## Resultados

- Foi gerado uma página pelo servidor web simulando uma página do Java.
- Através da página gerada foi possível obter todas as pequisas que o usuário estava realizando na mesma. 
