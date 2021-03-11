# Awesome View
## Simples, rápido, fácil de instalar. Um plugin que facilita a visualização de imagens em seu website.

### Como utilizar?
Basta utilizar os atributos do plugin como nos exemplos abaixo

Simples:
```
<img data-aws-view src alt>
```

Com imagem de tamanho diferente na exibição do html:
```
<img data-aws-view data-aws-view-source={imagem de tamanho original} src={imagem pequena} alt>
```

Imagens em um grupo específico
```
<img data-aws-view data-aws-view-group={categoria "paisagem"} src={imagem de paisagem} alt>
<img data-aws-view data-aws-view-group={categoria "paisagem"} src={imagem de paisagem} alt>

<img data-aws-view data-aws-view-group={categoria "animal"} src={imagem de animal} alt>
<img data-aws-view data-aws-view-group={categoria "animal"} src={imagem de animal} alt>
```

### A ideia é futuramente lançar

- Mais skins próprias para o projeto, agilizando o processo do front-end;
- Uma melhora no aspect-ratio das imagens e a utilização de ```<canvas>``` no lugar de ```<img>```;
- Otimização no código Javascript em geral
