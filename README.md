🗓️ Escala 6x2 - Calendário de Folgas

Aplicação web interativa e responsiva para consulta e navegação da escala de trabalho 6x2, desenvolvida por Mariana Martins.

📋 Sobre o Projeto

A Escala 6x2 é um modelo de jornada de trabalho onde o colaborador trabalha 6 dias consecutivos e folga 2 dias, totalizando um ciclo contínuo de 8 dias.

Esta aplicação permite consultar rapidamente a escala de qualquer mês e ano, filtrando por turma (Letra A, B, C ou D) ou visualizando todas as turmas juntas no mesmo calendário.

✨ Funcionalidades

📱 100% Responsivo: Projetado com layout fluido para telas de smartphones, tablets e computadores.

📆 Filtros por Mês e Ano: Navegação livre por qualquer período do calendário.

👥 Visão Individual ou Geral:

Filtre por uma turma específica (Letra A, B, C ou D).

Selecione "🌟 Todas as Turmas Juntas" para ver quais turmas folgam a cada dia.

⭐ Destaque de Fim de Semana: Identifica e destaca automaticamente as folgas que caem no Sábado ou Domingo.

🔍 Detalhamento ao Clicar: Clique/Toque em qualquer dia para abrir um modal com o status exato de todas as turmas naquele dia.

📊 Resumo de Estatísticas: Exibe o total de folgas do mês, folgas em fins de semana e a data da próxima dupla de folga.

🛠️ Tecnologias Utilizadas

HTML5 & JavaScript Vanilla (ES6+) - Lógica e cálculo da escala contínua.

Tailwind CSS - Estilização moderna e layout responsivo.

FontAwesome - Ícones visuais e intutivos.

Google Fonts (Inter) - Tipografia limpa e legível.

🧮 Lógica e Matemática Modular (Ciclo de 8 Dias)

O cálculo do status de folga/trabalho é baseado na diferença de dias entre a data consultada e a data base da turma (Data_Base):

$$\text{DiffDias} = \text{DataAlvo} - \text{DataBase}$$

$$\text{PosicaoCiclo} = ((\text{DiffDias} \pmod 8) + 8) \pmod 8$$

PosicaoCiclo 0 ou 1: Dia de Folga 🎉 (Dia 1 ou Dia 2 da dupla).

PosicaoCiclo 2 a 7: Dia de Trabalho 💼 (Dia 1 ao Dia 6 da jornada).

🚀 Como Executar o Projeto Localmente

Clone ou Baixe o repositório:

git clone https://github.com/SEU-USUARIO/escala-6x2.git

Abra o arquivo:
Basta dar um duplo clique no arquivo index.html para abri-lo em qualquer navegador (Chrome, Edge, Safari, Firefox). Nenhuma instalação de servidor ou dependência externa é necessária!

👩‍💻 Autoria e Créditos

Desenvolvido por Mariana Martins.

Escala 6x2 - Calendário de Folgas | Direitos Reservados
