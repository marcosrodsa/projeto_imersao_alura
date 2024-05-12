# projeto_imersao_alura

## Sistema de informações sobre enchentes no RS

Utilizando a API do Google e o modelo Gemini Pro, este sistema centraliza dados sobre alertas, locais de doação, itens necessários e avisos da Defesa Civil. O acesso a informações cruciais é facilitado, auxiliando a população em momentos de crise.

### Funcionalidades

- **Informações sobre Enchentes:** Busca e resume notícias sobre enchentes no estado, permitindo perguntas detalhadas.
- **Alertas Personalizados:** Gera alertas personalizados para cidades específicas, incluindo áreas afetadas e recomendações de segurança.
- **Lugares para Doação:** Exibe informações sobre locais de doação, permitindo interações detalhadas.
- **Itens Necessários para Doação:** Mostra os itens necessários em diferentes locais, com possibilidade de perguntas específicas.
- **Informações da Defesa Civil:** Resume avisos e alertas, facilitando a disseminação de informações oficiais.

### Recursos Utilizados

- **Google Custom Search API:** Para buscar notícias e informações relevantes na web.
- **Gemini Pro:** Para resumir notícias e gerar alertas personalizados.
- **Geopy:** Para validar localizações informadas.
- **BeautifulSoup:** Para extrair informações de páginas HTML.
- **Markdown:** Para formatar a saída de texto.

### Como Utilizar

1. Clone o repositório.
2. Instale as dependências: `pip install google-api-python-client google-search-results geopy`
3. Obtenha sua chave de API do Google e substitua `SUA_API_KEY` no código.
4. Obtenha seu ID do mecanismo de pesquisa do Google e substitua `SEU_SEARCH_ENGINE_ID` no código.
5. Execute o script `main.py` e siga as instruções do menu.

### Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

### Observações

Este projeto é um protótipo e pode conter erros ou limitações. O uso da API do Google está sujeito a limites e pode gerar custos. As informações são para fins informativos e não substituem aconselhamento oficial.

### Licença

Este projeto está licenciado sob a licença MIT.
