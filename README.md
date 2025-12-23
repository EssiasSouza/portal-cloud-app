## 📘 Portal Cloud – Aplicação Node.js (Curso Alura)

Este repositório contém uma aplicação **Node.js com Express**, desenvolvida **exclusivamente para fins educacionais**, como parte do curso:

> **5555 – Oracle Cloud Infrastructure: banco de dados e infraestrutura como código**
> Plataforma: **Alura**

O projeto é utilizado como base prática para estudos envolvendo:

* Aplicações web em Node.js
* Organização de projetos com Express
* Integração com banco de dados
* Conceitos de infraestrutura como código (IaC)
* Provisionamento e testes em ambiente cloud (Oracle Cloud Infrastructure)

---

## 🚀 Executando a aplicação localmente

### Pré-requisitos

* **Node.js (LTS)** instalado
* **npm** (instalado junto com o Node.js)

### Passo a passo

1. Clone o repositório:

   ```bash
   git clone <url-do-repositorio>
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd portal-cloud
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie a aplicação:

   ```bash
   npm start
   ```

5. Acesse no navegador:

   ```
   http://localhost:3000
   ```

---

## 📂 Estrutura do projeto (resumida)

* `app.js` – Configuração principal da aplicação Express
* `bin/www` – Ponto de entrada do servidor HTTP
* `routes/` – Definição das rotas
* `services/` – Camada de serviços
* `views/` – Templates EJS
* `public/` – Arquivos estáticos (CSS, favicon, etc.)
* `orm-portal-cloud/` – Arquivos relacionados à infraestrutura como código (Terraform)

---

## ⚠️ Aviso sobre uso educacional e direitos autorais

Este projeto faz parte de um **curso pago da plataforma Alura** e está disponibilizado aqui **somente para fins de estudo, aprendizado e referência técnica**.

* O conteúdo original do curso, a proposta didática, a estrutura pedagógica e os materiais associados são **propriedade intelectual da Alura**.
* Este repositório **não tem finalidade comercial**.
* **Não é permitida** a redistribuição, venda ou reaproveitamento deste projeto como material de curso, treinamento ou produto comercial.
* O uso deste código deve respeitar os **Termos de Uso da Alura**.

Caso você seja aluno(a) do curso, utilize este repositório apenas como apoio aos estudos.

---

## 📌 Observação final

Este repositório reflete **um exercício prático** e **não deve ser considerado um projeto de produção**. Ajustes de segurança, arquitetura e escalabilidade seriam necessários para uso em ambientes reais.
