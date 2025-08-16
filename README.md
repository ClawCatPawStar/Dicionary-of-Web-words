
while True:
    
    meme_dict = {
            "CRINGE": "Algo excepcionalmente raro o embarazoso",
            "LOL": "Una respuesta común a algo gracioso",
            "ROFL": "una respuesta a una broma",
            "SHEESH": "ligera desaprobación",
            "CREEPY": "aterrador, siniestro",
            "AGGRO": "ponerse agresivo/enojado",
            "XD": "Risa sarcastica",
            "GG": "Buen juego",
            "LAG": "Bajo internet que se traba",
            "TROLL": "Broma pesada que engaña a una persona a hacer algo y sucede lo contrario",
            "AFK": "No esta directamente en linea, inactivo"
            }
    
    print(meme_dict.keys())
    word = input("Escribe una palabra que no entiendas: ").upper()

    if word in meme_dict.keys():
        
        print ("Significado:",meme_dict[word])
        
    else:
        print("esta palabra no se encuentra en el diccionario")
