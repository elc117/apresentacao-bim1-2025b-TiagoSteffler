# **Compilador x Interpretador**

### O que são?

O **compilador**, de forma sucinta, converte um código em linguagem textual (linguagem de alto nível, "legível" para nós) em linguagem de máquina (linguagem de baixo nível, específica para computadores/SO). Ao realizar essa tradução, ele transforma em um código assembly para então passar ao assembler para transformar em linguagem de máquina propriamente dita.
- Pode ser um pouco lento e ocupar maior quantidade de memória, pois ele traduz o código fonte inteiramente;
- O código compilado roda mais rápido que um código interpretado;
- Somente verifica erros de semântica e de sintaxe.

<br>

O **interpretador** realiza algo similar: ele realiza a mesma tradução de um código em linguagem de alto nível para um código de máquina (baixo nível) - no entanto, ele realiza isso em tempo de execução, ou seja, linha por linha ao executá-lo.
- Fácil depuração e gestão de memória automática;
- Mais flexível que uma linguagem compilada;
- Código interpretado roda mais lentamente que o código compilado.

<br>

Enquanto que um compilador salva o código compilado em um código objeto para direta execução e utilização futura, o interpretador não salva nenhum código de máquina - dessa forma, é necessário o código fonte para futura execução.  
<br>

**Linguagens Compiladas:**
- **C e C++** - os compiladores mais utilizados para essas linguagens são o GCC e Clang;
- **COBOL** - o GnuCOBOL é o mais utilizado e é open-source;

**Linguagens Interpretadas:**
- **Python** - PyPy é um interpretador famoso, enquanto CPython atua como interpretador e compilador (primeiro compila, depois interpreta);
- **Ruby** - CRuby/Ruby MRI é o mais utilizado, mas existem alternativas como JRuby, YARV e mRuby.  
<br>
> Existem exceções como Java, por exemplo, que são tanto compiladas e interpretadas de acordo com seu jeito único de modelo de execução (máquina virtual ou VM).

<br>

### Interação com Haskell:
Exemplo de um código com a linguagem Haskell
![Alt Text](AtividadeHaskell.gif)