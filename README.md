# Bot-CRM

## 📌 Sobre o Projeto

O **Bot-CRM** é uma API escrita em JavaScript que se conecta ao WhatsApp associado a um número de telefone e permite a integração com um modelo de processamento de mensagens rodado localmente no **LM Studio**. O objetivo principal é facilitar o primeiro contato com clientes por meio de requisições simples ao LangFlow.

## 🏗️ Estrutura do Modelo no LangFlow

O modelo no LangFlow deve conter um prompt adequado ao que se deseja construir. A estrutura básica é:

1. **Chat Input**
2. **Prompt** (contém as instruções desejadas para o modelo)
3. **LM Studio** (modelo escolhido para o processamento)
4. **Chat Output**

## 🔗 Conexões

As conexões devem ser realizadas conforme o fluxograma acima. No **LM Studio**, é essencial configurar corretamente os seguintes campos:

- **Model Name**: Nome do modelo pré-carregado em sua máquina (servidor).
- **Base URL**: Endereço onde o modelo está disponível localmente.

## ⚙️ Requisitos Recomendados

Para garantir um funcionamento eficiente, recomenda-se:

- **Modelo de IA**: Utilizar modelos destilados de até 10GB.
- **Memória RAM**: No mínimo 16GB.
- **Processador**: Mínimo 6 núcleos.
- **Placa de Vídeo (GPU)**:
  - **NVIDIA**: Série RTX 20XX ou superior.
  - **AMD**: Final da série 5000 ou superior.
  - Pelo menos 8GB de VRAM.

## 🚀 Como Usar

1. Configure o **LM Studio** e carregue o modelo desejado.
2. Ajuste o **LangFlow** para estruturar o fluxo de mensagens conforme as necessidades do seu projeto.
3. Execute a API do **Bot-CRM** e conecte-a ao WhatsApp.
4. Teste as interações e faça ajustes conforme necessário.
