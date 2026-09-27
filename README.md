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
  - forma de onda e progresso interativos
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

A aplicação usa um catálogo gerado automaticamente pelo GitHub Pages e, se necessário, consulta a API do GitHub para listar os arquivos de áudio. Em seguida:

1. organiza os arquivos `.mp3` nas seis coleções configuradas;
2. permite ao usuário escolher primeiro uma pasta;
3. apresenta somente as faixas daquela pasta;
4. permite voltar à página inicial para trocar de pasta;
5. permite controlar a reprodução das faixas;
6. toca os áudios diretamente do site ou por links alternativos do GitHub.

O player ignora arquivos vazios ou menores que 1 KB, tenta mais de um endpoint do GitHub quando uma fonte falha e exibe uma mensagem clara caso o arquivo enviado não seja um MP3 válido.

> **Importante:** renomear um arquivo vazio para `.mp3` não o transforma em áudio. Antes de enviar, confirme que o arquivo toca localmente e tem tamanho maior que 1 KB. Depois do envio, aguarde a conclusão do commit/deploy e recarregue a página.

## ▶️ Como usar

1. Abra a página da aplicação em um navegador moderno.
2. Aguarde o carregamento automático da playlist.
3. Clique em uma música da lista para iniciar a reprodução.
4. Use os controles do player para:
   - pausar ou continuar
   - voltar ou avançar faixas
   - ajustar o volume
   - ativar ou desativar o loop
   - navegar pela forma de onda da faixa

## 🎧 Recursos do player

O player oferece:

- reprodução contínua entre faixas;
- seleção manual de músicas;
- controle visual da faixa atual;
- forma de onda real e interativa para acompanhar ou alterar o ponto de reprodução;
- ajuste de volume em tempo real, com slider visível também no celular;
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

Os áudios são organizados desta forma:

- `Cantata-E-Era-Natal`: arquivos cujo nome começa com `0`;
- `Pasta-1`: arquivos cujo nome começa com `1`;
- `Pasta-2`: arquivos cujo nome começa com `2`;
- `Pasta-3`: arquivos cujo nome começa com `3`;
- `Pasta-4`: arquivos cujo nome começa com `4`;
- `Pasta-5`: arquivos cujo nome começa com `5`.

O arquivo `catalog.json` é processado durante o deploy. Novos MP3 e novas pastas de primeiro nível aparecem automaticamente no site. Para manter uma pasta vazia no Git, adicione a ela um arquivo chamado `.gitkeep`.

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
