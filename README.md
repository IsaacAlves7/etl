# 🎂 ELT/ETL
**Web scraping** é o processo de extração automatizada de informações de páginas da web, simulando o comportamento de um usuário humano, mas de forma programática. Em vez de copiar dados manualmente de um site, um script ou programa acessa o conteúdo HTML da página, interpreta sua estrutura e coleta as informações desejadas — como textos, links, imagens, preços, notícias ou qualquer dado disponível publicamente.

Em resumo, o web scraping é uma forma de coletar dados estruturados a partir de fontes não estruturadas na web — transformando páginas HTML em datasets úteis para análise, aprendizado de máquina, automação e relatórios, desde que feito com responsabilidade e dentro dos limites éticos e legais.

![FB_IMG_1735839034899](https://github.com/user-attachments/assets/9f2416bb-e69c-4115-a296-e29d8772f503)
![FB_IMG_1735839040474](https://github.com/user-attachments/assets/4264a5e2-45f3-45a9-8256-71477561a9cb)
![FB_IMG_1735839051637](https://github.com/user-attachments/assets/da293070-2dd5-4379-8a54-95c558ad9cb5)
![FB_IMG_1735839060017](https://github.com/user-attachments/assets/becb6f34-6db3-4a10-b1ea-a4469759dab1)

Tecnicamente, o web scraping funciona em três etapas principais:

1. Primeiro, o programa **envia uma requisição HTTP** para o servidor do site, assim como um navegador faria quando você acessa uma página.
2. Em seguida, ele **recebe o HTML bruto** como resposta.
3. Por fim, esse HTML é **analisado e interpretado**, geralmente com bibliotecas que entendem a estrutura do documento (como `BeautifulSoup`, `lxml` ou `Scrapy` no Python), para extrair os elementos específicos que você quer, identificados por tags, classes, IDs ou atributos.

Esse processo é amplamente usado em análise de dados, ciência de dados, monitoramento de preços, coleta de notícias, SEO, e até inteligência de mercado, quando APIs não estão disponíveis. 

Por exemplo, se uma loja online não oferece uma API pública, você pode criar um scraper que visita as páginas de produtos e extrai automaticamente nomes, valores e descrições.

No entanto, há uma questão ética e legal importante: nem todos os sites permitem scraping. Muitos têm restrições no arquivo `robots.txt`, que define o que pode ou não ser acessado por scripts automatizados. Além disso, scraping em excesso pode sobrecarregar servidores e ser considerado uso indevido. Por isso, boas práticas incluem respeitar limites de requisição, identificar o agente de usuário (user-agent) e nunca raspar dados pessoais ou protegidos por login.

- https://github.com/microsoft/markitdown
- https://github.com/browser-use/browser-use
- https://python.plainenglish.io/full-apache-airflow-tutorial-interview-notes-zero-to-ready-31b5e3ae5b56

<img width="1280" height="799" alt="687640848_959948516644747_1933087596060947387_n" src="https://github.com/user-attachments/assets/9ebe4b03-c4f5-415f-b435-fc84b11d1f27" />
