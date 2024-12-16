![image](https://github.com/user-attachments/assets/70fdaf7d-79b8-4957-a09d-cfeed412ce44)



# Nearby - Aplicativo de Clube de Benefícios

**Nearby** é um aplicativo móvel que oferece uma plataforma exclusiva de clube de benefícios. Ele é composto por duas partes principais:

- **API** - Backend desenvolvido em Node.js.
- **Aplicativo Móvel** - Desenvolvido com *React Native* utilizando *Expo*.

---

## 🚀 Tecnologias Utilizadas

### Backend
- Node.js
- Express.js

### Frontend
- React Native
- Expo

---

## ⚙️ Configuração do Projeto

Siga as instruções abaixo para executar o projeto localmente.

### 📥 1. Clone o Repositório

```bash
git clone https://github.com/caiquejv/nearby.git
cd nearby
```

---

### 🛠 2. Configurando e Rodando a API

Navegue até a pasta **API** e instale as dependências:

```bash
cd API
npm install
```

Inicie a API com o comando:

```bash
npm start
```

A API estará disponível no seguinte endereço padrão:

```
http://localhost:3333
```

⚠️ **Importante**: Anote o endereço IP da sua máquina caso esteja rodando em rede local.

---

### 📱 3. Configurando e Rodando o Aplicativo Móvel

Abra outro terminal e navegue até a pasta **nearby-mobile**:

```bash
cd nearby-mobile
```

Instale as dependências:

```bash
npm install
```

Atualize o arquivo `Service/api.ts` com o IP correto da sua máquina:

```javascript
const apiUrl = 'http://<seu_ip>:<porta>'; // Substitua <seu_ip> e <porta>
```

Inicie o aplicativo móvel com Expo:

```bash
npx expo start
```

Caso queira rodar no seu dispositivo **Android** ou **iOS**, baixe o **Expo Go** na loja de aplicativos e leia o **QRCode** gerado quando você inicia o `expo start`.  

---

## 🎯 Funcionalidades

- Interface simples e intuitiva para acesso a benefícios exclusivos.
- Arquitetura orientada por API para alta escalabilidade.
- Integração perfeita com Expo para um desenvolvimento ágil.

---

## 🗂 Estrutura de Diretórios

```plaintext
nearby/
├── API/              # Implementação do backend (Node.js)
├── nearby-mobile/    # Aplicativo React Native (Expo)
```




