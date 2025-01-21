### Uso do language studio para análise de sentimento

---

A abordagem decidida aqui, também mantém a simplicidade sem escalonamento apenas para conhecimento das ferramentas da Azure, dessa vez o language studio e análises de sentimento.

Para o teste primeiramente compilei alguns comentários de reviews um restaurante da minha cidade. Selecionei negativos e positivos
![Printscreen Compilado](https://github.com/falatfernando/ai-900-lab3/blob/main/processo.png?raw=true)

Então rodei a análise de sentimento via [Azure Language Studio](https://language.cognitive.azure.com/tryout/sentiment) após configurar o resource.

Achei muito interessante que ele separa o texto por sentenças e permite identificar uma análise mista, por exemplo essa primeira que subi que é uma review positiva porém começa com uma crítica não ao restaurante mas as opções veganas em outros lugares:

### Sentença Negativa
![Printscreen negativa](https://github.com/falatfernando/ai-900-lab3/blob/main/negativa.png?raw=true)

### Sentença Positiva
![Printscreen negativa](https://github.com/falatfernando/ai-900-lab3/blob/main/positiva.png?raw=true)