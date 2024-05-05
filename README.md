## <img src="https://media.giphy.com/media/EfDzi9nKLFPtF0VwTk/giphy.gif?cid=790b7611oh7utjjmlaa2v5p8nz9285pq24nl7jp0kgd6jyis&ep=v1_stickers_search&rid=giphy.gif&ct=s" alt="Giphy: Mascote do Reddit erguendo um corçação"  style="align=center" height="50"/> Redddit Sent 

Análise de Sentimentos de Submissões do Reddit

Este script desenvolvido tem como objetivo automatizar a análise de sentimentos em comentários de submissões do Reddit. Ele utiliza a API do Reddit para coletar submissões de diferentes subreddits especificados pelo usuário. Em seguida, solicita a classificação dos comentários em positivos, negativos ou neutros em relação às emoções humanas por meio da integração com o ChatGPT, uma inteligência artificial de linguagem natural.


___


**Funcionalidades Principais**

1.  **Coleta de Dados do Reddit**: O script permite especificar os subreddits alvo para coletar submissões recentes.

2. **Análise de Sentimentos**: Utilizando a API do ChatGPT, o script classifica os comentários associados às submissões em três categorias: positivos, negativos ou neutros.

3. **Construção de Análise**: Com base nos resultados da classificação de sentimentos, o script gera uma análise detalhada dos dados coletados. Isso pode incluir estatísticas sobre a distribuição de sentimentos, palavras-chave associadas a cada categoria e insights sobre a percepção geral dos usuários em relação aos tópicos discutidos nos subreddits selecionados.

___

**Principais Ferramentas**

1. **Bilioteca PRAW**: para acesso à API do Reddit \
    _É importante ressaltar que para ultilizaro o código, um ID de APP do Reddit será solicitad, assim como uma chave de acesso (secret_key) e o ID (username) do usuário._
   
3. **Bibloteca openai**: para cesso à API do chat GPT (versão GPT-3-TURBO) \
   _Ao utilizar o APP uma API_KEY será solicitada._
