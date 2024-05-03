dicionário = {
    "hello": "olá",
    "goodbye": "adeus",
    "cat": "gato",
    "dog": "cachorro",
    "house": "casa",
    "tree": "árvore",
    "book": "livro",
    "computer": "computador",
    "friend": "amigo",
    "family": "família",
    "car": "carro",
    "bike": "bicicleta",
    "sun": "sol",
    "moon": "lua",
    "water": "água",
    "food": "comida",
    "love": "amor",
    "happiness": "felicidade",
    "sadness": "tristeza",
    "work": "trabalho"
}

for palavra in sorted(dicionario.keys()):
    print(f"{palavra}: {dicionario[palavra]}")
