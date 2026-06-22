# Requisitos do Sistema

## Problema Identificado

As plataformas educacionais atuais apresentam algumas limitações que impactam a colaboração e o acompanhamento dos alunos, tais como:

* Dificuldade para criação de grupos diretamente na plataforma.
* Poucas atualizações e recursos colaborativos.
* Ausência de uma inteligência artificial voltada para explicações e resumos educacionais.
* Interface pouco organizada para gerenciamento de conteúdos.
* Falta de ferramentas para visualização de dados acadêmicos através de gráficos e tabelas.
* Pouca visibilidade para os professores sobre o engajamento dos alunos nos conteúdos disponibilizados.
* Limitações para avaliações em grupo.
* Ausência de papéis intermediários, como monitores.
* Falta de critérios personalizados para avaliação de trabalhos em grupo.

      # Requisitos Funcionais

## RF01 - Autenticação

O sistema deve permitir login utilizando conta Google.

## RF02 - Gerenciamento de Turmas

O sistema deve permitir que usuários participem e gerenciem turmas.

## RF03 - Criação de Atividades

O sistema deve permitir que professores criem atividades para suas turmas.

## RF04 - Comunicação

O sistema deve permitir troca de mensagens entre alunos e professores.

## RF05 - Organização de Conteúdo

O sistema deve permitir a classificação e organização de conteúdos e documentos.

## RF06 - Grupos de Estudo

O sistema deve permitir a criação de grupos de estudo e conversa pelos alunos.

## RF07 - Monitoramento de Acesso

O sistema deve permitir que professores visualizem quais alunos acessaram conteúdos e documentos.

## RF08 - Avaliações em Grupo

O sistema deve permitir avaliações realizadas em grupo.

## RF09 - Perfis de Usuário

O sistema deve possuir diferentes perfis de acesso:

* Administrador
* Professor
* Aluno
* Monitor

## RF10 - Inteligência Artificial

O sistema deve disponibilizar uma inteligência artificial capaz de gerar explicações e resumos sobre conteúdos educacionais.

## RF11 - Avaliação Colaborativa

O sistema deve permitir que alunos avaliem apresentações e trabalhos realizados por outros grupos através de notas e critérios definidos pelo professor.

Ao final da avaliação, o sistema deve calcular automaticamente a média das notas atribuídas pelos alunos e combiná-la com a nota do professor, utilizando pesos configuráveis para compor a nota final da atividade.

## RF12 - Chat ao Vivo

O sistema deve permitir a comunicação em tempo real entre alunos, professores e monitores por meio de um chat ao vivo integrado às turmas e grupos de estudo.

## RF13 - Chamadas de Vídeo

O sistema deve permitir a realização de chamadas de vídeo entre os participantes de uma turma ou grupo de estudo, possibilitando reuniões, aulas e apresentações remotas.

## RF14 - Compartilhamento durante Chamadas

O sistema deve permitir que usuários compartilhem links, documentos e materiais de apoio durante as chamadas de vídeo.

## RF15 - Gerenciamento de Sessões de Vídeo

O sistema deve permitir que professores criem, iniciem, encerrem e gerenciem sessões de videoconferência vinculadas às suas turmas.

    # Requisitos Não Funcionais

## RNF01 - Segurança

O sistema deve garantir autenticação segura por meio de contas Google, protegendo os dados dos usuários contra acessos não autorizados.

## RNF02 - Escalabilidade

O sistema deve suportar o crescimento gradual do número de usuários e turmas sem perda significativa de desempenho ou necessidade de reestruturação completa da arquitetura.

## RNF03 - Integração

O sistema deve ser desenvolvido de forma a permitir futuras integrações com sistemas acadêmicos, serviços externos e plataformas institucionais.

## RNF04 - Usabilidade

O sistema deve apresentar uma interface intuitiva, responsiva e organizada, permitindo que alunos e professores utilizem suas funcionalidades com facilidade.

## RNF05 - Disponibilidade

O sistema deve permanecer disponível para acesso contínuo durante os períodos letivos, garantindo alta disponibilidade e minimizando interrupções no serviço.

## RNF06 - Desempenho

O sistema deve responder às principais operações do usuário em até 3 segundos em condições normais de utilização.

## RNF07 - Manutenibilidade

O sistema deve possuir uma arquitetura que facilite correções, atualizações e inclusão de novas funcionalidades ao longo do tempo.

    # Funcionalidades Futuras

* Integração completa com sistemas de escolas e universidades.
* Controle de presença automatizado.
* Integração com sistemas de notas institucionais.
* Relatórios avançados de desempenho.
* Dashboards com gráficos e indicadores acadêmicos.
* Evolução da Inteligência Artificial para suporte educacional avançado.
