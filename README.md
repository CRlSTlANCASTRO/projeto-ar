AR Markers Project - Simple Math with Augmented Reality
Projeto de Realidade Aumentada para Operações de Soma

Este é um projeto de Realidade Aumentada (AR) feito para funcionar direto no navegador, usando A-Frame e AR.js. Ele reconhece marcadores personalizados pela câmera do computador ou do celular e realiza uma operação de soma de forma simples e intuitiva.

**Descrição do Projeto**

A ideia principal é permitir que o usuário aponte dois marcadores de números e, depois, um marcador de soma. Quando os três aparecem na ordem correta, o sistema mostra o resultado na tela.

Exemplo:
Mostrar o marcador de “1”, depois o de “2” e, por último, o marcador de “+”. O aplicativo então exibe “1 + 2 = 3”. Após alguns segundos, ele reinicia para permitir uma nova operação.

O objetivo foi criar uma experiência prática de AR, fácil de entender e de testar, funcionando tanto no computador quanto no celular.

--Como Usar**

1 - Acesse o projeto pelo navegador:
https://CRlSTlANCASTRO.github.io/projeto-ar/

2 - Permita o acesso à câmera quando o navegador pedir.

3 - Utilize os marcadores impressos (números e o símbolo de soma).

4 - Mostre os marcadores seguindo esta ordem:

primeiro um número,

depois outro número,

e por último o marcador de soma.

O resultado aparecerá na tela e o sistema reiniciará automaticamente.

**Tecnologias Utilizadas**

> A-Frame 1.2.0 — criação da cena 3D

> AR.js 2.1.8 — detecção dos marcadores

> JavaScript — lógica de reconhecimento e cálculo

> Canva — criação visual dos marcadores

> AR.js Marker Generator — geração dos padrões (.patt)

> GitHub Pages — hospedagem do projeto

projeto-ar/
├── index.html – Arquivo principal do projeto
├── markers/ – Arquivos dos marcadores (.patt)
│   ├── pattern-marker-1.patt
│   ├── pattern-marker-2.patt
│   └── pattern-marker-plus.patt
└── assets/ – Pasta reservada para imagens e outros arquivos futuros

Autor
Criado por Cristian Castro
GitHub: https://github.com/CRlSTlANCASTRO

Licença
Este projeto utiliza a licença MIT e pode ser usado e modificado livremente.
