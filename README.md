# AI Investment Insight Team: Revolutionizing Financial Analysis 


# Steps

- Install Ollama
- Create custom local LLM made for CrewAI
  - Run the ./setup/create_llama2-model-file.sh       or 
            ./setup/create_llama2-model-file.sh
  script
    - Make this script executable by running `chmod +x ./setup/create_llama2-model-file.sh `
      or copy and paste commands into terminal
  - This will create a model file in the models directory
  - To change models, edit the create_model.sh script
- Verify you are using local llm
  - `cat ~/.ollama/logs/server.log`

# Tips

- If using multiple models,

# Warnings & Recommendations

- Ollama doesn't work with Async tasks and a bunch of newer CrewAI features yet.
- Lose context. Be very explicit in tasks. Not generic.

# Resources

- Want to find out which LLMs support which features in CrewAI? Here's the link for you:
  - https://python.langchain.com/docs/integrations/llms/
- Learn more about Modelfiles:
  - https://github.com/ollama/ollama/blob/main/docs/modelfile.md
- Check out CrewAI's instructions for working with Ollama and running LLMs locally:
  - https://docs.crewai.com/how-to/LLM-Connections/#connect-crewai-to-llms
