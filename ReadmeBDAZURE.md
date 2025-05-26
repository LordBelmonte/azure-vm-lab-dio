# 💾 Desafio DIO - Configuração de Instância de Banco de Dados na Azure

Este repositório foi criado como parte do desafio prático da DIO, cujo objetivo é configurar uma instância de banco de dados no Microsoft Azure e documentar toda a experiência. As anotações e dicas aqui registradas servirão como material de apoio para estudos e futuras implementações.

---

## 🎯 Objetivo

Aplicar os conhecimentos adquiridos durante o curso da DIO, configurando uma instância gerenciada de SQL Database no Azure e documentando cada etapa de forma clara e estruturada.

---

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
- Azure SQL Database
- Git e GitHub
- GitHub Markdown
- Azure Portal

---

## 🚀 Etapas Realizadas

1. **Acesso ao Portal Azure**
   - Navegação até o [portal Azure](https://portal.azure.com)
   - Login com conta pessoal ou educacional

2. **Criação do Grupo de Recursos**
   - Nome: `grupo-sql-dio`
   - Região: `Brazil South`

3. **Criação da Instância SQL**
   - Tipo de Serviço: **Banco de Dados SQL**
   - Nome do servidor: `sqlserver-dio`
   - Nome do banco de dados: `banco-dio`
   - Autenticação: `SQL Authentication (usuário e senha)`
   - Camada de preço: `Basic` (para ambiente de testes)

4. **Configuração de Regras de Firewall**
   - IP do cliente adicionado para permitir acesso remoto
   - Nenhum outro acesso externo liberado por segurança

5. **Teste de Conexão**
   - Utilização do **Azure Data Studio** ou **SQL Server Management Studio**
   - Teste de conexão utilizando string de conexão fornecida no portal

---

## 📝 Dicas Importantes

- 🔐 **Segurança:** Nunca exponha portas ou IPs desnecessariamente. Sempre restrinja os acessos ao seu IP ou faixas confiáveis.
- 💸 **Custo:** Para evitar cobranças, use a camada "Basic" ou exclua os recursos após os testes.
- 🧰 **Ferramentas úteis:** Azure Data Studio é leve e ideal para testes rápidos com bancos SQL.
- 🗑️ **Encerramento:** Sempre lembre de **deletar o grupo de recursos** ao final do laboratório para liberar recursos e evitar custos.

---

## 📸 Imagens

As capturas de tela do processo estão organizadas na pasta [`/images`](./images) (opcional).

---

## 🔗 Recursos e Documentações

- [Criar uma instância de Banco de Dados SQL - Microsoft Learn](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)
- [GitHub Markdown Guide](https://guides.github.com/feat)

