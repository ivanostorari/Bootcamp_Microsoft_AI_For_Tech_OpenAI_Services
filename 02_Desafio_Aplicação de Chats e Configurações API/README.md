# API e Semantic Kernel Básico  

## Objetivos e Pré-requisitos  

### Objetivo Geral  
- **Acesso ao Azure Open AI**  
- **Compreensão dos LLMs (Modelos de Linguagem de Grande Escala)**  
- **Noções básicas de codificação**  

### Pré-requisitos  
- Entendimento das chamadas de API  
- Conceitos básicos sobre o Semantic Kernel e IA de Agentes  

## Suporte para Diversos Modos  
- **Chat**  
- **Completar**  
- **Imagens**  
- **Áudio**  

## Exemplos de Chamada da API  

### Uso da API  

```python  
client = AzureOpenAI(  
    azure_endpoint=os.getenv("AZURE_OPENAI_ENDPOINT"),  
    api_key=os.getenv("AZURE_OPENAI_API_KEY"),  
    api_version="2024-02-01"  
)

