# 📚 Classificação Bibliográfica do Coutinho (CBC)

## 🎯 Objetivo

Criar um sistema de classificação **impessoal, conciso e funcional** para organizar livros de ficção — especialmente romances — com base em critérios objetivos como gênero, origem autoral, formato narrativo e período de publicação.

Inspirado em Dewey, LCC e Cutter Numbers, mas adaptado ao uso pessoal do leitor.

---

## 🧱 Estrutura do Código CBC

**Formato geral:**
[GÊNERO].[AUTOR].[FORMATO].PERÍODO][.TRAD].[ID]


- `TRAD` → Opcional. Só será incluído **se o livro for traduzido de idioma diferente do inglês**
- `ID` → Identificador final: `[SOBRENOME][ANO][TT]`, para desambiguação e ordenação

---

## 1. 📘 Gênero Literário

| Código | Significado       |
|--------|--------------------|
| ROM    | Romance           |
| FAN    | Fantasia          |
| CF     | Ficção Científica |
| MST    | Mistério/Thriller |
| HOR    | Horror            |
| HIST   | Histórico         |

---

## 2. 🌍 Origem do Autor

| Código | Significado              |
|--------|---------------------------|
| BR     | Brasil                   |
| USA    | Estados Unidos           |
| UK     | Reino Unido              |
| JP     | Japão                    |
| LUSO   | Países Lusófonos         |
| AUS    | Austrália                |
| INT    | Internacional/multinacionais |

---

### Regra para identidades hifenizadas ou dualidade cultural
Quando o autor apresentar identidade hifenizada (ex.: Pakistani-American, Nigerian-British, Indo-Canadian) e essa dualidade for central na autodescrição biográfica e no posicionamento editorial:
Preferir o código INT, pois o sistema não prevê códigos compostos (ex.: USA-PAK) nem códigos específicos para todos os países de origem cultural.
Registrar obrigatoriamente, nas Notas Adicionais da ficha catalográfica, a dualidade cultural, a nacionalidade legal e o circuito de publicação.
Exemplo de nota:
> Origem autoral: INT (autora se identifica como Pakistani Muslim American; nascida e residente nos Estados Unidos; identidade cultural dual fortemente enfatizada pela própria autora e pelo mercado editorial). Nacionalidade legal e circuito de publicação: estadunidense.
Essa regra prioriza a fidelidade à identidade reivindicada pelo autor sem quebrar a estrutura concisa da CBC. Em casos em que a dualidade for meramente incidental, manter o código da nacionalidade legal ou do principal circuito de publicação (geralmente USA, UK etc.).

---

## 3. 🕰️ Período de Publicação

| Código | Intervalo                   |
|--------|------------------------------|
| PRE19  | Antes de 1800               |
| 19A    | Século XIX (1800–1899)      |
| 20A    | 1900–1949                   |
| 20B    | 1950–1999                   |
| 21A    | 2000–2024                   |
| 21B    | 2025 em diante              |

---

## 4. 🌐 Tradução (Opcional)

| Código  | Quando usar                                     |
|---------|-------------------------------------------------|
| *(omitido)* | Se o livro estiver no idioma original ou traduzido do inglês |
| `TR-XX` | Se traduzido de idioma **diferente do inglês** (ex: TR-FR, TR-JP) |

---

## 5. 🆔 Identificador Final

Formato: `[SOBRENOME][ANO][TT]`  
- `SOBRENOME`: Até 5 letras do sobrenome principal do autor
- `ANO`: Publicação original
- `TT`: Duas letras significativas do título (ignorando artigos)

---

## 🧪 Exemplos completos de CBC

| Título                          | Código CBC                             |
|---------------------------------|-----------------------------------------|
| Grande Sertão: Veredas          | `ROM.BR.20B.ROSA56GR`              |
| 1984 (George Orwell)            | `CF.UK.20A.ORWE49NI`                |
| O Nome do Vento                 | `FAN.USA.21A.ROTH07NO`              |
| O Jogo do Amor Ódio             | `ROM.AUS.21A.THOR16HA`              |
| O Perfume (Patrick Süskind)     | `HOR.DE.20B.SUSK85PE.TR-DE`         |
| Noruwei no Mori (Murakami)      | `ROM.JP.20B.MURAK87NO.TR-JP`        |

---

## 🛠️ Observações Finais

- O CBC pode ser usado em planilhas, etiquetas físicas, metadados de arquivos e catálogos pessoais
- É modular: você pode suprimir ou expandir segmentos conforme sua necessidade
- Pode ser complementado com marcadores extras como ISBN, número de páginas ou tags

---

Versão: 3.1  
Atualizado em: 29 de setembro de 2026  
Curador: Guilherme Coutinho
Alterações na versão 3.1: Inclusão da regra para identidades hifenizadas/dualidade cultural na seção de Origem do Autor.
