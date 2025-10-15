# 🌈 Chromatch 🎨: Análise de Colorimetria Pessoal via IA (Protótipo Mobile Acadêmico)

![Status do Projeto](https://img.shields.io/badge/status-prot%C3%B3tipo%20acad%C3%AAmico-blue)
![Tecnologia Principal](https://img.shields.io/badge/Tecnologia-Python%20%7C%20OpenCV%20%7C%20IA%20(base44)-orange)
![Licença](https://img.shields.io/badge/license-MIT-green)

## ✨ Visão Geral: Seu Sommelier Pessoal de Cores

Bem-vindo(a) ao **Chromatch 🎨**, um protótipo de aplicativo mobile que explora a interseção entre inteligência artificial, processamento de imagem e os princípios da colorimetria sazonal. Este projeto acadêmico foi desenvolvido com o intuito de demonstrar como a tecnologia pode oferecer soluções de personalização inovadoras no setor de beleza e moda.

Pense no Chromatch como seu **sommelier pessoal de cores**: assim como um sommelier analisa o vinho para recomendar a harmonização perfeita, o Chromatch analisa o tom de pele do usuário para decifrar seu subtom, profundidade e intensidade. Com base nessa análise detalhada, o aplicativo recomenda paletas de cores personalizadas e harmoniosas para vestuário e maquiagem, seguindo o Método Sazonal Expandido de 12 Estações. É a ciência da cor ao seu alcance, transformando a forma como você interage com o mundo das cores.

Este projeto visa não apenas oferecer uma ferramenta prática, mas também servir como um estudo de caso robusto para a aplicação de conceitos de Gestão da Tecnologia da Informação (GTI), visão computacional e interação usuário-sistema.

## 🎯 Objetivos Principais do Projeto (Foco Acadêmico e GTI)

O Chromatch foi concebido com os seguintes pilares acadêmicos e práticos:

*   **Demonstrar Conhecimento em GTI:** Aplicar e aprofundar conhecimentos em gestão de projetos de TI, inteligência artificial, desenvolvimento mobile (conceitual) e experiência do usuário (UX) em um contexto prático e inovador.
*   **Prototipagem e Validação:** Desenvolver um protótipo funcional para validar a viabilidade técnica da análise colorimétrica digital via IA e sua aplicabilidade no mercado.
*   **Estudo de Caso Abrangente:** Servir como um estudo de caso para análise de requisitos, design de sistemas, metodologia de desenvolvimento (agile), e estratégias de testes em um ambiente de inovação tecnológica.
*   **Inovação e Pesquisa:** Explorar e contribuir para a pesquisa acadêmica sobre o potencial da IA na personalização de serviços nos setores de beleza e moda.

## 👥 Público-Alvo (Para quem é o Chromatch?)

Nosso foco de estudo e teste se concentra em:

*   **Primário (Voluntários de Teste):** Indivíduos interessados em moda, beleza e autoimagem que buscam compreender sua colorimetria pessoal e que estejam dispostos a fornecer feedback para o aprimoramento do protótipo.
*   **Secundário (Acadêmico/Profissional):** Estudantes, professores e pesquisadores das áreas de GTI, design, visão computacional e moda, que podem avaliar a inovação e a execução técnica do projeto.

## 🚀 Funcionalidades Essenciais (MVP: Minimum Viable Product para o Projeto)

Para este protótipo acadêmico, o Chromatch se concentra nas seguintes funcionalidades críticas:

### A. Módulo de Análise de Tom de Pele (O Coração da Pesquisa do Chromatch)

Onde a mágica da IA acontece. Este módulo é responsável por decifrar as nuances do seu tom de pele.

*   **Entrada de Dados para Análise:**
    *   **Captura via Câmera (Primária):** O usuário posiciona o smartphone para capturar uma foto de sua pele (ex: pulso, pescoço ou queixo). O Chromatch oferece guias visuais e instruções claras ("Procure iluminação natural", "Remova maquiagem", "Mantenha o braço esticado e sem sombras") para assegurar a qualidade da imagem para a IA.
    *   **Upload de Imagem (Alternativa):** Permite o upload de fotos da galeria, com as mesmas orientações de qualidade.
*   **Processamento da Imagem:** A inteligência artificial (utilizando a capacidade do `base44`) analisa a imagem, focando em áreas de pele exposta para identificar o **subtom** (quente, frio, neutro), a **profundidade** (claro, médio, escuro) e a **intensidade** (brilhante, suave).
*   **Questionário Complementar (Validação de Dados):** Um questionário interativo sobre características pessoais (ex: "Sua pele bronzeia ou queima facilmente?", "Qual a cor das veias no seu pulso?", "Cor natural dos olhos e cabelo"). As respostas são usadas para refinar, validar ou comparar com a análise visual da IA.
*   **Algoritmo de Classificação:** A IA cruza os dados de subtom, profundidade e intensidade para classificar o usuário em uma das **12 estações expandidas da colorimetria** (ex: Primavera Quente, Verão Puro, Outono Suave, Inverno Brilhante).
*   **Feedback Visual da Análise:** O Chromatch apresenta o resultado de forma clara e amigável (ex: "Sua Estação de Colorimetria é: Primavera Clara ☀️"), incluindo uma breve explicação do que significa essa estação.

### B. Módulo de Recomendações de Paletas de Cores (A Aplicação do Conhecimento do Chromatch)

Com sua estação definida, é hora de descobrir seu universo de cores!

*   **Paleta Principal Personalizada:** Exibe uma paleta completa de cores ideais para a estação identificada, categorizadas (ex: Cores Primárias, Neutras, Cores de Acento). Cada cor é apresentada com seu nome e, se possível, seu código HEX/RGB/CMYK para referência técnica.
*   **Exemplos de Aplicação:** Para cada cor ou conjunto de cores, o Chromatch mostra exemplos visuais claros de aplicação:
    *   **Vestuário:** Imagens ilustrativas de tecidos ou peças na cor recomendada.
    *   **Maquiagem:** Sugestões de tons de batom, sombra, blush que harmonizem.
*   **Seção "Por que funciona?":** Breves explicações sobre os princípios da colorimetria por trás de cada recomendação, enriquecendo o caráter educativo do projeto.

### C. Interface do Usuário (UI/UX - A Vitrine do Projeto Chromatch)

Acreditamos que a beleza está na simplicidade e na funcionalidade.

*   **Design Intuitivo e Limpo:** Interface visualmente agradável, minimalista e fácil de navegar, demonstrando princípios de bom design de interface e experiência do usuário.
*   **Navegação Clara:** Seções bem definidas como "Analisar Minha Cor", "Minha Paleta", "Conceitos de Colorimetria".
*   **Registro da Análise:** Permite que o usuário salve sua análise e paleta para acesso rápido e comparações futuras.

## ⚙️ Tecnologias Envolvidas (Os Pilares Tecnológicos)

Este projeto foi construído sobre uma base robusta de tecnologias, demonstrando proficiência em diversas áreas da GTI:

*   **Back-end e Processamento de IA:** Utiliza a capacidade computacional e os recursos de IA do **`base44`** para:
    *   Desenvolver e refinar o algoritmo de processamento de imagem para detecção de tom de pele e características (subtom, profundidade, intensidade).
    *   Implementar e testar modelos de aprendizado de máquina para classificação de estações de colorimetria.
    *   Gerenciar o banco de dados de paletas de cores e regras de recomendação.
*   **Linguagem de Programação:** Python 🐍 (para o backend de IA e processamento).
*   **Bibliotecas de Processamento de Imagem:** OpenCV, Pillow.
*   **Bibliotecas de Análise de Dados e ML:** NumPy, scikit-learn.
*   **Visualização de Dados:** Matplotlib, Seaborn.
*   **APIs e Integrações (Potencial de Estudo):** A arquitetura do projeto foi pensada para permitir futuras integrações com APIs de visão computacional ou bibliotecas de cores externas, explorando a escalabilidade do sistema.

## 🧑‍💻 Experiência do Usuário (UX - A Pesquisa com o Usuário)

A experiência do usuário é central no desenvolvimento do Chromatch, com foco em:

*   **Simplicidade e Clareza:** O processo de análise é descomplicado, com feedback instantâneo e orientações passo a passo, facilitando os estudos de usabilidade.
*   **Personalização:** Cada recomendação é feita sob medida, reforçando a sensação de que o Chromatch "entende" o usuário.
*   **Educativo:** Além das recomendações, o aplicativo oferece pequenos "insights" sobre colorimetria, explicando os fundamentos teóricos por trás das escolhas de cores.

## 🎨 Elementos de Design (UI - A Estética do Estudo)

O design visual do Chromatch reflete a natureza do projeto:

*   **Estilo Visual:** Moderno, elegante, limpo e com foco nas cores. O design é funcional e não sobrecarrega as informações.
*   **Iconografia e Tipografia:** Uso de elementos visuais que transmitem profissionalismo e clareza, adequados para um projeto acadêmico de alto nível.

## 📦 Como Usar (Guia Rápido para Testadores e Avaliadores)

Este é um projeto protótipo. As instruções abaixo são para simular o ambiente de desenvolvimento.

### Pré-requisitos

Certifique-se de ter Python 3.x instalado.

### Instalação (Simulada para ambiente de desenvolvimento/teste)

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/Darllan/Chromatch.git
    ```
2.  **Navegue até o Diretório do Projeto:**
    ```bash
    cd Chromatch
    ```
3.  **Crie um Ambiente Virtual (Recomendado):**
    ```bash
    python -m venv venv
    ```
    *   Ative o ambiente virtual:
        *   No Windows: `.\venv\Scripts\activate`
        *   No macOS/Linux: `source venv/bin/activate`
4.  **Instale as Dependências:**
    ```bash
    pip install -r requirements.txt
    ```
    (Certifique-se de que o arquivo `requirements.txt` contenha todas as bibliotecas listadas na seção de Tecnologias).

### Execução (Exemplo de simulação do backend de análise)

Para simular o processamento de uma imagem pelo backend de IA (utilizando `base44` como motor):

```bash
python main_analyzer.py --image_path assets/sample_skin_tone.jpg --user_answers answers.json
