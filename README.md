# 🔢 AR Markers Project - Simple Math with Augmented Reality

Projeto de Realidade Aumentada para Operações de Soma

Este é um projeto de Realidade Aumentada (AR) feito para funcionar direto no navegador, usando A-Frame e AR.js. Ele reconhece marcadores personalizados pela câmera do computador ou do celular e realiza uma operação de soma de forma simples e intuitiva.

Descrição do Projeto

A ideia principal é permitir que o usuário aponte dois marcadores de números e, depois, um marcador de soma. Quando os três aparecem na ordem correta, o sistema mostra o resultado na tela.
Exemplo: mostrar o marcador de “1”, depois o de “2” e, por último, o marcador de “+”. O aplicativo então exibe “1 + 2 = 3”. Após alguns segundos, ele reinicia para permitir uma nova operação.

O objetivo foi criar uma experiência prática de AR, fácil de entender e de testar, funcionando tanto no computador quanto no celular.

Como Usar

Acesse o projeto pelo navegador:
https://CRlSTlANCASTRO.github.io/projeto-ar/

Permita o acesso à câmera quando o navegador pedir.

Utilize os marcadores impressos (números e o símbolo de soma).

Mostre os marcadores seguindo esta ordem:
primeiro um número, depois outro número, e por último o marcador de soma.

O resultado aparecerá na tela e o sistema reiniciará automaticamente.

O funcionamento é simples e não requer instalação.

Tecnologias Utilizadas

A-Frame 1.2.0 para criação da cena 3D.

AR.js 2.1.8 para detecção dos marcadores.

JavaScript para a lógica de reconhecimento e cálculo.

Canva para criação visual dos marcadores.

AR.js Marker Generator para gerar os padrões dos marcadores (.patt).

GitHub Pages para hospedagem do projeto.

Estrutura do Projeto

projeto-ar/
├── index.html – Arquivo principal do projeto
├── markers/ – Arquivos dos marcadores (.patt)
│ ├── pattern-marker-1.patt
│ ├── pattern-marker-2.patt
│ └── pattern-marker-plus.patt
└── assets/ – Pasta reservada para imagens e outros arquivos futuros

Recursos do Sistema

Detecção dos marcadores em tempo real.

Exibição do resultado somente quando a ordem correta é seguida.

Texto de apoio na tela para mostrar o estado atual.

Reinício automático após três segundos.

Compatível com dispositivos móveis.

Atualizações Futuras

Inclusão de novos números.

Outras operações matemáticas, como subtração, multiplicação e divisão.

Efeitos visuais ou sonoros.

Melhorias na interface.

Compatibilidade com Celular

O projeto foi testado em Android e iOS usando o navegador com acesso à câmera.

Autor

Criado por Cristian Castro
GitHub: https://github.com/CRlSTlANCASTRO

Licença

O projeto utiliza a licença MIT e pode ser usado e modificado livremente.
