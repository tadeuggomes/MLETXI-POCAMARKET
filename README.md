# 🛒 POCAMARKET | Calculadora de Conversão e Vendas

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tech-HTML5%20|%20CSS3%20|%20JavaScript-blue)

## 📌 Sobre o Projeto
O **POCAMARKET** é uma aplicação web (Single Page Application) desenvolvida para otimizar e automatizar o funil de vendas de photocards de K-Pop de uma cliente. A ferramenta atua como uma interface de conversão: ela educa o cliente através de regras de compra e, em seguida, oferece uma calculadora automatizada que converte valores em dólar para real, já embutindo taxas operacionais e de comissão.

🔗 **[Acessar a Aplicação Online](https://tadeuggomes.github.io/calculadora/)**

---

## 🎯 O Problema e a Solução Estratégica

**A Dor da Cliente (Gargalo Operacional):**
A cliente atua na importação e venda de produtos internacionais e lidava com um gargalo exaustivo no seu atendimento: precisava gastar horas do seu dia respondendo a dezenas de mensagens repetitivas apenas para fazer orçamentos manuais. Os compradores tinham dúvidas sobre a conversão do dólar e as taxas embutidas (da plataforma e da intermediária), o que gerava atrito, atrasava o atendimento e "esfriava" o desejo de compra. Além disso, muitos iniciavam o contato sem ler as regras vitais do negócio.

**A Minha Solução (Automação do Funil):**
Criei muito mais que uma calculadora; desenvolvi uma **máquina de pré-vendas automatizada**. 
A arquitetura do site inverteu o funil de atendimento: 
1. **Educação Forçada:** O comprador é guiado primeiro por uma tela limpa de regras que deve ser lida antes do orçamento, alinhando as expectativas e evitando dores de cabeça futuras.
2. **Autonomia e Transparência:** Na tela seguinte, o próprio usuário insere o valor. O JavaScript faz o cálculo instantâneo do câmbio + taxas, mostrando o valor final e transparente.
3. **Conversão Direta:** No exato momento em que o valor é revelado (pico de interesse), um Call to Action pulsante direciona o usuário para o WhatsApp. 

**O Impacto:** O cliente agora chega no WhatsApp da vendedora já educado, com o valor calculado e pronto para fechar o PIX, eliminando o trabalho braçal da cliente e aumentando drasticamente a velocidade de conversão.

---

## 🚀 Principais Funcionalidades e UI/UX

* **Design Focado em Conversão:** Estrutura dividida em duas etapas (Educação -> Ação). O botão final pulsa (CSS Animation) atraindo o clique no momento ideal.
* **Estética Premium (Glassmorphism):** Interface construída com o efeito de "vidro fosco", utilizando desfoque de fundo e bordas suaves, alinhada com a paleta de cores *Rose Quartz* e *Serenity* para gerar identificação visual imediata com o público-alvo (fandom de K-Pop).
* **Responsividade Mobile-First:** Totalmente adaptado para dispositivos móveis, com tipografia e espaçamentos dinâmicos que garantem legibilidade e evitam quebras de layout na palma da mão.
* **Cálculo Dinâmico:** Lógica em JavaScript nativo para conversão imediata, com tratamento de erros integrado (animação de 'shake' e foco no input caso o usuário insira dados inválidos).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e divisão de telas (Telas de Regras e Calculadora).
* **CSS3:** Estilização avançada com Flexbox, animações de keyframes, gradientes animados e design responsivo (`@media queries`).
* **Vanilla JavaScript:** Manipulação do DOM para transição suave entre telas e cálculo financeiro em tempo real.

---

## 👨‍💻 Sobre o Desenvolvedor

Desenvolvido por **Jorge Tadeu**, estudante do 4º período de Sistemas de Informação na CESAR School. 

Este projeto reflete minha visão de unir desenvolvimento de software com estratégia de negócios e e-commerce. Meu foco é construir soluções tecnológicas que não apenas apresentem um código limpo, mas que entreguem estética impecável, excelente experiência do usuário e resultados reais de conversão para o cliente final.

* **GitHub:** [https://github.com/tadeuggomes](https://github.com/tadeuggomes)
* **LinkedIn:** [Jorge Tadeu Filho](https://www.linkedin.com/in/jorge-tadeu-filho/)
