### gabrielpedroti

```python
class Pedroti(Developer):

    def __init__(self):
        self.name     = 'Gabriel Pedroti'
        self.role     = 'Software Developer'
        self.company  = 'Baja & Aguiar'
        self.focus    = ['automação', 'IA aplicada', 'sistemas internos']
        self.locality = 'Curitiba - PR - Brazil'
        self.degree   = 'Análise e Desenvolvimento de Sistemas — PUC-PR'
        self.linkedin = 'linkedin.com/in/gabrielpedroti'

    def workflow(self):
        return 'entende o processo/problema → escreve a solução → testa/valida → deixa rodando'


class Skills(Pedroti):
    languages = ['Python', 'JavaScript', 'HTML', 'CSS', 'Java']
    frontend  = ['React']
    ai        = ['LLMs aplicadas a automação de entregas']
    learning  = ['full stack']
```
