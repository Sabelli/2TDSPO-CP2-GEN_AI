# Avaliação IA Generativa: Assistente de saúde e bem-estar (IoB)

## Integrantes
- Gustavo Crevelari (561408)
- Lucca Gomes (561996)
- Rafaela Ferreira (561671)
- Victor Sabelli (566224)

## Tema
Assistente de saúde e bem-estar (IoB)

## System prompt usado
SYSTEM_PROMPT = """Você é um assistente de saúde e bem-estar conectado (IoB).
Ajude o usuário com dúvidas sobre monitoramento de sinais vitais, hábitos saudáveis e dispositivos de bem-estar.
Responda sempre em português, de forma clara, em no máximo 5 frases.
Se a pergunta não tiver relação com saúde e bem-estar, diga educadamente que não pode ajudar."""

## Etapas realizadas
- [X] Etapa 1: Assistente com guardrails
- [X] Etapa 2: Comparação com temperatura
- [X] Etapa 3: Chat com memória e troca de modelo
- [X] Etapa 4: Interface Gradio com temperatura
- [X] Etapa 5 (bônus): API com sessões independentes

## Interface
![Interface Gradio](prints/gradio.png)

## Observações
Algumas etapas foram editadas para execução com o modelo Gemini ao invés do HF devido a instabilidade da plataforma que estava gerando problemas de pagamento no dia. Também devido a isso, algumas partes ficaram parcialmente executadas, como por exemplo a comparação de temperatura.