# Criptografia e Segurança de Sistemas Computacionais

## Autenticador de Documentos

### SHA-256 File Hasher

Ferramenta de linha de comando para gerar e verificar hashes SHA-256 de qualquer arquivo.

#### Requisitos
- Python 3.8+
- Nenhuma dependência externa

#### Instalação
Clone ou baixe o arquivo **autenticador.py** e execute direto pelo terminal - sem instalação adicional.

---

#### Uso

#### Gerar o hash de um arquivo

> bash
> -
> python autenticador.py generate <caminho_do_arquivo>

---

#### Verificar a autenticidade de um arquivo

> bash
> -
> python autenticador.py verify <caminho_do_arquivo> <hash_esperado>

---

#### Aliases

Os subcomandos aceitam versões curtas:

|  Completo  |  Curto  |
|:----------:|:-------:|
| `generate` | `gen`   |
| `verify`   | `ver`   |

> bash
> -
> python autenticador.py gen <caminho_do_arquivo>  
> python autenticador.py ver <caminho_do_arquivo> <hash_esperado>

#### Formatos suportados

Qualquer formato de arquivo: **.txt**, **.pdf**, **.png**, **.zip**, **.exe**, etc.