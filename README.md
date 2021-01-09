# CamCracker
Tire fotos da câmera frontal do telefone do alvo ou da webcam do PC apenas enviando um link.
![cam](https://media.discordapp.net/attachments/790798410411802674/797518314153967656/Screenshot_2021-01-09_14_21_51.png?width=690&height=388)

# O que é CamCracker?
<p>CamCracker São técnicas para tirar fotos da câmera do telefone do alvo ou da webcam do PC. CamPhish hospeda um site falso em um servidor PHP integrado e usa ngrok & serveo para gerar um link que encaminharemos para o destino, que pode ser usado na Internet. o site pede permissão para a câmera e, se o alvo permitir, esta ferramenta captura imagens do dispositivo do alvo</p>

## Característicos
<p>Nesta ferramenta, adicionei dois modelos de página da web automáticos para o alvo engajado na página da web para obter mais imagens da cam</p>
<ul>
  <li>Desejo do Festival</li>
  <li>YouTube TV ao vivo</li>
</ul>
<p>basta inserir o nome do festival ou o ID do vídeo do youtube</p>

## Esta ferramenta foi testada em:
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

# Iinstalação e requisitos
<p>Esta ferramenta requer PHP para servidor web, SSH ou link de serviço. Primeiro execute o seguinte comando em seu terminal</p>

```
apt-get -y install php openssh git wget
```

## Instalando (Kali Linux / Termux):

```
git clone https://github.com/CrackerUserModder/CamCracker
cd CamCracker
bash CamCracker.sh
```
### Aviso
<p>CamCracker foi criado para ajudar nos testes de penetração e não é responsável por qualquer uso indevido ou fins ilegais.</p>
<p>CamCracker é inspirado por https://github.com/thelinuxchoice/ Muito obrigado a @thelinuxchoice</p>
