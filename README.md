# Journeys Project

Este projeto é composto por duas partes:
- **Backend** em Node.js + TypeScript, responsável por processar e expor os dados de jornadas (touchpoints) via API.
- **Frontend** em React + TypeScript, que consome a API e exibe os dados de forma visual e organizada.

## 🚀 Tecnologias utilizadas
- Node.js + TypeScript (backend)
- Express (servidor da API)
- React + TypeScript (frontend)
- Fetch API para comunicação entre frontend e backend
- CSS inline para estilização simples

## 📂 Estrutura
- `api-node-typescript/` → código da API (porta 3000)
- `frontend/` → código React (App.tsx renderiza os cards das jornadas)
- Interfaces `Journey` e `Touchpoint` definem a estrutura dos dados recebidos

## ⚙️ Pré-requisitos
Antes de rodar o projeto, você precisa ter instalado:
- [Node.js](https://nodejs.org/) 
- [npm](https://www.npmjs.com/)



## ▶️ Como executar o backend

1. Entre na pasta do backend:
cd api-node-typescript


2.Instale as dependencias pelo command prompt do Vscode
npm install

3.Inicie o servidor
npm run dev

4. O backend vai ficar disponivel em
http://localhost:3000/journeys

▶️ Como executar o frontend 
1. Em outro terminal, entre na pasta do frontend:
cd frontend
2.Instale as dependências:
npm install
3.Inicie o servidor de desenvolvimento:
npm run dev

O frontend ficará disponível em:  http://localhost:5173
(ou a porta configurada pelo React/Vite)
📊 Funcionalidades- Exibe jornadas com:
- ID da sessão
- Número de canais (touchpoints)
- Datas de início e fim
- Blocos coloridos para cada canal (utm_source)

-------------------------------------------------------------------------------
ENGLISH
# Journeys Project

This project consists of two parts:

- **Backend** in Node.js + TypeScript, responsible for processing and exposing journey data (touchpoints) via API.

- **Frontend** in React + TypeScript, which consumes the API and displays the data in a visual and organized way.

## 🚀 Technologies Used
- Node.js + TypeScript (backend)
- Express (API server)
- React + TypeScript (frontend)
- Fetch API for communication between frontend and backend
- Inline CSS for simple styling

## 📂 Structure
- `api-node-typescript/ → API code (port 3000)
- `frontend/` → React code (App.tsx renders journey cards)
- `Journey` and `Touchpoint` interfaces define the structure of the received data

## ⚙️ Prerequisites
Before running the project, you need to have installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## ▶️ How to run the backend

1. Go to the folder of backend:
cd api-node-typescript

2. Install the dependencies via the VS Code command prompt:
 npm install

4. Start the server:
 npm run dev

6. The backend will be available at:
http://localhost:3000/journeys

▶️ How to run the frontend:

1. In another terminal, navigate to the frontend folder:
cd frontend
2. Install the dependencies:
npm install
3. Start the development server:
npm run dev
The frontend will be available at: http://localhost:5173

(or the port configured by React/Vite)

📊 Features: Displays journeys with:
- Session ID
- Number of channels (touchpoints)
- Start and end dates
- Colored blocks for each channel (utm_source)





