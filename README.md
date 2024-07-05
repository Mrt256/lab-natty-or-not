# Geração de imagens realisticas com IA

## 📒 Descrição
Projeto do Curso Fundamentos de IA para devs do DIO, consiste em gerar algo com IA que se assemelhe com a realidade.

## 🤖 Tecnologias Utilizadas
ConfyUI: https://github.com/comfyanonymous/ComfyUI.git
Realistic Vision V6.0 B1: https://civitai.com/models/4201/realistic-vision-v60-b1

## 🧐 Processo de Criação
Após a instação e configuração foram setados os seguintes prompts e cfgs:
Imagem 1
Positivo: (instagram photo, picture of a woman wearing a black dress, long black hair smiling, medium closeup shot, white room background, melmac)
Negativo: {(deformed iris, deformed pupils, semi-realistic, cgi, 3d, render, sketch, cartoon, drawing, anime, mutated hands and fingers:1.4), (deformed, distorted, disfigured:1.3), poorly drawn, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, disconnected limbs, mutation, mutated, ugly, disgusting, amputation, cartoon, (duplicated body parts), (extra limgs), (deformed iris, deformed pupils, semi-realistic, cgi, 3d, render, sketch, cartoon, drawing, anime, mutated hands and fingers:1.4), (deformed, distorted, disfigured:1.3), poorly drawn, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, disconnected limbs, mutation, mutated, ugly, disgusting, amputation, cartoon, (duplicated body parts), (extra limgs)}
steps: 20
cfg: 7.0
sampler:euler
denoise: 1.0

Imagem 2:
Positivo: (instagram photo, picture of a woman wearing a black dress, long black hair smiling, medium closeup shot, big city background, sunny day, summer)
Negativo: {(deformed iris, deformed pupils, semi-realistic, cgi, 3d, render, sketch, cartoon, drawing, anime, mutated hands and fingers:1.4), (deformed, distorted, disfigured:1.3), poorly drawn, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, disconnected limbs, mutation, mutated, ugly, disgusting, amputation, cartoon, (duplicated body parts), (extra limgs), (deformed iris, deformed pupils, semi-realistic, cgi, 3d, render, sketch, cartoon, drawing, anime, mutated hands and fingers:1.4), (deformed, distorted, disfigured:1.3), poorly drawn, bad anatomy, wrong anatomy, extra limb, missing limb, floating limbs, disconnected limbs, mutation, mutated, ugly, disgusting, amputation, cartoon, (duplicated body parts), (extra limgs)}
steps: 20
cfg: 7.5
sampler:euler
denoise: 1.0

## 🚀 Resultados
Os resultados foram imagens de mulheres realistas geradas inteiramente com IA
