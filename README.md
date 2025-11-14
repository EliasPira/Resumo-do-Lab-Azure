# 📘 Certificação Microsoft Azure AI-900 — Introdução aos Conceitos Básicos

![Azure Badge](https://img.shields.io/badge/Microsoft%20Azure-Cloud%20Fundamentals-blue?logo=microsoft-azure)
![DIO Badge](https://img.shields.io/badge/DIO%20Bootcamp-AZ--900%20Fundamentos-purple?logo=data:image/svg+xml;base64,...)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Em%20Desenvolvimento-yellow)

Este repositório contém um resumo dos primeiros aprendizados do curso **AZ-900: Introdução aos Conceitos Básicos do Microsoft Azure**, ministrado na plataforma [DIO](https://www.dio.me/). O conteúdo é voltado para quem está iniciando na jornada de certificação **AZ-900**, com foco nos fundamentos da computação em nuvem e nos modelos de serviço da Microsoft Azure.

---

## 🧠 Conteúdo Abordado

### 1. Conceitos de Computação em Nuvem
- Definição: Computação em nuvem é o fornecimento de serviços de computação pela Internet, permitindo inovação rápida, escalabilidade e economia de custos.
- Modelo de responsabilidade compartilhada entre provedor e cliente.
- Diferença entre **CapEx** (despesas de capital) e **OpEx** (despesas operacionais).

### 2. Modelos de Implantação de Nuvem
| Modelo         | Características principais |
|----------------|----------------------------|
| Nuvem Pública  | Recursos acessíveis via Internet, sem despesas de capital, escalabilidade rápida. |
| Nuvem Privada  | Infraestrutura dedicada, controle total de segurança e manutenção. |
| Nuvem Híbrida  | Combinação dos dois modelos, flexibilidade para executar aplicações onde for mais adequado. |

### 3. Modelo de Preço Baseado em Consumo
- Pagamento conforme o uso.
- Previsibilidade de custos.
- Cobrança com base em recursos e serviços utilizados.

---

## 🛠️ Hands-On
O curso inclui atividades práticas para reforçar os conceitos aprendidos, permitindo aplicar os conhecimentos em cenários reais de uso da plataforma Azure.

---

## 🚀 Instalação de Ferramentas Azure

Para começar a praticar com os serviços da Microsoft Azure, siga os passos abaixo:

### 1. Criar uma Conta Gratuita no Azure
- Acesse: [https://azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free)
- Você receberá créditos gratuitos para testar os serviços.

### 2. Instalar o Azure CLI
O Azure CLI permite gerenciar recursos diretamente pelo terminal.

**Windows:**
```bash
winget install Microsoft.AzureCLI
```

**macOS:**
```bash
brew update && brew install azure-cli
```

**Linux (Ubuntu/Debian):**
```bash
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
```

### 3. Verificar a Instalação
```bash
az version
```

### 4. Fazer Login
```bash
az login
```

---

## 📍 Objetivos de Aprendizagem
- Compreender os fundamentos da computação em nuvem.
- Identificar os modelos de nuvem e seus casos de uso.
- Comparar os modelos de preços e entender o modelo baseado em consumo.

---

## 📚 Fonte
Material baseado nos slides oficiais da Microsoft utilizados no curso da DIO.

---
