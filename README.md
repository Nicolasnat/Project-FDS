# TransferConnect

## 🚛 Descrição do Projeto
Uma aplicação web voltada para **conectar pessoas que precisam fretar cargas ou fazer mudanças com funcionários e caminhoneiros especialistas na área**.  
A ideia é a pessoa fornecer detalhes do serviço que busca e o site facilitar a conexão com quem pode ajudá-la.

---

## 👥 Cargos da Equipe
- **Carlos** - Product Owner (PO)  
- **Allana** - Scrum Master  
- **Nícolas** - Desenvolvedor  
- **Lara Thaylanne Ho da Silva** - Desenvolvedora  

---

##  Histórias de Usuário + 3C’s

### Motoristas

#### 1. Cadastro de motorista  
**Card:** Como motorista, eu quero me cadastrar na plataforma para que clientes possam me encontrar para fretes.  
**Conversation:** O motorista deve fornecer nome, CNH, tipo de caminhão, telefone e e-mail. O sistema valida os dados.  
**Confirmation:** O cadastro aparece no sistema, permitindo que clientes encontrem o motorista.

---

#### 2. Atualização de perfil  
**Card:** Como motorista, eu quero atualizar minhas informações (caminhão, disponibilidade, fotos) para que meu perfil esteja sempre correto.  
**Conversation:** O motorista acessa seu perfil e pode editar campos como caminhão, disponibilidade e imagens.  
**Confirmation:** As mudanças são salvas e exibidas imediatamente no perfil atualizado.

---

#### 3. Receber notificações de pedidos  
**Card:** Como motorista, eu quero receber notificações quando um cliente buscar caminhões na minha região para poder responder rapidamente.  
**Conversation:** O sistema envia alertas por push ou e-mail sempre que um cliente fizer um pedido na área do motorista.  
**Confirmation:** O motorista recebe a notificação corretamente e consegue visualizar os detalhes do pedido.

---

#### 4. Visualizar histórico de fretes  
**Card:** Como motorista, eu quero ver os fretes que já realizei para acompanhar meu desempenho e histórico de serviços.  
**Conversation:** O sistema lista todos os fretes concluídos com data, cliente e valor.  
**Confirmation:** O motorista acessa a tela de histórico e encontra seus fretes anteriores.

---

#### 5. Avaliação recebida  
**Card:** Como motorista, eu quero receber avaliações dos clientes para melhorar minha reputação na plataforma.  
**Conversation:** Após um frete, o cliente avalia o motorista com estrelas e comentário.  
**Confirmation:** A avaliação aparece no perfil do motorista e influencia sua nota média.

---

### Clientes/Usuários

#### 6. Cadastro de cliente  
**Card:** Como cliente, eu quero criar uma conta para que eu possa contratar motoristas de caminhão para minhas mudanças ou fretes.  
**Conversation:** O cliente fornece nome, telefone, e-mail e senha. O sistema valida os dados.  
**Confirmation:** O cadastro é concluído e o cliente pode acessar a plataforma.

---

#### 7. Buscar motoristas  
**Card:** Como cliente, eu quero filtrar motoristas por região, tipo de caminhão e disponibilidade para encontrar alguém adequado rapidamente.  
**Conversation:** O cliente aplica filtros de busca (ex.: caminhão baú, região X).  
**Confirmation:** O sistema exibe apenas motoristas que atendem os filtros aplicados.

---

#### 8. Contato com motorista  
**Card:** Como cliente, eu quero poder entrar em contato diretamente com o motorista para combinar detalhes do frete.  
**Conversation:** O cliente pode iniciar um chat ou visualizar telefone/e-mail do motorista.  
**Confirmation:** O contato é realizado e a comunicação entre cliente e motorista funciona corretamente.

---

#### 9. Avaliar motorista  
**Card:** Como cliente, eu quero avaliar o serviço do motorista após o frete para ajudar outros usuários a escolherem motoristas confiáveis.  
**Conversation:** O cliente atribui uma nota (1 a 5 estrelas) e comentário após o serviço.  
**Confirmation:** A avaliação é salva e exibida no perfil do motorista.

---

#### 10. Histórico de contratações  
**Card:** Como cliente, eu quero ver os fretes que já contratei para acompanhar meus gastos e referências de motoristas confiáveis.  
**Conversation:** O sistema mostra uma lista com data, motorista contratado e valor do frete.  
**Confirmation:** O cliente acessa a tela de histórico e vê seus fretes passados.

---

#### 11. Atualizar perfil do cliente  
**Card:** Como cliente, eu quero poder atualizar as informações do meu perfil.  
**Conversation:** O cliente pode editar dados como nome, telefone, e-mail e senha na área de perfil.  
**Confirmation:** As alterações são salvas e refletidas imediatamente no sistema.

---

#### 12. Fazer solicitação do frete  
**Card:** Como cliente, eu quero solicitar o frete para realizar o transporte dos meus objetos.  
**Conversation:** O cliente preenche os detalhes do frete (endereço de origem e destino, tipo de carga, data).  
**Confirmation:** A solicitação aparece para motoristas disponíveis, e o cliente recebe confirmação de envio.

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ef5df443-796a-48b5-b7ff-d3ad85208529" />


## ✅ DoD (Definition of Done)

Histórias do Motorista

1. Cadastro de motorista

O formulário de cadastro funciona e valida todos os campos obrigatórios.

Dados são armazenados corretamente no banco.

Motorista pode fazer login após cadastro.

Testado em desktop e mobile.

PO validou que motoristas aparecem na busca dos clientes.

2. Atualização de perfil

Motorista consegue editar suas informações (caminhão, disponibilidade, fotos).

Alterações são salvas e refletidas em tempo real.

Dados antigos são substituídos corretamente.

Testado em diferentes navegadores.

PO aprovou a entrega após validação no sistema.

3. Receber notificações de pedidos

Motorista recebe notificações em tempo real (push/e-mail).

Notificação contém informações básicas do pedido.

Só motoristas na região recebem o alerta.

Funcionalidade testada simulando pedidos reais.

Validado em Sprint Review com feedback do PO.

4. Visualizar histórico de fretes

Tela lista todos os fretes concluídos com data, cliente e valor.

Histórico mostra informações corretas do banco.

Motorista consegue acessar de forma simples.

Testado com diferentes cenários (nenhum, poucos e muitos fretes).

PO validou o histórico em demonstração.

5. Avaliação recebida

Sistema registra avaliações dos clientes.

Avaliações aparecem no perfil do motorista.

Média é recalculada automaticamente.

Testado com avaliações positivas e negativas.

PO aprovou após validação funcional.

Histórias do Cliente

6. Cadastro de cliente

Formulário de cadastro implementado com validação de campos.

Dados salvos corretamente no banco.

Cliente consegue acessar a conta após cadastro.

Testado em navegadores e dispositivos diferentes.

Validado e aprovado pelo PO.

7. Buscar motoristas

Cliente consegue aplicar filtros (região, tipo de caminhão, disponibilidade).

Resultados retornam apenas motoristas compatíveis.

Testado com diferentes combinações de filtros.

Pesquisa rápida e sem erros.

PO validou em Sprint Review.

8. Contato com motorista

Cliente pode iniciar chat ou visualizar contato do motorista.

Mensagens são enviadas e recebidas corretamente.

Testado em cenários reais (cliente → motorista).

Funcionalidade segura (somente usuários logados podem acessar).

Validado com feedback do PO.

9. Avaliar motorista

Cliente consegue dar nota (1–5) e comentário.

Avaliação é registrada e exibida no perfil do motorista.

Testado com múltiplos clientes avaliando o mesmo motorista.

Dados armazenados corretamente.

Validado na Sprint Review.

10. Histórico de contratações

Cliente visualiza todos os fretes contratados.

Informações exibidas: motorista, data, valor.

Testado com histórico vazio e histórico extenso.

Listagem clara e sem erros de duplicação.

Validado pelo PO.

11. Atualizar perfil do cliente

Cliente consegue editar dados pessoais (nome, e-mail, telefone, senha).

Alterações são salvas no banco e refletidas de imediato.

Testado em desktop e mobile.

Funcionalidade validada pelo PO em Sprint Review.

12. Fazer solicitação do frete

Cliente consegue preencher dados (origem, destino, tipo de carga, data).

Solicitação aparece para motoristas disponíveis.

Cliente recebe confirmação do pedido.

Testado em cenários de diferentes tipos de carga.

Validado pelo PO na Sprint Review.



---
