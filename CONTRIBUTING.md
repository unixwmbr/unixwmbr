<h1 align="center">Contribution</h1>

<p>
    Para adicionar uma amostra da sua config você pode fazer um pull request utilizando utilizando os templates abaixo. O processo é bem simples, basta apenas copiar e colar o template desejado no final da sessão <b>dotfiles | scripts | barras</b> no arquivo <a href="https://github.com/unixwmbr/unixwmbr/blob/master/README.md">README.md</a> e alterar os locais identificados com <b>{ instrução }</b> pelo valor correto.
</p>

<h4>Exemplo:</h4>

Para adicionar o link do repositório dotfiles, altere o exemplo abaixo:

```html
<a href="{Link referência para o seu dotfiles.}" />
```

Para:

```html
<a href="https://github.com/seu_usuario/seu_repositorio_de_dotfiles" />
```

<h3 align="center">Template de Dotfiles</h3>

```html
--------------

<div align="center">
  <a href="{Link referência para o seu dotfiles.}">
    <img
      alt="Dotfiles"
      src="https://img.shields.io/badge/config-{seu nome}-%232c3e50?style=for-the-badge"
    />
  </a>
  <a href="{Link referência para WM.}">
    <img
      alt="WM"
      src="https://img.shields.io/badge/wm-{nome da wm}-%235352ed?style=for-the-badge"
    />
  </a>
  <a href="{Link referência para o tema.}">
    <img
      alt="Tema"
      src="https://img.shields.io/badge/tema-{nome do tema}-%232ed573?style=for-the-badge"
    />
  </a>
  <br /><br />
  <img alt="Captura de tela / Gif" src="{Link para sua captura de tela / Gif}" />
  <br/><br/>
</div>
```

<h3 align="center">Template Scripts / Barras</h3>

```html
--------------

<div align="center">
  <a href="{Link referência para o seu script ou imagem da barra.}">
    <img
      alt="Script / Barra"
      src="https://img.shields.io/badge/nome-{nome do script ou barra}-%2322252f?style=for-the-badge"
    />
  </a>
  <br /><br />
  <p>
    {adicione um texto falando sobre o script, ao menos o que ele faz imagem ou
    gif de amostra, se houver}. Caso for barra não precisa incluir paragrafo.
  </p>
  <img alt="Captura de tela / Gif" src="{Link para captura de tela / Gif}" />
  <br/><br/>
</div>
```
