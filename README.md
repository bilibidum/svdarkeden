# Gerenciador de gameserver do jogo DarkEden

O svdarkeden é um gerenciador de serviços para o jogo DarkEden. 
Este projeto permite aos administradores visualizar o status, iniciar e parar o servidor do jogo.

## Instalação

- Baixe o arquivo;
```
https://github.com/bilibidum/svdarkeden.git
```
  
- coloque-o na pasta do servidor (onde está localizado o seu gameserver);
  
- abra o terminal;
  
- execute o comando abaixo para dar permissão de execução ao svdarkeden:
```
sudo chmod a+x svdarkeden
``` 
- edite o arquivo `config.sv` com o caminho do diretório principal que o servidor está instalado.
  
  -- será necessário ter os arquivos bash de inicialização do servidor neste diretório (login1, share1 e game1)
  

## Uso

As opções principais incluem:

Mostra o menu de ajuda
```
svdarkeden --help
```
Inicia o servidor 
```
svdarkeden --start
```		
Para o servidor 
```
svdarkeden --stop
```		
Reinicia o servidor
```
svdarkeden --restart	
```
Mostra o status do servidor
```
svdarkeden --status	
```

## Licença

Este projeto está licenciado sob a Licença Pública Geral GNU versão 3 (GPLv3). 
Esta licença permite a liberdade de usar, modificar e redistribuir este software, desde que quaisquer versões modificadas também sejam compartilhadas sob os mesmos termos. 
A GPLv3 é uma escolha popular para projetos de software que desejam garantir a liberdade para todos os usuários finais.

Para mais detalhes, veja o texto completo da licença em [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).



