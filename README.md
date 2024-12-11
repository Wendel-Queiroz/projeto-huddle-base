# Frontend Mentor - Solução de página de destino Huddle com seção introdutória única

Esta é uma solução para o [desafio de página de destino Huddle com seção introdutória única no Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

## Índice

- [Visão geral]
- [O desafio]
- [Captura de tela]
- [Links]
- [Meu processo]
- [Construído com]
- [Códigos]
- [Agradecimentos]


## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal para a página, dependendo do tamanho da tela do dispositivo
- Ver estados de foco para todos os elementos interativos na página

### Captura de tela

<img src=./src/design/imagem-desktop.png>

### Links

- URL da solução: [https://github.com/Wendel-Queiroz/projeto-huddle-base]
- URL do site ativo: [https://wendel-queiroz.github.io/projeto-huddle-base/]

## Meu processo

### Criado com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Grade CSS
- Fluxo de trabalho desktop-first
- Responsivo


### Códigos

Alguns trechos em destaque:

```html
  <main>
    <div><img src="./src/images/illustration-mockups.svg" alt="imagem ilustração"></div>
    <section>
      <h2>Build The Community Your Fans Will Love</h2>
      <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
      <button>Register</button>
    </section>
  </main>
```
```css
main section button{
    color: hsl(257, 40%, 49%);
    padding: 10px 50px;
    border-radius: 20px;
    border-style: none;
    margin-top: 30px;
    transition: 0.3s;
}

main section button:hover{
    color: white;
    background-color: hsl(300, 69%, 71%);
}
```

## Agradecimentos

Sempre grato ao curso Dev em Dobro!