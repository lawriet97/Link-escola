# Link-escola
O projeto nasceu para ser uma alternativa 100% gratuita para escolas que oferecem cursos como serviço — como escolas de informática, de idiomas ou cursos profissionalizantes. A ideia principal foi fugir daquele formato EAD engessado e trazer algo muito mais interativo.

Para os professores, o sistema oferece um construtor de aulas bem dinâmico. Em vez de apenas anexar um PDF ou um link de vídeo, o educador monta o conteúdo por blocos. Dá para empilhar textos, citações, quizzes e até jogos da memória na mesma página. Como o banco de dados foi estruturado para salvar tudo isso em um formato flexível (JSON), a tela de criação funciona quase como montar blocos de Lego, dando total liberdade.

Já o grande diferencial para o aluno é a gamificação. Conforme eles avançam nas aulas, acertam as questões e cumprem o tempo mínimo de leitura configurado pelo professor, o sistema distribui pontos de experiência (XP). Isso alimenta um ranking global da escola, o que gera uma competição saudável e aumenta bastante o engajamento da turma.

Outro ponto forte é a infraestrutura. O sistema foi desenhado para rodar direto na rede local (LAN) da escola. Usando um servidor leve em Node.js com banco SQLite na máquina principal, os computadores dos alunos acessam tudo com velocidade máxima. É uma solução muito rápida e que não depende de uma internet externa boa para funcionar sem travamentos no dia a dia.
