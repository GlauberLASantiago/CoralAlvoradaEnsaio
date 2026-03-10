# 🎶 Coral Alvorada - Kits de Ensaio

O **Coral Alvorada - Kits de Ensaio** é uma aplicação web desenvolvida para facilitar o acesso às faixas de estudo e ensaio do coral. O sistema funciona como um player de áudio online que carrega automaticamente músicas hospedadas em um repositório do GitHub, organizando-as em uma playlist simples, visual e fácil de usar.

A proposta é oferecer aos integrantes do coral uma ferramenta prática para ouvir, revisar e praticar os materiais de ensaio em qualquer dispositivo com navegador.

## ✨ Funcionalidades

- Carregamento automático de arquivos `.mp3` a partir de um repositório no GitHub
- Exibição das músicas em formato de playlist
- Reprodução de áudio diretamente no navegador
- Controles de:
  - play e pause
  - música anterior
  - próxima música
  - progresso da faixa
  - volume
  - loop
- Destaque visual da música em reprodução
- Exibição de:
  - título da faixa atual
  - tempo decorrido
  - duração total
- Navegação simples e intuitiva
- Interface adaptada para uso interno do coral

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Tailwind CSS**
- **Font Awesome**
- **GitHub API**
- **Elemento `<audio>` do navegador**

## 🎯 Objetivo do Projeto

O projeto foi criado para centralizar os materiais de ensaio do **Coral Alvorada** em uma interface única, acessível e fácil de manter. Em vez de distribuir arquivos manualmente, o sistema busca as músicas diretamente do repositório configurado, facilitando a atualização e o acesso pelos membros.

## ⚙️ Como funciona

A aplicação consulta a API do GitHub para listar os arquivos de áudio disponíveis no repositório configurado. Em seguida:

1. filtra os arquivos com extensão `.mp3`;
2. monta automaticamente a playlist;
3. permite ao usuário escolher ou controlar a reprodução das faixas;
4. toca os áudios diretamente a partir dos links de download do GitHub.

## ▶️ Como usar

1. Abra a página da aplicação em um navegador moderno.
2. Aguarde o carregamento automático da playlist.
3. Clique em uma música da lista para iniciar a reprodução.
4. Use os controles do player para:
   - pausar ou continuar
   - voltar ou avançar faixas
   - ajustar o volume
   - ativar ou desativar o loop
   - navegar pela barra de progresso

## 🎧 Recursos do player

O player oferece:

- reprodução contínua entre faixas;
- seleção manual de músicas;
- controle visual da faixa atual;
- barra de progresso interativa;
- ajuste de volume em tempo real;
- opção de repetição da música.

## 🌐 Integração com GitHub

O sistema depende de um repositório GitHub configurado com arquivos de áudio em formato `.mp3`. A playlist é gerada dinamicamente a partir desses arquivos, o que torna o gerenciamento simples: basta adicionar ou remover músicas no repositório para atualizar o conteúdo do player.

## 🎨 Interface

A interface foi desenvolvida com foco em clareza e praticidade, utilizando:

- painel central com player destacado;
- playlist organizada em lista;
- contraste forte entre fundo e controles;
- ícones intuitivos;
- paleta em tons escuros com destaques em laranja e verde.

## 📱 Responsividade

A aplicação funciona bem em:

- computadores
- tablets
- celulares

## 📁 Estrutura do Projeto

O projeto está concentrado em um único arquivo HTML com:

- **HTML**: estrutura visual do player e da playlist
- **CSS**: personalização visual e identidade do projeto
- **JavaScript**: carregamento dos arquivos do GitHub, lógica do player e interações do usuário

## ✅ Possíveis usos

Este projeto pode ser utilizado como:

- player interno para corais;
- central de materiais de ensaio;
- repositório musical acessível por navegador;
- ferramenta de apoio para estudo vocal;
- modelo para bibliotecas simples de áudio online.

## 🔒 Observação

Este site foi pensado para uso interno e exclusivo dos membros do **Coral Alvorada**.

## 📄 Licença

Este projeto pode ser utilizado para fins educacionais, musicais e institucionais.
