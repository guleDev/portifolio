#1. Introdução
Este relatório descreve a estrutura, tecnologias e decisões de design aplicadas no desenvolvimento do meu portfólio pessoal. O objetivo foi criar um site moderno, responsivo e acessível, demonstrando minhas habilidades em HTML, CSS e design front-end.
#2. Estrutura HTML
#2.1. Semântica e Organização
O HTML foi estruturado seguindo as melhores práticas de acessibilidade e SEO:
<!DOCTYPE html> para garantir a renderização no modo padrão.
<html lang="pt-BR"> definindo o idioma principal.
Metadados otimizados, incluindo:
<meta charset="UTF-8"> para suporte a caracteres especiais.
<meta name="viewport"> para responsividade em dispositivos móveis.
<link rel="icon"> com um favicon personalizado.
#2.2. Conteúdo Principal
<main id="portifolio"> → Contém toda a apresentação.
Seção de apresentação (#presentation) com:
<h1> para o nome (elemento mais importante/destaque da página).
<h2> com efeito de digitação animado (simulando uma máquina de escrever).
Seção "Sobre Mim" (#about-txt) → Texto descritivo em parágrafos (<p>).
Imagem de perfil (#about-img) → Otimizada com loading="lazy".
Botões de contato (#contact) → Links para GitHub e LinkedIn.
<footer> → Direitos autorais.

#3. Estilização CSS
#3.1. Design System e Variáveis
Para garantir consistência visual, utilizei CSS Custom Properties (variáveis) para:
Cores:
Tons de verde (--green-primary, --green-bright) como cor primária.
Escala de cinza (--bg-dark, --light-gray) para contraste e fundo.
Espaçamentos:
--espaco-pequeno, --espaco-medio, etc., garantindo proporção em diferentes dispositivos.
#3.2. Tipografia
Fontes do Google Fonts:
Inter → Legibilidade em textos longos.
Special Gothic Expanded One → Estilo único para títulos.
Tamanhos responsivos com clamp():
#3.3. Layout Flexível
Flexbox para alinhamento centralizado.
Media Queries para diferentes tamanhos de tela:
Mobile (default): Conteúdo em coluna.
Tablet (481px+): Botões lado a lado.
Desktop (769px+): Texto e imagem em linha.
#3.4. Efeitos Visuais
Animação de digitação (keyframes typing).
Transições suaves em botões (hover e active).
Borda circular na foto (border-radius: 50%).
Sombras para profundidade (box-shadow).
#4. Conclusão
Este projeto reflete meu conhecimento em:
HTML semântico (acessibilidade e SEO).
CSS moderno (Flexbox, variáveis, responsividade).
Design limpo (cores, tipografia, espaçamento).
Otimização (imagens lazy loading, animações performáticas).

