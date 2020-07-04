'''
Projeto em Python para a criação de um full route, contendo todos os IPs de 1.x.x.x até 255.x.x.x.x, onde é gravado em um arquivo .txt
Qualquer dúvida e ou melhoria que acharem viável, meus contatos: (21) 96476-5184 / felipe_lira@live.com
'''

text_file = open("full_route.txt", "w")

primeiro_octeto = 1
segundo_octeto = 0

while primeiro_octeto <= 255:
    primeiro = str(primeiro_octeto)
    segundo_octeto = 0
    
    while segundo_octeto <= 255:
        segundo = str(segundo_octeto)
        terceiro_octeto = 0
    
        while terceiro_octeto <= 255:
            terceiro = str(terceiro_octeto)
            ultimo_octeto = 0
        
            while ultimo_octeto <= 254:
                ultimo = str(ultimo_octeto)
                text_file.write("ip route "+primeiro+"."+segundo+"."+terceiro+"."+ultimo+" 255.255.255.255 Null0\n")
                ultimo_octeto += 1
            terceiro_octeto += 1
        segundo_octeto += 1
        
    primeiro_octeto += 1


text_file.close()
