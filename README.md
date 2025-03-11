# Clerk API + Firestore para Google Sheets (Apps Script)

Scripts em Google Apps Script que integram dados do Clerk e Firestore em planilhas Google Sheets, facilitando análises e geração de insights para dashboards em plataformas como o Looker Studio.

## 📌 Funcionalidades

- **Extração e atualização automática de usuários** cadastrados no Clerk com detalhamento completo.
- **Cálculo e atualização automática de métricas** semanais e mensais sobre usuários do Clerk.
- **Exportação automatizada dos dados do Firestore** para o Google Sheets usando Firebase Functions.
- Facilita a criação de dashboards e visualizações de dados utilizando ferramentas como o **Looker Studio**.

## 🚀 Aplicações e Impacto

Criei esses scripts para apoiar pessoas e organizações que trabalham com dados abertos e impacto social, permitindo gerenciar grandes volumes de informações com eficiência. São especialmente úteis para:

- Organizações sociais e empresas que utilizam **dados abertos** para gerar insights estratégicos.
- Equipes técnicas e analistas que desejam automatizar a coleta e visualização de dados.
- Projetos que necessitam monitorar rapidamente o engajamento e comportamento de usuários.

Utilizo esses scripts atualmente para gerar dashboards interativos no Looker Studio, permitindo análises detalhadas sobre engajamento, comportamento de usuários e métricas essenciais para desempenho organizacional.

## 🔑 Ferramentas Utilizadas

- [Clerk](https://clerk.com/docs): Gestão de usuários e autenticação.
- **Firestore & Firebase Functions**: Infraestrutura segura para armazenamento e entrega de dados.
- **Google Sheets**: Planilhas colaborativas para armazenamento e visualização de dados.
- **Looker Studio**: Criação visual e acessível de insights e dashboards interativos.

## 🌐 Dados Abertos e Impacto Social

Disponibilizo este repositório como parte do meu compromisso com a inovação social, transparência e colaboração aberta. Meu objetivo é apoiar organizações e iniciativas sociais na democratização e gestão eficiente de dados abertos, fortalecendo projetos de impacto.

### Contribuições
Contribuições são muito bem-vindas! Fique à vontade para fazer um fork, abrir issues ou enviar pull requests.

## 🛠️ Configuração

Siga os passos abaixo para adaptar os scripts ao seu ambiente:

1. Clone ou faça o download deste repositório.
2. Copie os arquivos da pasta `src` para um projeto no [Google Apps Script](https://script.google.com/).
3. Configure as variáveis necessárias no seu ambiente do Apps Script:

### Exemplo de variáveis necessárias:

```javascript
const CLERK_API_KEY = 'sua-chave-clerk';
const CLERK_USERS_API_URL = 'https://api.clerk.com/v1/users';
const FIRESTORE_ENDPOINT = 'seu-endpoint-firebase-functions';
