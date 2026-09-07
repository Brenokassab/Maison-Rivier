# Fotos das peças

Coloque as fotos dos produtos **nesta pasta**. O site troca a ilustração pela
foto automaticamente assim que o arquivo existir — não precisa mexer no código.

## Nome dos arquivos

Formato: `id-da-peca-cor.jpg`

Uma foto por cor (recomendado para o catálogo ficar igual ao brand board):

```
polo-heritage-azul-marinho.jpg
polo-heritage-branco.jpg
polo-heritage-bege-areia.jpg
polo-heritage-verde-oliva.jpg
polo-heritage-cinza-mescla.jpg
polo-heritage-preto.jpg

tee-essential-branco.jpg
tee-essential-azul-marinho.jpg
tee-essential-verde-oliva.jpg
tee-essential-bege-areia.jpg
tee-essential-cinza-claro.jpg
tee-essential-cinza-escuro.jpg
tee-essential-preto.jpg
tee-essential-azul-claro.jpg

moletom-rivier-azul-marinho.jpg   (e -bege-areia, -cinza-mescla, -preto)
oxford-classica-branco.jpg        (e -azul-claro, -azul-listrado, -bege)
chino-alfaiataria-bege-areia.jpg  (e -azul-marinho, -caqui, -cinza)
bermuda-riviera-bege-areia.jpg    (e -azul-marinho, -branco, -verde-oliva)
bone-brasao-azul-marinho.jpg      (e -bege, -verde-oliva)
pulseira-couro-couro-marrom.jpg
pulseira-corda-corda-marinho.jpg
pulseira-onix-pedras-onix.jpg
```

### Só tem uma foto por peça?

Use o nome curto, sem a cor — vale para todas as cores daquela peça:

```
polo-heritage.jpg
tee-essential.jpg
moletom-rivier.jpg
oxford-classica.jpg
chino-alfaiataria.jpg
bermuda-riviera.jpg
bone-brasao.jpg
pulseira-couro.jpg
pulseira-corda.jpg
pulseira-onix.jpg
```

## Especificação técnica

- **JPG** (ou PNG), fundo branco ou bem claro
- **Quadrada**, no mínimo 1000 × 1000 px
- Peça centralizada, mesmo enquadramento em todas (catálogo uniforme)
- Até ~400 KB por arquivo de preferência (comprima antes de subir)

## Como publicar depois de adicionar as fotos

```
cd C:\Users\Breno\maison-rivier
git add -A
git commit -m "Adiciona fotos das pecas"
git push
```

Em ~1 minuto o site atualiza sozinho em https://brenokassab.github.io/Maison-Rivier/
