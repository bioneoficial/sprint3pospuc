https://bioneandroid.atlassian.net/jira/software/projects/KAN/list?jql=project+%3D+KAN+ORDER+BY+cf%5B10019%5D+ASC&atlOrigin=eyJpIjoiNGEyNTUxYzRlMTdmNDY0NGE0OThhNGNmZDhiZDQ0MmEiLCJwIjoiaiJ9

5. Definition of Ready (DoR) & Definition of Done (DoD)


Definition of Ready (DoR):
A história segue o padrão "Como/Quero/Para".
Os critérios de aceitação estão descritos em formato Gherkin (Dado/Quando/Então).
A estimativa do esforço foi definida em Story Points.
O wireframe do Figma para a funcionalidade foi desenvolvido e linkado no card.
Definition of Done (DoD) + Requisitos Não Funcionais:
O código passou por Code Review de outro desenvolvedor e foi aprovado.
Testes unitários e de integração escritos com cobertura mínima de 80%.
A funcionalidade foi homologada pelo PO.
Performance (Requisito Não Funcional): O tempo de resposta para qualquer API de consulta de ofertas deve ser inferior a 1.5 segundos.
Responsividade (Requisito Não Funcional): A tela do cliente deve ser exibida corretamente sem quebras em larguras de 360px (mobile básico) a 1920px (desktop).
Segurança (Requisito Não Funcional): Senhas de usuários e estabelecimentos devem ser salvas no banco de dados com hash de criptografia forte (ex: bcrypt). As conexões devem usar HTTPS.