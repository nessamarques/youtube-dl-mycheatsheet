# 📺 Dowload de vídeo ou playlist

Abra o CMD na pasta youtube-dl contendo os arquivos:
-   youtube-dl.exe
-   ffmpeg.exe
-   ffplay.exe
-   ffprobe.exe

e execute:

``` bash

youtube-dl COLOQUEAQUISUAURL

``` 



# 🎧 Dowload de músicas (modelo)

Abra o CMD na pasta youtube-dl contendo os arquivos:
-   youtube-dl.exe
-   ffmpeg.exe
-   ffplay.exe
-   ffprobe.exe

e execute:

```bash
youtube-dl -x --audio-format mp3 --audio-quality 0 --add-metadata --embed-thumbnail --postprocessor-args "-write_id3v1 1 -id3v2_version 3" -o "%(title)s-%(id)s.%(ext)s" COLOQUEAQUISUAURL
``` 
Parâmetros:
-   Apenas áudio (-x);
-   Formato do áudio em MP3 (--audio-format mp3)
-   Melhor qualidade de áudio (--audio-quality 0)
-   Adicionar informações do vídeo como *Nome, Artista e etc.* (--add-metadata)
-   Adiciona a imagem de capa (thumbnail) (--embed-thumbnail)
-   Pós processadores utilziados (--postprocessor-args "-write_id3v1 1 -id3v2_version 3")
-   Utiliza como nome de arquivo o título do vídeo (-o "%(title)s-%(id)s.%(ext)s")
  

## 📒 SOBRE

Guia básico para meus principais usos pessoais do youtube-dl. 

Este documento tem como finalidade servir de referência rápida para consultas futuras nas necessidades gerais.
 
---
## 📝 Documentação original 
Toda a documentação completa pode ser encontrada no repositório oficial do [**youtube-dl**](https://github.com/ytdl-org/youtube-dl)

#  🤵 Autor

Alguma dúvida? fala comigo! 😁

 <sub><b>Paulo Vitor de Souza</b></sub> 
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Paulo_Vitor-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/paulop2-vs/)](https://www.linkedin.com/in/paulop2-vs/) [![Gmail Badge](https://img.shields.io/badge/-paulo225vitor@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:paulo225vitor@gmail.com)](mailto:paulo225vitor@gmail.com) [![Discord Badge](https://img.shields.io/badge/-Paulo%20Vitor%235683-lightgrey?logo=discord&logoColor=white)](https://discord.gg/Pesu4yDT)

