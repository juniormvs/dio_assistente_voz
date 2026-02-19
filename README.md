# dio_assistente_voz
Assistente de voz usando whisper e groq

>Única alteração que deve ser feita é na parte do código abaixo, onde você deverá substituir GROQ_API_KEY pela sua API_KEY, seja ela da groq, openAI, ou qualquer outra.
```client = OpenAI(
    base_url = 'https://api.groq.com/openai/v1',
    api_key = os.environ.get('GROQ_API_KEY')
)
```
