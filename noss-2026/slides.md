---
# try also 'default' to start simple
theme: unicorn
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Open source vs. IA
info: |
  Um panorama das políticas de engajamento atuais
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
# duration of the presentation
duration: 30min
---

# Open source vs. IA

Um panorama das políticas de engajamento atuais

---
layout: cover
---

# O que tem de errado com essa imagem?

<div class="flex justify-center">
  <img src="./images/slop.png" width="500px" />
</div>

---

# O que é Open Source?

<div class="flex justify-center">
  <img src="./images/sistema_sociotecnico.png" width="900px" />
</div>

---

# Contrato social

<div class="flex justify-center">
  <img src="./images/matplotlib.png" width="900px" />
</div>

---

# O que é uma contribuição?

<div class="flex justify-center">
  <img src="./images/puppy.png" width="900px" />
</div>

---
layout: image-right
image: ./images/qc.gif
---

# Velocidade

<div style="margin-top: 150px;">
<ul>
  <li>A IA é mais rápida do que conseguimos revisar</li>
  <li>O gargalo agora é revisão humana</li>
</ul>
</div>

---
layout: image-center
image: ./images/scott.png
---

# O caso da Matplotlib

---

# O que os projetos estão fazendo?

<!-- What are our communities thinking and discussing? Can we share common practices and requirements? -->

- Orientar mantenedores e contribuidores
- Acertar expectativas
- Templates para PR, declaração de autoria
- "Interaja com o projeto primeiro"
- Ban para quem desrespeitar as regras

<h2 class="text-center">
Regras/<i>policies</i>
</h2>

---

# Regras

<div class="flex justify-center">
  <img src="./images/myrepo.png" width="600px" />
</div>

---

# Regras

- 124 projetos
- Accepting, rejecting, restricting: most require a human in the loop
- You are accountable for all changes you submit, regardless of the tools you use.
- Concerns are more about quality than origin
- Qualifying restrictions (i.e. no “substantial” LLM contributions, no LLM for communications)
- No clear path on attribution (Co-authored-by, Assisted-by, Generated-by)
- The Developer Certificate of Origin (DCO) is emerging as the primary legal mechanism. 
- Others are doing similar work (CHAOSS Wg and RedMonk article) - paste in chat: https://redmonk.com/kholterhoff/2026/02/26/generative-ai-policy-landscape-in-open-source/
- RedMonk article: 86 organizations surveyed
    - Permissive (48)
    - Ban (any type) (20)
    - Undecided (13)
    - No Policy / Advocacy (5)

---

# Produtividade

"We are paying you to solve the hard problems that we cannot just give to an LLM"

---

# Como educar os contribuidores que nem leem documentação?

- Qual é o objetivo de _good first issues_?
- Se resolver com a IA fosse o objetivo, os mantenedores poderiam estar fazendo isso sozinhos.
- Sustentabilidade: onboarding ainda é necessário.

---

# Good Egg

<div class="flex justify-center">
  <img src="./images/good_egg.png" width="800px" />
</div>

---

# Vouch

<div class="flex justify-center">
  <img src="./images/vouch.png" width="600px" />
</div>

---

# Pra onde estamos indo?

<!-- O que podemos esperar do futuro? Do GitHub? De outras ferramentas e plataformas? -->

<div class="flex justify-center">
  <img src="./images/fengetal.png" width="900px" />
</div>

https://arxiv.org/html/2508.04921v2

---
layout: center
class: text-center
---

# Obrigada!

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
