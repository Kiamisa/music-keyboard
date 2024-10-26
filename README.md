## README para Piano Online

# Piano Online

Este projeto é um piano virtual que permite aos usuários tocar notas individuais usando o teclado ou o mouse. A interface é estilizada para proporcionar uma experiência de uso simples e intuitiva.

## Estrutura do Projeto

O projeto está dividido em três partes principais:

1. **HTML (`index.html`)**: Estrutura o layout principal do piano, com teclas organizadas em uma escala, controle de volume e opção de mostrar/ocultar as letras das teclas.

2. **CSS (`main.css` e `reset.css`)**: Define o estilo visual do piano, incluindo as cores das teclas, efeitos de som, e controle de layout.

3. **JavaScript (`main.js`)**: Adiciona a funcionalidade principal do piano, incluindo reprodução de som, controle de volume e alternância de exibição das teclas.

## Funcionalidades

- **Toque de Notas**: Cada tecla do piano pode ser tocada ao clicar com o mouse ou pressionar a tecla correspondente no teclado.
- **Controle de Volume**: O volume do piano pode ser ajustado deslizando o controle de volume.
- **Exibição das Letras**: Possibilidade de alternar a exibição das letras que indicam quais teclas do teclado acionam cada nota.

## Instalação e Uso

1. Clone este repositório em sua máquina local.
2. Navegue até o diretório do projeto e abra o arquivo `index.html` em um navegador.
3. Utilize as teclas de seu teclado ou clique com o mouse para tocar as notas.
4. Ajuste o volume utilizando o controle deslizante e marque/desmarque a caixa de seleção para alternar a exibição das letras nas teclas.

## Estrutura de Arquivos

```
Piano Online
├── src/
│   ├── js/
│   │   └── main.js         # Código JavaScript para funcionalidades do piano
│   ├── styles/
│   │   ├── main.css        # Estilos principais do piano
│   │   └── reset.css       # Reset de estilos padrão do navegador
│   └── tunes/              # Pasta contendo os arquivos de áudio para cada tecla
├── index.html              # Estrutura HTML do piano
└── README.md               # Documentação do projeto
```

## Tecnologias Utilizadas

- **HTML5**: Estrutura da interface do piano.
- **CSS3**: Estilos e layout.
- **JavaScript**: Interatividade e controle do áudio.
