# Conversor de algarismos romanos v.1.0.0

**Esta biblioteca se destina à conversão de algarismos romanos em arábicos e vice-versa.**

Ao inserir o número de um cartão, esta versão informa de acordo com o algorítmo de Luhn se o cartão inserido é válido ou inválido.
Ao inserir um algarismo romano, esta versão informa o equivalente ao inserido em números decimais e vice-versa.


## Os métodos utilizados na biblioteca são:

#### **romanToInt(str) e intToRoman(num);**

Exemplo de uso:

```
$node
> let convert = require('convert-romans')
> convert.romanToInt('X'); // 10
> convert.intToRoman(10); // 'X'
```


## Versão 1.0.0
- Funcionalidades: Converte algarismos romanos e arábicos de 1 até 3999.


## Instalação

- Você deverá ter o node + npm instalados. Para guia de instalação, visite [o site oficial](https://www.npmjs.com/get-npm).
- proceda com a instalação com `$npm install convert-romans`


## Roadmap oficial do projeto

#### Versão 3.0.0 (sem previsão, aceita-se contribuições)
- README translated to english;

#### Versão 2.0.0 (previsão dezembro/2018)
- Implementação de conversão de algarismos a partir de 4000.

#### Versão 1.0.0 (released)
- Funcionalidades: Converte algarismos romanos e arábicos de 1 até 3999.
