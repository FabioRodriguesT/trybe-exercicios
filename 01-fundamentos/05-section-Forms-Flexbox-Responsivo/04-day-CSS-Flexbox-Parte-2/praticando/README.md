# PARTE I - Flex Items

#### Para fixar
É momento de testar os conhecimentos apresentados até aqui.

1. Teste as possibilidades para a propriedade align-self considerando todos os valores que ela suporta. Para isso, utilize os códigos abaixo:

```HTML
<!DOCTYPE html>
<html lang="pt">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS FLEXBOX - ALIGN SELF</title>
    <style>
      .container {
        border: 1px solid black;
        display: flex;
        height: 300px;
        margin: auto;
        width: 500px;
      }

      .keep {
        align-self: center;
        background-color: #FAA488;
        display: flex;
        justify-content: center;
        width: 150px;
        list-style: none;
      }

      .change {
        /* Altere a propriedade align-self. */
        align-self: center;
        background-color: #FBD26A;
        display: flex;
        justify-content: center;
        width: 200px;
        list-style: none;
      }

    </style>
  </head>
  <body>
    <ul class="container">
      <li class="keep">REFERÊNCIA</li>
      <li class="change">ELEMENTO TESTE</li>
      <li class="keep">REFERÊNCIA</li>
    </ul>
  </body>
</html>
```

2. Teste as possibilidades para a propriedade order considerando todos os valores que ela suporta. Para isso, utilize os códigos abaixo:

```HTML
<!DOCTYPE html>
<html lang="pt">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS FLEXBOX - ORDER</title>
    <style>
      .container {
        border: 1px solid black;
        display: flex;
        height: 50px;
        margin: auto;
        width: 500px;
      }

      .box {
        align-items: center;
        display: flex;
        justify-content: center;
        width: 125px;
      }

      .one {
        background-color: #FBD26A;
        display: flex;
        /* Altere a propriedade order. */
        order: 1;
        list-style: none;
      }

      .two {
        background-color: #FAA488;
        display: flex;
        /* Altere a propriedade order. */
        order: 2;
        list-style: none;
      }

      .three {
        background-color: #9069EF;
        display: flex;
        /* Altere a propriedade order. */
        order: 3;
        list-style: none;
      }

      .four {
        background-color: #006472;
        display: flex;
        /* Altere a propriedade order. */
        order: 4;
        list-style: none;
      }

    </style>
  </head>
  <body>
    <ul class="container">
      <li class="box one">1</li>
      <li class="box two">2</li>
      <li class="box three">3</li>
      <li class="box four">4</li>
    </ul>
  </body>
</html>
```

# PARTE 2 - Propriedades: flex-grow, flex-shrink, flex-basis

#### Para fixar
É momento de testar os conhecimentos apresentados até aqui.

Utilize o código abaixo para realizar os exercícios:

```HTML 
<!DOCTYPE html>
<html lang="pt">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS FLEXBOX - FLEX-GROW</title>
    <style>
      .container {
        display: flex;
        height: 50px;
        margin: auto;
        width: 100%;
      }

      .box {
        align-items: center;
        display: flex;
        justify-content: center;
      }

      .one {
        background-color: #FBD26A;
        display: flex;
        /* Altere a propriedade grow. */
        flex-grow: 1;
        list-style: none;
      }

      .two {
        background-color: #FAA488;
        display: flex;
        /* Altere a propriedade grow. */
        flex-grow: 1;
        list-style: none;
      }

      .three {
        background-color: #9069EF;
        display: flex;
        /* Altere a propriedade grow. */
        flex-grow: 1;
        list-style: none;
      }

      .four {
        background-color: #006472;
        display: flex;
        /* Altere a propriedade grow. */
        flex-grow: 1;
        list-style: none;
      }

    </style>
  </head>
  <body>
    <ul class="container">
      <li class="box one">1</li>
      <li class="box two">2</li>
      <li class="box three">3</li>
      <li class="box four">4</li>
    </ul>
  </body>
</html>
```

1. Teste as possibilidades para a propriedade flex-grow.

2. Teste as possibilidades para a propriedade flex-shrink. Para isso, altere as propriedades css do exercício anterior para que fique como está representado a seguir.

```HTML 
<!-- -->
    <style>
      .container {
        display: flex;
        height: 50px;
        margin: auto;
        width: 100%;
      }

      .box {
        align-items: center;
        display: flex;
        justify-content: center;
        flex-basis: 500px;
        flex-grow: 0;
        flex-shrink: 1;
      }

      .one {
        background-color: #FBD26A;
        display: flex;
        /* Altere a propriedade shrink. */
        flex-shrink: 1;
        list-style: none;
      }

      .two {
        background-color: #FAA488;
        display: flex;
        /* Altere a propriedade shrink. */
        flex-shrink: 1;
        list-style: none;
      }

      .three {
        background-color: #9069EF;
        display: flex;
        /* Altere a propriedade shrink. */
        flex-shrink: 1;
        list-style: none;
      }

      .four {
        background-color: #006472;
        display: flex;
        /* Altere a propriedade shrink. */
        flex-shrink: 1;
        list-style: none;
      }
    </style>
<!-- ... -->
```

3. Teste as possibilidades para a propriedade flex-basis. Para isso, altere as propriedades css do exercício anterior para que fique como está representado a seguir.

```HTML
<!-- ... -->
    <style>
      .container {
        display: flex;
        height: 50px;
        margin: auto;
        width: 100%;
      }

      .box {
        align-items: center;
        display: flex;
        justify-content: center;
        /* Altere a propriedade flex-basis */
        flex-basis: 500px;
        flex-grow: 0;
        flex-shrink: 1;
      }

      .one {
        background-color: #FBD26A;
        list-style: none;
      }

      .two {
        background-color: #FAA488;
        list-style: none;
      }

      .three {
        background-color: #9069EF;
        list-style: none;
      }

      .four {
        background-color: #006472;
        list-style: none;
      }
    <!-- </style> -->
  <!-- ... -->
  ```

