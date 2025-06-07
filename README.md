# VDPsPrivate
extra curricular project

# Projeto
O VidaPlus é uma solução avançada de gestão hospitalar, projetada para centralizar e otimizar todas as atividades relacionadas à área da saúde. A plataforma integra, de forma eficiente, hospitais, clínicas, laboratórios e serviços de atendimento domiciliar (home care) em um único ambiente unificado.

# Principais Funcionalidades
* Gestão de Pacientes
* Cadastro completo
* Histórico médico
* Agendamento de consultas

# Gestão de Profissionais
* Cadastro de médicos
* Controle de agendas
*	Histórico de atendimentos
# Administração Hospitalar
* Controle de leitos
* Gestão de suprimentos
* Relatórios financeiros

#  Telemedicina
*	Consultas online
*	Prescrições digitais
*	Agendamento remoto
*	Prontuários eletrônicos

# Pré-requisitos
*	Java
*	Postman (para testes da API)
# Instalação
1.	Clone o repositório
Plain Text
git clone https://github.com/seu-usuario/vidaplus.git
cd vidaplus
1.	Crie e ative o ambiente virtual
Plain Text
# Windows
python -m venv venv
venv\Scripts\activate
# Linux/Mac
python -m venv venv
source venv/bin/activate
1.	Instale as dependências
Plain Text
pip install -r requirements.txt
1.	Configure as variáveis de ambiente Crie um arquivo .env na raiz do projeto:
Plain Text
DATABASE_URL=sqlite:///vidaplus.db
JWT_SECRET_KEY=sua-chave-secreta-aqui
FLASK_ENV=development
FLASK_APP=app.py
1.	Execute o sistema
Plain Text
python app.py
📡 Endpoints da API
🔐 Autenticação
•	POST /api/auth/registro - Registro de novo usuário
•	POST /api/auth/login - Login de usuário
👤 Pacientes
•	POST /api/pacientes - Cadastro de novo paciente
•	GET /api/pacientes/{id} - Consulta de paciente
•	PUT /api/pacientes/{id} - Atualização de dados
📅 Consultas
•	POST /api/consultas - Agendamento de consulta
•	GET /api/consultas/{id} - Detalhes da consulta
•	PUT /api/consultas/{id} - Atualização de status
📋 Prontuários
•	POST /api/prontuarios - Criação de prontuário
•	GET /api/prontuarios/{id} - Consulta de prontuário
•	PUT /api/prontuarios/{id} - Atualização de prontuário
🛡️ Segurança
•	🔒 Autenticação via JWT
•	🔐 Senhas criptografadas com bcrypt
•	👥 Controle de acesso por perfil
•	📜 Conformidade com LGPD
•	🔍 Registro de auditoria
📊 Banco de Dados
O sistema utiliza SQLite como banco de dados principal, com suporte para migração para PostgreSQL em ambiente de produção.
🧪 Testes
Para executar os testes:
Plain Text
python -m pytest
📝 Documentação
A documentação completa do sistema está disponível em:
•	Documentação Técnica
•	Guia de API
•	Manual do Usuário
🤝 Contribuindo
1.	Faça o fork do projeto
2.	Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
3.	Commit suas mudanças (git commit -m 'Add some AmazingFeature')
4.	Push para a branch (git push origin feature/AmazingFeature)
5.	Abra um Pull Request
📞 Suporte
Para suporte, envie um email para suporte@vidaplus.com ou abra uma issue no GitHub.

