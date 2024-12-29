# cortex_wine_demo
Snowflake Cortex Demo on Wine Reviews

# [WIP]
# Demo to leverage the Cortex Chat API for an agentic generative AI application that can answer various user prompts about wine.

## The following components will be included in the demo
- RAG model for qualitative questions of wine descriptions 
    - Embed wine descriptions into a vector store with Cortex Search
    - Build a RAG model on cortex services
    - Instrument and evaluate RAG model performance with Trulens
- Text-to-SQL model for more structured queries into wine review dataset
    - Create semantic model using semantic model generator tool
    - Use cortex analyst to set up text to sql LLM
