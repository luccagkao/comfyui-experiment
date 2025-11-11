# Projeto Generative - Redes Neurais

Este trabalho tem como objetivo explorar o funcionamento e as aplicações da Inteligência Artificial Generativa, com foco em modelos de conversão entre texto e imagem. A proposta consiste em construir e analisar pipelines de Text-to-Image e Image-to-Text utilizando a ferramenta [Comfy UI](https://www.comfy.org/), uma interface modular e visual que permite a criação de fluxos complexos de inferência em modelos de difusão.

A [primeira parte](https://luccagkao.github.io/comfyui-experiment/implementacao/text2image/) do projeto investiga o processo de Text-to-Image, em que um modelo de difusão é guiado por descrições textuais para gerar imagens sintéticas de alta fidelidade e coerência semântica. Foram configurados nós de CLIP Text Encoder, Noise Sampler e Diffusion Model dentro do ComfyUI, permitindo compreender como a interpretação textual influencia as etapas de ruído, refinamento e renderização da imagem final. Essa fase enfatiza o papel da engenharia de prompts e dos parâmetros de inferência na qualidade e estilo das imagens geradas.

Na [segunda parte](https://luccagkao.github.io/comfyui-experiment/implementacao/image2text/), o pipeline Image-to-Text inverte o processo: a partir de uma imagem de entrada, o sistema utiliza modelos de captioning e CLIP Vision Encoder para produzir descrições automáticas em linguagem natural, simulando uma forma de “compreensão” visual por parte da IA. Essa abordagem demonstra a integração entre modelos de visão e linguagem, evidenciando como representações latentes podem ser traduzidas entre domínios multimodais.

O uso do ComfyUI permitiu a experimentação prática e visual desses fluxos, favorecendo o entendimento da estrutura interna dos modelos generativos e suas relações entre embeddings textuais, vetores latentes e processos de difusão. O projeto, portanto, não apenas demonstra a capacidade criativa das IAs generativas, mas também aprofunda a compreensão de seus fundamentos técnicos, reforçando a importância da modularidade, da parametrização e da interpretação crítica dos resultados obtidos.

## Grupo

1. Esdras Gomes Carvalho
2. Lincoln Rodrigo Pereira de Melo
3. Lucca d'Oliveira Gheti Kao