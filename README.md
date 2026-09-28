Assistente Virtual de Filmes e Séries (CineBot)
Repositório desenvolvido para o Lab "Construa Seu Assistente Virtual Com Inteligência Artificial" da DIO.

1. Documentação do Agente
O que faz: Um assistente virtual inteligente especializado em recomendar filmes e séries com base no género, ano, plataforma ou mood do utilizador.

Para quem serve: Para entusiastas de cinema e espectadores indecisos que procuram recomendações personalizadas rapidamente.

Comportamento esperado: Respostas objetivas, empáticas, alinhadas exclusivamente aos dados do catálogo oficial, sem inventar informações (zero alucinações).

2. Base de Conhecimento (data/)
Os dados encontram-se estruturados em formato JSON na pasta data/movies_db.json, contendo títulos, géneros, anos, notas, plataformas de streaming e sinopses.

3. Prompts do Agente (docs/)
Prompt de Sistema:

"Tu és o 'CineBot', um assistente virtual especialista em cinema e séries. O teu objetivo é ajudar o utilizador a escolher o que ver a seguir de forma personalizada. Utiliza exclusivamente os dados fornecidos na base de conhecimento. Se não tiveres informações sobre o título pedido, sê honesto e diz que não consta no catálogo atual."

4. Aplicação Funcional (src/)
Implementado em Python (src/main.py), permitindo realizar consultas diretas e interativas ao catálogo de dados com base nos filtros solicitados.

5. Avaliação e Métricas
Critérios de Qualidade:

Precisão na filtragem por género e plataforma.

Ausência total de dados fictícios sobre o catálogo.

Clareza, utilidade e rapidez na recomendação final.

6. Pitch Final
O Problema: Excesso de opções nas plataformas de streaming gera perda de tempo e indecisão crónica.

A Solução: Um assistente virtual direto e inteligente que filtra o catálogo ideal em segundos.

O Valor: Praticidade, assertividade e uma experiência de descoberta de conteúdos simplificada.
