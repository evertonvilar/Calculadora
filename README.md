# ⚙️ Calculadora Salesforce (APEX + LWC)

Este projeto é uma **Calculadora** desenvolvida com **Salesforce APEX** no backend e **Lightning Web Components (LWC)** no frontend.  
O objetivo é demonstrar a integração entre lógica de negócio em APEX e interface moderna com LWC, servindo como projeto de portfólio e base de aprendizado para outros desenvolvedores Salesforce.

---

## 🚀 Funcionalidades

- Cálculos aritméticos básicos (soma, subtração, multiplicação, divisão)  
- Backend em **APEX** para processamento dos valores  
- Frontend em **LWC**, totalmente responsivo  
- Integração com a plataforma **Salesforce DX**  
- Código modular e fácil de adaptar a novos contextos  

---

## 🧠 Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-------------|
| Backend | APEX |
| Frontend | Lightning Web Components (LWC) |
| Plataforma | Salesforce DX |
| IDE | Visual Studio Code |
| Controle de Versão | Git + GitHub |

---

## 💻 Estrutura do Projeto

Calculadora/
│
├── force-app/
│ ├── main/
│ │ ├── default/
│ │ │ ├── classes/ # Código APEX
│ │ │ │ ├── backEnd.cls
│ │ │ │ └── backEnd.cls-meta.xml
│ │ │ └── lwc/ # Componentes LWC
│ │ │ └── frontEnd/
│ │ │ ├── frontEnd.html
│ │ │ ├── frontEnd.js
│ │ │ └── frontEnd.js-meta.xml
│ │ └── config/
│ └── package.xml
│
├── README.md

yaml
Copiar código

---

## 🧩 Como Clonar e Rodar o Projeto Localmente

1. **Clone o repositório:**
git clone git@github.com:evertonvilar/Calculadora.git
cd Calculadora

2. **Autentique-se na sua org Salesforce (sandbox ou devhub):**
sfdx force:auth:web:login -d -a DevHub

3. **Crie uma scratch org (opcional para teste isolado):**
sfdx force:org:create -f config/project-scratch-def.json -s -a calculadora

4. **Envie o código para a org:**
sfdx force:source:push

5. **Abra a org e teste:**
sfdx force:org:open
Acesse o app Calculadora

🤝 Contribuições
Contribuições são muito bem-vindas!
Sinta-se à vontade para abrir um Pull Request com melhorias, correções ou novas features.

💡 Sugestões de evolução
Adicionar histórico de cálculos

Interface com SLDS (Salesforce Lightning Design System)

Testes automatizados em APEX e Jest (para LWC)

📄 Licença
Este projeto é open-source sob a licença MIT.

👤 Autor
Everton Reinaldo Vilar
📧 evertonreinaldovilar@gmail.com
💼 LinkedIn
💻 GitHub



💡 **Dica extra**:  
Se quiser deixar o README ainda mais atraente, posso adicionar:
- um **print da calculadora LWC** no topo (exibido automaticamente no GitHub);
- **badges visuais** de tecnologia (APEX, LWC, VSCode, GitHub, etc);
- e uma seção “📸 Screenshots”.

Quer que eu gere a **versão final com imagens e badges** (como os repositórios de portfólio mais profissionais)?






