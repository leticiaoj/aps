# Cyber Chase Technology

**APS - Qualidade de Software**

- Autoras: Leticia Jesus e Julia Silva
- Foco: planejamento e garantia de qualidade antes do desenvolvimento
- Vídeo da apresentação: [https://youtu.be/wo-XcBDZbIY?is=SmbHzu0LwTOqxCS5](https://youtu.be/wo-XcBDZbIY?is=SmbHzu0LwTOqxCS5)

---

## Sobre este repositório

- Reúne os artefatos da APS (Atividade Prática Supervisionada) da disciplina de Qualidade de Software
- **Esta é a etapa anterior ao desenvolvimento**
- O foco não é o código final, e sim o planejamento: recursos, metodologia, riscos, requisitos de qualidade e protótipo
- O objetivo é garantir boas práticas de desenvolvimento, para que o software seja robusto, seguro e de fácil manutenção
- Prevenir problemas no planejamento custa menos do que corrigi-los depois da implementação

---

## O projeto: Cyber Chase

- Plataforma web educacional de segurança cibernética
- O usuário constrói seu "escudo cibernético" pouco a pouco, por meio de cursos e testes
- Missão: capacitar pessoas com conhecimento e habilidades para navegar com segurança no mundo digital
- Visão: criar um ambiente digital mais seguro por meio de ampla educação em segurança cibernética
- Valores: Educação, Segurança, Empoderamento, Inclusão e Inovação

### Principais funcionalidades previstas

- Catálogo de cursos com busca (Antivírus, Segurança na Nuvem, Criptografia, Firewall, Autenticação multifator, Prevenção contra phishing, entre outros)
- Cybot, assistente virtual (chatbot) para ajudar o usuário
- Teste de phishing: ao "cair" no teste, o usuário é direcionado a cursos relacionados (phishing, engenharia social, vírus, ransomware e gestão de vulnerabilidades)
- Página Sobre nós (missão, visão e valores)
- Página de Contato

---

## Recursos necessários

- **IDE:** Visual Studio Code
- **Versionamento:** Git e GitHub
- **Frontend:** HTML, CSS, JavaScript, TypeScript com framework React
- **Backend:** Java utilizando o modelo MVC (Model, View e Controller)
- **Banco de dados:** 3 tabelas (usuários, cursos e temas dos cursos)
- **Hospedagem:** GitHub Pages
- **Design:** Canva (protótipos)
- **Comunicação:** WhatsApp, Discord e Asana

---

## Metodologia de desenvolvimento

- Metodologia ágil com Scrum e Kanban
- Sprints quinzenais com funções rotativas (PO, SM e Dev)
- Daily Scrum e subdivisão de tarefas
- Quadro Kanban para visualização do fluxo de trabalho

---

## Gestão de riscos

Riscos identificados antes de escrever qualquer código, cada um com mitigação definida.

- **R1 - Falhas de segurança cibernética** (impacto alto, probabilidade média)
  - Causa: implementação inadequada de criptografia ou autenticação
  - Mitigação: padrões de segurança (HTTPS, JWT, hashing), revisão de código e testes
- **R2 - Incompatibilidade com dispositivos móveis** (impacto médio, probabilidade média)
  - Causa: layout não responsivo em dispositivos com resolução diferente de desktops
  - Mitigação: design responsivo e testes em navegadores e dispositivos reais
- **R3 - Lentidão no sistema** (impacto alto, probabilidade média)
  - Causa: backend sobrecarregado de requisições
  - Mitigação: cache, limitação de requisições, banco eficiente e testes de estresse
- **R4 - Vazamento de dados pessoais** (impacto alto, probabilidade baixa)
  - Causa: falta de conformidade com a LGPD
  - Mitigação: mapear dados sensíveis, aplicar boas práticas de privacidade e termos de uso
- **R5 - Inviabilidade técnica do chatbot** (impacto médio, probabilidade média)
  - Causa: limitações das APIs ou custos de uso
  - Mitigação: escolher ferramentas com bom custo-benefício e prototipar antes
- **R6 - Problemas de escalabilidade futura** (impacto médio, probabilidade baixa)
  - Causa: arquitetura pouco flexível
  - Mitigação: arquitetura modular e limpa, seguindo princípios SOLID
- **R7 - Dependência de ferramentas externas** (impacto médio, probabilidade baixa)
  - Causa: APIs ou serviços de terceiros ficarem indisponíveis
  - Mitigação: fallback ou plano B e documentação das APIs críticas

![Gestão de riscos](docs/imagens/gestao%20de%20riscos.jpg)

---

## Plano de qualidade

Relaciona as necessidades do cliente a requisitos técnicos, com pesos de 1 a 5.

- **Facilidade de uso** (peso 5)
  - Requisitos: interface intuitiva e menu claro (peso técnico 5)
- **Tempo de resposta** (peso 4)
  - Requisitos: backend otimizado, cache e queries (peso técnico 4)
- **Segurança dos dados** (peso 5)
  - Requisitos: criptografia, autenticação e JWT (peso técnico 5)
- **Acessibilidade** (peso 3)
  - Requisitos: layout responsivo e acessível (peso técnico 3)
- **Atualizações e manutenções** (peso 2)
  - Requisitos: código limpo e modular (peso técnico 4)

![Plano de qualidade](docs/imagens/plano%20de%20qualidade.jpg)

---

## Protótipo

Telas prototipadas antes do desenvolvimento:

- Página inicial com o Cybot

  ![Protótipo 7](docs/imagens/prototipo_7.jpg)

- Sobre nós

  ![Protótipo 8](docs/imagens/prototipo_8.jpg)

- Nossos cursos

  ![Protótipo 9](docs/imagens/prototipo_9.jpg)

- Resultado do teste de phishing

  ![Protótipo 10](docs/imagens/prototipo_10.jpg)

---

## Próximos passos

- Implementar frontend e backend seguindo o plano de qualidade e os riscos mapeados
- Aplicar as mitigações previstas (segurança, responsividade, desempenho e LGPD)
- Validar o sistema com testes e revisões de código

---

## Contexto acadêmico

- Projeto desenvolvido como APS da disciplina de Qualidade de Software
