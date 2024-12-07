# 🌾Feira Fácil - Marketplace de Feirantes e Consumidores  

Conectamos feirantes a consumidores finais, promovendo economia, praticidade e sustentabilidade. 🚀

## 📚 Sobre o Projeto

Este projeto tem como objetivo combater dois grandes problemas:  

- *Insegurança alimentar*: Que afeta cerca de 18% da população brasileira.  
- *Desperdício de alimentos*: Estima-se que 40% ocorra nos centros de distribuição, mercados e consumidores finais.

A solução proposta é um *marketplace inovador* que conecta feirantes e consumidores finais. O feirante pode vender produtos perecíveis que seriam desperdiçados, enquanto o cliente adquire alimentos saudáveis a preços mais baixos.

---

## 🎯 Público-Alvo  

- *Feirantes*: Que desejam evitar perdas financeiras e vender excedentes.  
- *Consumidores*: Que buscam alimentos acessíveis e de qualidade.

---

## 🌟 Diferenciais  

- *Incentivo à economia circular*: Redução de desperdício de alimentos.  
- *Preços competitivos*: Produtos com valores abaixo do mercado.  
- *Conexão local*: Aproximação entre feirantes e consumidores.  

---

## 🛠️ Funcionalidades  

### Para Feirantes  

1. *Cadastro*: Criação de conta com informações pessoais, localização e dados da feira/ponto de venda.  
2. *Adicionar Produto*: Cadastro do nome do produto, quantidade, preço sugerido e raio de entrega/retirada.  
3. *Gestão de Ofertas*: Publicação de produtos, edição, remoção e histórico de vendas.  

### Para Consumidores  

1. *Cadastro*: Conta criada com informações pessoais e localização.  
2. *Procurar Produtos*: Busca personalizada por produtos com filtros por preço e localização.  
3. *Contato Direto*: Possibilidade de combinar detalhes com o feirante.  
4. *Pagamento*: Escolha de métodos de pagamento e opções de retirada.  

---

## 📈 Fluxo de Processo  

### Feirante  
1. Cadastro → 2. Adicionar Produto → 3. Publicação → 4. Gestão de Ofertas  

### Cliente  
1. Cadastro → 2. Procurar Produto → 3. Seleção → 4. Pagamento  

---

## 📑 Colaboradores  

- *Andre Palacio*  
- *Ana Beatriz Chagas*  
- *Bernardo Maia*  
- *Ian Tiozzo Brussolo*  
- *João Pedro Vilela*  
- *Lucas T. F. Garcia*  
- *Luan Acquafreda*  
- *Matheus Rocha*  
- *Matheus Salermo*  
- *Rafael Balocco*  

## **Requisitos**

### **Ambiente de Desenvolvimento**
- **Sistema Operacional**: Ubuntu 22.04 LTS
- **Dependências**:
  - **Node.js** (v18 ou superior)
  - **npm** (v9 ou superior) ou **yarn**
  - **Docker** e **Docker Compose** (para execução de serviços adicionais, como banco de dados)
  - **Git** (para versionamento e clonagem do repositório)

---

## **Passo a Passo para Configuração**

### **1. Clone o Repositório**
```bash
git clone https://github.com/seu-usuario/feira-facil.git
cd feira-facil
```

### **2. Instale as Dependências**
Certifique-se de que você está na raiz do projeto.

#### Com npm:
```bash
npm install
```

#### Ou com yarn:
```bash
yarn install
```

### **3. Configure o Ambiente**
Renomeie o arquivo `.env.example` para `.env` e configure as variáveis necessárias, como URL do banco de dados, chaves de API, etc.

```bash
cp .env.example .env
nano .env
```

### **4. Suba os Serviços Necessários (opcional)**
Se o projeto utiliza um banco de dados ou outros serviços via Docker, utilize o comando:

```bash
docker-compose up -d
```

### **5. Execute a Aplicação**
Certifique-se de que todas as dependências e serviços estão configurados corretamente.

#### Ambiente de Desenvolvimento:
```bash
npm run dev
```

#### Ambiente de Produção:
```bash
npm run build
npm start
```

---

## **Acesso ao App**
Após executar o comando acima, o aplicativo estará disponível localmente em:

```
http://localhost:3000
```

---

## **Contribuição**
Quer contribuir com o **Feira Fácil**? Siga os passos abaixo:
1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas alterações:
   ```bash
   git commit -m "Minha contribuição"
   ```
4. Suba sua branch:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---
