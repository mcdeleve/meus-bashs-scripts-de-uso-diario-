Esses sao codigos que criei com auxilio da IA (gemini, ChatGPT e Duckduckgo AI) para dar conta do uso que faço na criação de conteúdos artísticos com compuatdor pela linha de comando abrindo o minimo programas GUI possiveis, automatizando a criação por meio de scripts e comando em programas CLI.

comandos »

» FRASE-IMAGEM;

    ~imagemagick~
    inserir nome do comando seguido de uma farse entre aspas e é criado sempre uma imagem de tamanho 1080x1080 de letra branca e fundo preto com efeito de papel de jornal, fazendo a letra ficar estilizada como em baixa resolução. 
      Uso: /usr/bin/frase-imagem "Sua frase aqui"

GIFMAKER;
    
    ~yt-dl + ffmpeg~
    escolhe trecho de um video do youtube e transforma automaticamente em um arquivo .gif (arquivos grandes!)
    Uso: gifmaker <url> <inicio> <duracao> '<texto>' [nome_arquivo.gif]

HQ-PB-AUTO;
    
    ~imagemagick~
    Transcreve todas imagens de dentro de uma HQ colorida no formato .cbz e a transforma em uma HQ identica mas em preto e branco. 
Uso: /usr/bin/hq-pb-auto arquivo.cbz

HQ-PB-AUTO-CBR;

    ~imagemagick~
Transcreve todas imagens de dentro de uma HQ colorida no formato .cbr e a transforma em uma HQ identica mas em preto e branco. 
Uso: /usr/bin/hq-pb-auto arquivo.cbz

IMAGE-MEME-AUTOMATICO;

    ~imagemagick~
Adapta qualquer imagem - grande ou pequena - ao tamanho vertical stories/reels. 
    Uso: /usr/bin/image-meme-automatico input.jpg output.jpg

IMAGENS-PARA-VIDEO;


~ffmpeg~
    Pega todo e qualquer arquivo de imagem dentro de uma pasta - usa-o por 2.5 segundos cada imagem, soma um arquivo de audio que vc aciona de onde ele começa e cria-se um video automaticamente de tamanho e duração que comporte cada imagem por 2.5 segundos.
USO »  /usr/bin/imagens-para-video /musicas/trilha.mp3 00:01:30

    PAPELJORNAL;
  
  Transforma qualquer imagem em uma versão preto e branco com baixa resolução, onde se assemelha a um jornal antigo.
      USO » comando papeljornal «ENTRA» em seguida escolher nome da imagem. Aceita «TAB» para completar o nome da imagem. 

REPARTIRVIDEO;

~ffmpeg~
Corta todo e qualquer video em intervalo de 20 segundos, numerando as partes por decimais, de maneira ultra rapida, sem reencodar o arquivo.
Uso: /usr/bin/repartirvideo /caminho/do/video.mp4

VIDEO7SEG;

~ffmpeg~
Pega uma imagem e a transforma em um video de 7 segundos, sendo 0,5 segundo de fade in e 0,5 segundo de fade out. 
O nome do arquivo é o mesmo nome da imagem acrescido da extensão de arquivo .mp4. 
Uso: /usr/bin/video7seg imagem.jpg

VIDEO7SEG-AUDIO;

~ffmpeg~
Pega uma imagem e a transforma em um video de 7 segundos, sendo 0,5 segundo de fade in e 0,5 segundo de fade out 
E adiciona uma musica a ser selecionada junto da escolha do inicio da musica, que tera duração automatica de 7 segundos apartir da escolha do ponto de inicio. 
O nome do arquivo é o mesmo nome da imagem acrescido da extensão de arquivo .mp4. 

Exemplo: /usr/bin/video7seg-audio foto.png musica.mp3 01:23.5

VIDEOLOFI;

~ffmpeg~
Transforma um video em alta resolução em um de baixa resolução 320p nas cores preto e branco saindo o OUT automaticamente mediante sufixo _bw. 
Uso: /usr/bin/videolofi arquivo_de_entrada

ZINE-A4-IMAGEMAGICK-AUTO;

~imagemagick~
pega toda e qualquer imagem e transforma seu tamanho de modo que caiba em uma das oito partes de um lado da folha no tamanho A4.
selecione oito imagens e as coloque de modo que esteja pronto para cortar em formato zine, comecando pelo primeiro arquivo que sera a capa.
feito para as imagens geradas com o comando 'frase-imagem' mas funciona com qualquer imagem, mas lembre que pode ficar pequena demais a imagem. 
Uso: /usr/bin/zine top1 top2 top3 top4 bottom1 bottom2 bottom3 bottom4 out.pdf


