# 🎓 EscolaOnline

**EscolaOnline** é um projeto de website responsivo para uma escola de formação em **b-learning** (*blended learning*), uma modalidade que combina ensino online e presencial.

O site apresenta a instituição, os cursos disponíveis, informações detalhadas sobre cada formação e formas de contacto, com uma interface adaptada a computadores, tablets e telemóveis.

> **Projeto académico:** desenvolvido para a unidade curricular de **Composição de Interfaces Multiplataforma**, do curso de **Informática Web, Móvel e na Nuvem** da **Universidade da Beira Interior (UBI)**.

## ✨ Funcionalidades

- **Página inicial** com apresentação da plataforma, cursos em destaque e testemunhos ilustrativos de alunos.
- **Catálogo de seis cursos** com imagens, descrições e acesso a páginas de detalhes.
- **Páginas individuais de cursos**, com objetivos, conteúdos programáticos e apresentação do respetivo instrutor.
- **Secção “Sobre Nós”** com história, missão, visão, valores e explicação da metodologia b-learning.
- **Página dos autores**, com apresentação dos elementos responsáveis pelo desenvolvimento.
- **Página de contacto**, com formulário, informações de contacto e mapa incorporado.
- **Navegação entre páginas** e layout responsivo com Bootstrap.
- **Ícones, elementos visuais e ligações externas** para melhorar a apresentação do website.

## 📚 Cursos apresentados

| Curso | Página |
|---|---|
| Desenvolvimento Web Fullstack | [`curso-detalhes.html`](curso-detalhes.html) |
| Ciência de Dados | [`curso-detalhes1.html`](curso-detalhes1.html) |
| Design UX/UI | [`curso-detalhes2.html`](curso-detalhes2.html) |
| Marketing Digital | [`curso-detalhes3.html`](curso-detalhes3.html) |
| Inteligência Artificial | [`curso-detalhes4.html`](curso-detalhes4.html) |
| Gestão de Projetos | [`curso-detalhes5.html`](curso-detalhes5.html) |

Cada página apresenta uma descrição da formação, tópicos de aprendizagem e informações sobre o instrutor e a turma.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura e conteúdo das páginas.
- **CSS3** — estilos, cores, organização visual e adaptação a diferentes ecrãs.
- **Bootstrap 5.3** — grelha responsiva, componentes e navegação.
- **Bootstrap Icons** — ícones da interface.
- **JavaScript (via Bootstrap)** — comportamento de componentes como o menu de navegação responsivo.
- **Google Analytics** — código de integração de análise de visitas presente nas páginas.

O website utiliza também algumas imagens e recursos alojados externamente.

## 📁 Estrutura do repositório

```text
EscolaOnline/
├── index.html               # Página inicial
├── cursos.html              # Catálogo dos cursos
├── curso-detalhes.html      # Desenvolvimento Web Fullstack
├── curso-detalhes1.html     # Ciência de Dados
├── curso-detalhes2.html     # Design UX/UI
├── curso-detalhes3.html     # Marketing Digital
├── curso-detalhes4.html     # Inteligência Artificial
├── curso-detalhes5.html     # Gestão de Projetos
├── sobre.html               # Informações sobre a instituição
├── autores.html             # Autores do projeto
├── contacto.html            # Contactos e formulário
├── styles.css               # Estilos da página inicial
├── curso.css                # Estilos do catálogo
├── curso-detalhes.css       # Estilos das páginas de curso
├── sobre.css                # Estilos da página Sobre
├── autores.css              # Estilos da página Autores
├── contstyles.css           # Estilos da página Contacto
├── tiago.png                # Imagem de um dos autores
└── Simao.jpeg               # Imagem de um dos autores
```

## 🚀 Como executar

Este é um projeto **estático**, pelo que não necessita de instalar Node.js, bases de dados ou dependências através de um gestor de pacotes.

1. Clona o repositório:

   ```bash
   git clone https://github.com/Simao-PB/EscolaOnline.git
   ```

2. Entra na pasta do projeto:

   ```bash
   cd EscolaOnline
   ```

3. Abre o ficheiro **`index.html`** no navegador.

Em alternativa, podes abrir a pasta no **Visual Studio Code**, instalar a extensão **Live Server** e selecionar **Open with Live Server** no ficheiro `index.html`.

> Recomenda-se uma ligação à Internet para carregar o Bootstrap, os ícones, as imagens externas e os restantes recursos disponibilizados através de CDNs.

## 📱 Objetivos do projeto

O desenvolvimento da EscolaOnline teve como principais objetivos:

- Aplicar princípios de **design responsivo** e composição de interfaces multiplataforma.
- Organizar conteúdo educativo de forma clara e intuitiva.
- Construir uma navegação consistente entre várias páginas.
- Explorar os componentes e o sistema de grelha do Bootstrap.
- Considerar aspetos de acessibilidade e experiência de utilização na interface.

## ⚠️ Estado atual e limitações

A EscolaOnline é um **protótipo de interface** e não uma plataforma de gestão de aprendizagem completa.

- O **formulário de contacto** apresenta campos para preenchimento, mas não está ligado a um serviço de envio ou armazenamento de mensagens.
- Os botões **“Inscrever-se”** nas páginas dos cursos não estão ligados a um sistema de inscrições.
- Não existe, neste repositório, um **backend**, uma **base de dados** ou um sistema de autenticação de utilizadores.
- Os conteúdos institucionais, contactos, datas e testemunhos fazem parte da demonstração do website e não devem ser tratados como informação operacional de uma escola real.

## 👨‍💻 Autores

- **Tiago Bolota**
- **Simão Barroso**

Projeto desenvolvido no âmbito da Universidade da Beira Interior.

---

**Repositório:** [Simao-PB/EscolaOnline](https://github.com/Simao-PB/EscolaOnline)
