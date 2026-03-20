# Arte Sálmica em Portugues

Repositório de partituras de tradição bizantina para os serviços litúrgicos da Igreja Ortodoxa.
Os arquivos estão no formato `.byzx`, nativo do software **Neanes** — editor gratuito
e de código aberto para notação musical bizantina, disponível em:
👉 [github.com/neanes/neanes](https://github.com/neanes/neanes)

---

## Contribuindo

Contribuições são bem-vindas! Basta seguir as regras abaixo.

### Eu não sei usar Git/Github:
Se você não sabe como git e Github funcionam, você pode enviar sua contribuição por email. Basta enviar o arquivo para: ...@gmail.com

### Eu sei utilizar Git/Github:
Como cada adição costuma ser uma ou poucas partituras, não é necessário criar uma branch separada — um commit direto é suficiente.

1. Faça um **fork** do repositório.
2. Adicione seu(s) arquivo(s) na pasta correta, seguindo a convenção de nomes:
   - ✅ `PT-Hino dos querubins-tom1-karamanis.byzx`
   - ❌ `Hino dos Querubins v2 final portugues.byzx`
3. Abra um **Pull Request**.

---

## Tipos de arquivo
Neste repositório usamos exclusivamente arquivos `.byzx`, que permitem fazer gestionamento de versão.
Ao salvar no **Neanes**, altere o tipo de arquivo de `.byz` (padrão) para `.byzx`.

## Modelo padrão e tipografia
Para garantir a uniformidade tipográfica, há um modelo padrão de documento que deve ser utilizado para todas as partituras deste repositório, que encontra-se no arquivo [blank-model.byzx](#)

### Fonte padrão
Este modelo utiliza a fonte tipográfica **Coelacanth**, que deverá ser instalada para uma correta visualização:
- [Coelacanth](https://font.download/font/coelacanth)
- Para os "Neumas", utilizamos o **EZ Psaltica** que já vem pré-instalado no Neanes.

## Convenção de Nomes de Arquivo

O idioma (ou idiomas) é indicado por um **prefixo em maiúsculas** separado do nome por hífens:
- Idioma e nome são obrigatórios. 
- Tom é opcional, adicionar quando relevante (diferentes tons para o mesmo hino/conjunto)
- Autor é opcional. Como boa prática especificamos no caso de haver diversas partituras para o mesmo hino.
```
<IDIOMA>-<nome-da-peca>-<tom>-<autor>.byzx
```

### Exemplos

```
EL-Hino dos querubins-tom1-karamanis.byzx
EL-PT-Em ti se alegre ó cheia de graça-tom1.byzx
EL-EN-Trisagion-tom2-breve.byzx
EL-PT-EN-Christos anesti.byzx
```

### Tags de Idioma

| Tag   | Idioma                      |
|-------|-----------------------------|
| `EL`  | Grego                       |
| `PT`  | Português                   |
| `EN`  | Inglês                      |
| `AR`  | Árabe                       |
| `RO`  | Romeno                      |
| `RU`  | Russo                       |
| `CU`  | Eslavônico Eclesiástico     |
| `SR`  | Sérvio                      |
| `FR`  | Francês                     |

Quando a partitura contiver **mais de um idioma**, combine as tags: `EL-PT`, `EL-EN-PT`, etc.

---

## Convenção de Tom (Modo)

| Abreviação | Modo Eclesiástico        |
|------------|--------------------------|
| `tom1`     | 1º Tom                   |
| `tom2`     | 2º Tom                   |
| `tom3`     | 3º Tom                   |
| `tom4`     | 4º Tom                   |
| `tom5`     | Plagal do 1º (= 5º Tom)  |
| `tom6`     | Plagal do 2º (= 6º Tom)  |
| `tom7`     | Varys / Tom Grave (= 7º) |
| `tom8`     | Plagal do 4º (= 8º Tom)  |

---

## Licença

Salvo indicação contrária, as partituras deste repositório estão em **domínio público**
ou compartilhadas sob [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
Se contribuir com uma partitura sob licença diferente, declare-o no PR e adicione um
arquivo `LICENCA.txt` ao lado da partitura.

---

## Recursos Externos

- [Neanes](https://github.com/neanes/neanes) — software de notação bizantina (gratuito, código aberto)
