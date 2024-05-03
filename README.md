# Dicionário de palavras e significados de inglês para português
dicionario = {
    "Time": "Tempo",
    "Goodbye": "Adeus",
    "People": "Pessoas",
    "Book": "Livro",
    "Words": "Palavras",
    "Years": "Anos",
    "Place": "Lugar",
    "Tree": "Árvore",
    "Numbers": "Números",
    "Chair": "Cadeira",
    "Name": "Nome",
    "Computer": "Computador",
    "Line": "Linha",
    "Water": "Água",
    "Food": "Comida",
    "Moon": "Lua",
    "Eyes": "Olhos",
    "Sky": "Céu",
    "Side": "Lado",
    "Love": "Amor"
}

# Imprimindo as palavras e suas traduções em ordem
for palavra, significado in sorted(dicionario.items()):
    print(f"{palavra} - {significado}")
